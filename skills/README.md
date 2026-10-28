# Kaze's skills

The skills Kaze ships with. Each is a folder with a `SKILL.md` in the
[Agent Skills](https://agentskills.io) format (a name and description in frontmatter, then the
instructions). Kaze puts them in your Skills on first launch, where you can edit them; an edited
one is never overwritten.

| Skill | What it does |
|---|---|
| [`web-to-markdown`](web-to-markdown/SKILL.md) | Saves a web page as a clean Markdown file |

They're written for Kaze's agent: they read pages through [BrowserMCP](https://github.com/jackwener/BrowserMCP)
(`tab.read()`) and write with Kaze's `save_file`. Another agent with BrowserMCP can use them with
its own way of writing files.

The source of truth is Kaze's own repository; this folder is updated with each release.
