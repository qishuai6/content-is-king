# Content Is King

`Content Is King` is a Codex skill that turns the article's method into one reusable workflow with three capabilities inside a single skill:

- Information Gathering
- Angle Design
- Content Creation

The skill is based on the article:
- [The Viral Playbook](https://www.uisdc.com/the-viral-playbook)

## What This Skill Does

This skill helps Codex turn a topic, link, note, trend, draft, or rough idea into stronger content output.

Instead of stopping at information summary, it pushes the work through a story-first content method:

1. Gather better material
2. Find a stronger angle
3. Create content with rhythm

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

## Files

- `SKILL.md`: main skill instructions
- `agents/openai.yaml`: UI metadata for Codex
- `references/content-is-king-core.md`: distilled method and review checklist

## Installation

If you want Codex to discover this skill automatically, place it under:

```bash
~/.codex/skills/content-is-king
```

On this machine it is already linked there.

## Example Prompts

```text
Use $content-is-king to gather material for this topic before writing.
Use $content-is-king to give me 5 stronger angles for this idea.
Use $content-is-king to turn this topic into a complete article.
Use $content-is-king to rewrite this draft with better rhythm and narrative movement.
```

## Design Principles

- Treat content as storytelling, not information forwarding
- Prefer cross-domain input over narrow niche repetition
- Reject the first obvious angle
- Build drafts with rising beats
- Keep the value stance grounded and trustworthy

## Language

The current skill body is written in English with Chinese capability labels where they improve direct usability for Chinese content work.

For the Chinese README, see [README.zh-CN.md](./README.zh-CN.md).
