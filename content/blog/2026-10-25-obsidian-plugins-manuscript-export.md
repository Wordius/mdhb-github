+++
title = "Obsidian plugins: Manuscript Export"
description = "News from the world of markdown"
date = 2026-10-25
[taxonomies]
tags = ["markdown", "markdown editors", "Obsidian", "plugins", "Manuscript Export", "EPUB"]
+++

### The developer says…

Export a book manuscript written in Obsidian to a clean, valid EPUB, including one-command export of [Longform](/blog/obsidian-plugins-longform) projects. No separate paid tool, no leaving Obsidian.

If you write in Longform, you already have your scenes in order. Run `Export Longform project to EPUB` and you get a properly structured EPUB of that project – scenes exported in your Longform order (not filename order), with the project’s title as the book title. Multiple projects in one vault? You’ll get a picker. Single-file Longform projects are split into chapters on `#` headings.

No Longform? Use `Export manuscript to EPUB` with a plain folder of chapter notes (one note per chapter, natural-sort filename order – Chapter 2 correctly sorts before Chapter 10).

### Features

If you write long-form fiction or nonfiction in Obsidian, getting a properly formatted EPUB out the other end usually means a separate paid tool (Vellum, Atticus) or a fragile export chain. This handles the common case cleanly:

- Wiki links (`[[Note]]`, `[[Note|Display text]]`) render as plain text – a reader doesn’t care about your internal note names.
- Image embeds (`![[cover.png]]`) are embedded directly into the EPUB.
- Scene breaks (`***` or `---` on their own line) render as a centred divider.
- YAML front matter is stripped – metadata never leaks into your book.
- Callouts (`> [!note] ...`) are stripped entirely, not rendered – they’re almost always private author annotations (reminders, continuity notes), not content meant for a reader.
- Plain blockquotes (no `[!type]` marker) render normally, for genuine in-story quotes.
- Standard **bold**/_italic_ formatting.

Chapter titles come from a note’s `title:` front matter field, its leading `# Heading` or its filename – in that order.

### Our view

Manuscript Export promises to rid us of any reliance we might have on paid tools. That can only be good thing, right? Well, for small tools like this, such as transforming one document type into another, I would say yes.

#### Links

- [GitHub](https://github.com/dr3pi/obsidian-manuscript-export) 
- [Obsidian Community Plugins](https://community.obsidian.md/plugins/manuscript-export)
