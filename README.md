# style-terminal-navy

The readablecode "terminal navy" house design system: navy terminal surfaces,
monospace type everywhere, a green prompt accent, amber highlights, and
`// section` headers. Shared by the readablecode portfolio site
(site.tinkernet.me), [load-log](https://github.com/ReadableCode/load-log), and
future projects.

## Contents

| File | Purpose |
|---|---|
| `STYLE.md` | The full spec and source of truth: tokens, typography, component patterns, chart rules (including the CVD-validated two-series palette). |
| `tokens.css` | The same values as CSS custom properties, ready to copy into a project. |
| `SKILL.md` | Claude Code skill wrapper — drop this directory into a skills folder to have agents apply the style automatically. |
| `previews/*.html` | Self-contained reference renderings (colors, type, components, charts). Open in a browser when unsure how a piece should look. |

## Using it in a project

Copy `tokens.css` into the project, then paste the summary block from the
"Applying this in a new project" section of `STYLE.md` into the project's
CLAUDE.md so agents keep new UI on-style.
