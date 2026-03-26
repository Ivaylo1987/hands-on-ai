# AI Learning

Practical, interactive guides for building with AI — each one a self-contained deep dive you can read, share, and reference.

## Guides

| Guide | Description | Link |
|-------|-------------|------|
| **[Building Skills for Claude](./docs/guides/skills/)** | 7-chapter journey from zero to production skill. Covers structure, writing, patterns, testing, and distribution. | [View guide →](https://ivaylo1987.github.io/ai-coding/guides/skills/) |
| *More coming soon* | | |

## How this repo works

```
ai-coding/
├── docs/                    # GitHub Pages serves ONLY this folder
│   ├── index.html           # Landing page
│   ├── 404.html             # Custom 404
│   └── guides/
│       └── skills/
│           └── index.html
├── reference/               # Personal notes, PDFs, images — NOT published
├── README.md
└── LICENSE
```

- **`docs/`** — public guides, served via GitHub Pages. Add a new guide = add a new folder under `docs/guides/`.
- **`reference/`** — private reference material (PDFs, images, notes). Stored in the repo but not served publicly.

No build step, no deploy pipeline.

## Setup (one-time)

1. Push this content to `main`
2. Go to **Settings → Pages → Source**: select `Deploy from branch`, branch `main`, folder `/docs`
3. Your guides are live at `https://ivaylo1987.github.io/ai-coding/`

## Future topics

Some ideas for future guides:
- Building MCP servers
- Prompt engineering patterns
- Claude Code workflows
- AI-assisted code review
- Agent architecture patterns

## About

Built by Ivaylo Hristov — engineering leader exploring how AI changes the way we build software.

Guides are built with Claude and based on official documentation from Anthropic and other AI providers. Each guide is fact-checked against the latest official docs at the time of creation.
