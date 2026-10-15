# Learn Like Elementary School

A portable Agent Skill that turns college-level study material into clear lessons, precise term cards, worked examples, and exercises that progress from easy recall to challenging problem solving.

The skill uses the open `SKILL.md`-based Agent Skills format. It is instruction-only: it needs no API keys, package installation, or external services.

## Install

Clone or download this repository, then place the folder in a skill directory supported by your agent. Keep the folder name `learn-like-elementary-school` and keep `SKILL.md`, `references/`, and `agents/` together.

Common locations include:

- Codex, repository scope: `.agents/skills/learn-like-elementary-school/`
- Codex, user scope: `~/.codex/skills/learn-like-elementary-school/`
- Claude Code, repository scope: `.claude/skills/learn-like-elementary-school/`
- Claude Code, user scope: `~/.claude/skills/learn-like-elementary-school/`

For another Agent Skills-compatible tool, add the folder to that tool's skills or capabilities directory. Check the tool's current documentation because installation locations can change.

## Use

Attach or paste your notes, slides, textbook pages, assignment, or study guide, then ask:

```text
Use $learn-like-elementary-school to teach me this material. Start with the big picture, explain the key terms, and quiz me from easy to hard. Do not show solutions until I answer.
```

You can also ask for a specific mode:

```text
Turn this chapter into a study guide and 15-minute practice session.
```

```text
Tutor me Socratically on these lecture slides. Ask one question at a time and adapt to my answers.
```

```text
Make a mock exam from this material, with hints and a separate worked answer key.
```

## What it produces

- A dependency-ordered roadmap of the material
- Knowledge maps, prerequisite diagrams, process flows, and concept comparisons
- Plain-language explanations that preserve college-level precision
- Term cards with simple and formal meanings
- Worked examples and common mistakes
- Recall, explanation, application, problem-solving, and challenge exercises
- Progressive hints, reasoned solutions, and adaptive follow-up practice
- Larger, varied exercise banks delivered in manageable batches
- Exam coverage maps, mock exams, grading rubrics, and targeted retry sets

## Exam preparation

For a deeper course review, provide the study materials and—when available—the syllabus, learning objectives, past exams, permitted formula sheet, and exam format. Then ask:

```text
Use $learn-like-elementary-school to prepare me thoroughly for this exam. Build a coverage map, diagnose me across every major topic, teach weak areas in depth, and then give me mixed practice and a timed mock exam. Track my mistakes and do not mark a topic exam-ready without evidence from my answers.
```

The skill will work in rounds, so students receive substantial practice without being overwhelmed by one enormous response.

## Knowledge diagrams

The skill can connect ideas visually using concept maps, prerequisite maps, process flows, cause-and-effect maps, comparison diagrams, and system diagrams. It uses portable Mermaid when supported and provides a readable text explanation or fallback.

```text
Use $learn-like-elementary-school to explain this chapter and create a diagram showing how the major concepts depend on and relate to one another.
```

Diagrams can also become exercises: learners can fill missing concepts, label relationships, reconstruct a map from memory, or find an incorrect connection.

## Design principle

“Elementary school” describes the clarity of the teaching, not the difficulty of the subject. The skill keeps the original notation, assumptions, caveats, and technical vocabulary while explaining them in smaller, more concrete steps.

---

# 中文说明

`Learn Like Elementary School` 是一个可移植的 Agent Skill。它能把大学课程的学习材料拆解成清晰易懂的课程、术语卡片、分步示例，以及从基础记忆到高难度问题解决的练习。

这里的“像小学生一样学习”指的是讲解方式足够清楚、具体和循序渐进，并不代表降低大学课程的难度。Skill 会保留原材料中的专业术语、公式、符号、前提条件和重要例外，同时用更小的步骤解释它们。

该 Skill 使用以 `SKILL.md` 为核心的开放 Agent Skills 格式。它只包含指令和参考资料，不需要 API Key、额外软件包或外部服务。

## 安装

克隆或下载本仓库，然后把整个文件夹放入 AI Agent 支持的 Skills 目录中。请保留文件夹名称 `learn-like-elementary-school`，并确保 `SKILL.md`、`references/` 和 `agents/` 位于同一文件夹内。

常见安装位置：

- Codex，项目级：`.agents/skills/learn-like-elementary-school/`
- Codex，用户级：`~/.codex/skills/learn-like-elementary-school/`
- Claude Code，项目级：`.claude/skills/learn-like-elementary-school/`
- Claude Code，用户级：`~/.claude/skills/learn-like-elementary-school/`

对于其他兼容 Agent Skills 的工具，请将文件夹放入对应工具的 Skills 或 capabilities 目录。不同工具的安装位置可能发生变化，请同时查看该工具的最新文档。

## 使用方法

上传或粘贴课堂笔记、讲义、幻灯片、教材章节、作业或复习资料，然后输入：

```text
使用 $learn-like-elementary-school 教我这份学习材料。先讲整体框架，再解释重要术语，然后从简单到困难测试我。在我作答之前不要显示答案。
```

也可以指定学习模式：

```text
把这一章整理成学习指南，并安排一次 15 分钟的练习。
```

```text
用苏格拉底式教学带我学习这些课件。一次只问一个问题，并根据我的回答调整难度。
```

```text
根据这些材料制作一份模拟考试，提供分层提示，并把详细答案单独放置。
```

## Skill 可以生成什么

- 按知识依赖关系排列的学习路线
- 知识关系图、先修知识图、流程图和概念对比图
- 简单易懂但保持大学课程严谨度的讲解
- 同时包含通俗解释和正式定义的术语卡片
- 分步骤示例和常见错误分析
- 记忆、解释、应用、问题解决和挑战级练习
- 渐进式提示、完整推理答案和自适应后续练习
- 分批提供的大型多样化题库
- 考试知识覆盖表、模拟考试、评分标准和针对性重练题

## 考试准备模式

如果希望进行深入的考试复习，请提供学习材料；如果可以，也请提供教学大纲、学习目标、往年试题、允许使用的公式表和考试形式。然后输入：

```text
使用 $learn-like-elementary-school 帮我全面准备这次考试。建立知识覆盖表，诊断我对每个主要主题的掌握程度，深入讲解薄弱部分，然后给我混合练习和限时模拟考试。记录我的错误；没有我的作答证据时，不要把任何主题标记为“已达到考试要求”。
```

Skill 会分轮进行复习：先诊断，再补弱项，然后进行混合练习、模拟考试和针对性重练。这样既能提供足够多的练习，也不会一次给学生过多内容。

## 知识关系图

Skill 可以使用概念图、先修知识图、流程图、因果关系图、对比图和系统关系图，把分散的知识连接起来。在支持 Mermaid 的界面中会优先生成 Mermaid 图；同时也会提供普通文字说明或纯文本版本，确保图表无法渲染时仍然可以学习。

```text
使用 $learn-like-elementary-school 讲解这一章，并画一张知识关系图，展示主要概念之间的依赖关系和联系。
```

知识图也可以用于练习，例如填写缺失概念、补充关系标签、根据记忆重建图表，或者找出图中错误的连接。
