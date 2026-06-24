# Content Is King

`Content Is King` is a Codex skill for story-first content creation.

It turns the article's method into one reusable workflow with three capabilities inside a single skill:

- Information Gathering
- Angle Design
- Content Creation

The skill is based on the article:
- [The Viral Playbook](https://www.uisdc.com/the-viral-playbook)

Chinese README: [README.zh-CN.md](./README.zh-CN.md)

## Why This Exists

Most content systems are good at summarizing information and bad at making content feel worth reading or sharing.

This skill is built around a stricter assumption:

- raw information is not content
- the angle matters more than the first draft
- better inputs create better angles
- rhythm is part of the value, not just decoration

The goal is to help Codex produce content that feels more like a real point of view and less like organized notes.

## What This Skill Does

This skill helps Codex turn a topic, link, note, trend, draft, or rough idea into stronger content output.

Instead of stopping at information summary, it pushes the work through a story-first content method:

1. Gather better material
2. Find a stronger angle
3. Create content with rhythm

## Who This Is For

This skill is useful when you are:

- building a topic bank
- planning articles or video scripts
- rewriting flat drafts
- improving hooks and titles
- turning niche information into broader story-driven content
- working in Chinese content workflows but still wanting a clean Codex skill structure

## Three Capabilities

### 1. Information Gathering

Use this step to expand the material set before writing.

Outputs can include:
- topic maps
- source packs
- audience tension lists
- cross-domain inspiration

### 2. Angle Design

Use this step to avoid the obvious first take and generate stronger framing.

Outputs can include:
- angle options
- hook directions
- title directions
- narrative reframes

### 3. Content Creation

Use this step to turn the selected angle into an outline, article, post, or script.

Outputs can include:
- outlines
- rewritten drafts
- short posts
- longform articles
- scripts

## Workflow Logic

This skill can run in two modes:

### Single-step mode

Use only one capability when the user asks for one specific task, such as:
- only gather materials
- only find angles
- only rewrite a draft

### Full-workflow mode

Run the three capabilities in order when the user wants end-to-end help:

1. widen the input field
2. select the strongest angle
3. write with narrative movement

## Example Prompts

```text
Use $content-is-king to gather material for this topic before writing.
Use $content-is-king to give me 5 stronger angles for this idea.
Use $content-is-king to turn this topic into a complete article.
Use $content-is-king to rewrite this draft with better rhythm and narrative movement.
Use $content-is-king to run the full workflow from material gathering to final draft.
```

## Installation

If you want Codex to discover this skill automatically, place it under:

```bash
~/.codex/skills/content-is-king
```

If you are installing from this repository manually:

```bash
ln -s /absolute/path/to/content-is-king ~/.codex/skills/content-is-king
```

On this machine it is already linked there.

## Repository Structure

```text
content-is-king/
├── SKILL.md
├── LICENSE
├── README.md
├── README.zh-CN.md
├── agents/
│   └── openai.yaml
└── references/
    └── content-is-king-core.md
```

## Files

- `SKILL.md`: main skill instructions
- `agents/openai.yaml`: UI metadata for Codex
- `references/content-is-king-core.md`: distilled method and review checklist

## Design Principles

- Treat content as storytelling, not information forwarding
- Prefer cross-domain input over narrow niche repetition
- Reject the first obvious angle
- Build drafts with rising beats
- Keep the value stance grounded and trustworthy

## Output Style

By default, the skill tries to produce:

- clearer narrative tension
- more defensible but less obvious angles
- stronger movement from opening to ending
- more usable artifacts such as angle lists, outlines, scripts, and rewrites

## Notes

- The current skill body is written in English with Chinese capability labels where they improve direct usability for Chinese content work.
- The repository focuses on the skill itself, not a broader template, plugin, or content framework.

## License

This project is released under the [MIT License](./LICENSE).

For the Chinese README, see [README.zh-CN.md](./README.zh-CN.md).
