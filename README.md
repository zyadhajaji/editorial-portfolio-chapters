# Editorial Portfolio Chapters

Editorial Portfolio Chapters is an agent skill for creative-studio, agency, photographer, artist and portfolio websites where the work leads the story. Your coding agent builds the page as a sequence of distinct editorial chapters, like turning the pages of a magazine, so the work creates desire before the studio explains itself.

## How it works

When you ask for a studio or portfolio site, your agent stops reaching for the usual hero, features and team-card grid. Instead it follows a story:

1. Open with one strong campaign image and a concise positioning line.
2. Move straight into selected work, treating each case study as a new magazine cover.
3. Explain the studio's point of view only after the work has earned attention.
4. Use oversized service typography as the handoff from proof to contact.
5. End with a high-contrast contact chapter that feels final, not appended.

The visual system is a near-black frame, warm white, and one muted color field per project, set on a 12-column grid with a grotesk display face. Signature interactions include a masked project panel reveal and an oversized service handoff, with motion defaults tuned for an editorial pace: 160 to 220ms for control feedback, 500 to 760ms for entrances, parallax under 5%, and no scroll hijacking.

It also ships a worked interaction prompt pack covering the loader, pinned chapters, archive player, inspection views, sticky stacks and footer. Reuse the motion logic, never the reference identity, copy or imagery.

## Installation

### Claude Code (plugin marketplace)

```bash
/plugin marketplace add zyadhajaji/editorial-portfolio-chapters
```

```bash
/plugin install editorial-portfolio-chapters@editorial-portfolio-chapters
```

### Claude Code (manual)

```bash
git clone https://github.com/zyadhajaji/editorial-portfolio-chapters.git
cp -r editorial-portfolio-chapters/skills/editorial-portfolio-chapters ~/.claude/skills/
```

### Codex, Cursor and other agents

Copy `skills/editorial-portfolio-chapters` into your agent's skills folder (for Codex, `~/.codex/skills/`), or point the agent at `skills/editorial-portfolio-chapters/SKILL.md`.

### Verify installation

Ask your agent for something like "Redesign my photography studio's portfolio site". It should open with the work, not an about section.

## What's inside

- `skills/editorial-portfolio-chapters/SKILL.md`: story structure, visual system, page composition, signature interactions, motion defaults and validation.
- `skills/editorial-portfolio-chapters/ARTICLE.md`: the interaction prompt pack, a worked example of turning one editorial portfolio into portable motion prompts.
- `skills/editorial-portfolio-chapters/REFERENCES.md`: source references.

## Philosophy

- **Work before words.** Proof first, positioning second.
- **Chapters, not cards.** Each section changes scale and color for a reason.
- **Restraint reads as confidence.** Hairline rules, almost no shadow, slow and stable motion.
- **Original content only.** Keep the pacing and hierarchy of references, replace every brand, image and claim.

## Pairs well with

- [build-awwwards-quality-sites](https://github.com/zyadhajaji/build-awwwards-quality-sites)
- [no-ai-design-slop](https://github.com/zyadhajaji/no-ai-design-slop)

## Updating

```bash
/plugin update editorial-portfolio-chapters
```

## License

MIT License. See the [LICENSE](LICENSE) file for details.
