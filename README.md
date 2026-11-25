<!-- by: Claude Code (Opus 5.5), 2026-11-25, sources: companion-plugin/quantum-book-companion/skills/quantum-book-companion/SKILL.md; config/properties.yml -->
# Quantum Book Companion

A reader's guide to *The Atlas of Quantum Science and Technology* (Ouviaj LLC, 2026). Ask Claude about a quantum concept, experiment, device, algorithm or technology claim. The companion places the subject in the atlas's 80 topics and 13 parts, then explains it step by step: what it is, how it is used, a closer look with a worked example, and sources for further reading.

## Install

In Claude Code 2.1.275 or later:

```
/plugin install quantum-book-companion --marketplace bilgehanerman/taoqst-book-companion
```

Or from a shell:

```
claude plugin marketplace add bilgehanerman/taoqst-book-companion
claude plugin install quantum-book-companion@ouviaj-quantum
```

## Use

After installing, ask a quantum question, or invoke the skill directly:

```
/quantum-book-companion:quantum-book-companion Explain superposition with a two-path experiment.
```

Other questions to try:

- Compare quantum key distribution and post-quantum cryptography.
- What evidence should I look for in a quantum advantage claim?
- Where does quantum error correction fit in the atlas, and what should I read first?

## What it contains

- `skills/quantum-book-companion/SKILL.md`: how the companion explains topics and weighs technology claims.
- `skills/quantum-book-companion/references/atlas-map.md`: the atlas's topics in reading order, each with a one-line definition and a link to its companion page on [ouviaj.com](https://ouviaj.com/the-atlas-of-quantum-science-and-technology/).

The plugin is Markdown only. It runs no code, collects no data, and sends nothing anywhere. When Claude has web search, the skill asks it to check time-sensitive claims against primary sources.

## License

Copyright © 2026 Ouviaj LLC. Licensed under [Creative Commons Attribution-NonCommercial-NoDerivatives 4.0 International](https://creativecommons.org/licenses/by-nc-nd/4.0/). See `LICENSE`.
