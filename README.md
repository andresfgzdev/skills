# andresfgzdev skills

A Claude Code plugin marketplace with my agent skills. Each skill lives in its own repository, with its own docs, tests and changelog.

| Skill | What it does |
|---|---|
| [explain-it](https://github.com/andresfgzdev/explain-it) | Explains how a feature, API or multi-system flow works, in ASD-STE100 (Simplified Technical English) at Low, Medium or High depth. It draws the whole system as an SVG overview and an interactive walkthrough. |
| [tidy-tree](https://github.com/andresfgzdev/tidy-tree) | Finds and fixes where code lives in JS/TS repositories (grab-bag files, duplicates, misplaced and dead files, layer-crossing imports), following each project's own architecture. |

## Install

```text
/plugin marketplace add andresfgzdev/skills
/plugin install explain-it@andresfgzdev
/plugin install tidy-tree@andresfgzdev
```

Each skill also installs on its own, or into any agent that reads Agent Skills through the [`skills`](https://github.com/vercel-labs/skills) CLI. See each repository's README.

## License

[MIT](LICENSE)
