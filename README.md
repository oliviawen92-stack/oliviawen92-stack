# Olivia's Agent Skills

Reusable agent skills for turning messy personal and work inputs into useful artifacts.

This space is a public index for skills I build, use, and maintain. Each skill should be source-aware, honest about its limits, and designed to produce editable, reusable outputs rather than one-off screenshots or opaque summaries.

## Skills

| Skill | What it does | Status |
| --- | --- | --- |
| [book-to-feishu-visual-notes](https://github.com/oliviawen92-stack/book-to-feishu-visual-notes) | Turns books into Feishu/Lark visual reading notes with source-boundary handling and one editable whiteboard per core viewpoint. | Ready to publish |

## Principles

- **Source honesty first.** If a full source is unavailable, the skill should say so and produce a public-information framework version rather than pretending to have read the full material.
- **Editable artifacts over screenshots.** Prefer Feishu/Lark docs, whiteboards, Markdown, and other formats the user can continue editing.
- **One idea per visual.** Avoid cramming a whole book, meeting, or strategy into one giant diagram when multiple focused visuals work better.
- **Useful defaults, explicit boundaries.** Make the first run good enough, while clearly saying what extra input would improve fidelity.

## Installation Pattern

Most skills in this space follow the standard Codex skill layout:

```text
skill-name/
  SKILL.md
  agents/
    openai.yaml
  references/
    workflow.md
```

Install a skill by pointing your agent's skill installer at the repository root.

## Roadmap

- Publish `book-to-feishu-visual-notes`.
- Add a reusable Feishu report/briefing skill.
- Add a personal knowledge-base ingestion skill.
