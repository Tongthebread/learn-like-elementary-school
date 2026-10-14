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
- Plain-language explanations that preserve college-level precision
- Term cards with simple and formal meanings
- Worked examples and common mistakes
- Recall, explanation, application, problem-solving, and challenge exercises
- Progressive hints, reasoned solutions, and adaptive follow-up practice

## Design principle

“Elementary school” describes the clarity of the teaching, not the difficulty of the subject. The skill keeps the original notation, assumptions, caveats, and technical vocabulary while explaining them in smaller, more concrete steps.
