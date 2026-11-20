+++
title = "hVmark is a an opinionated markup language similar to markdown"
description = "News from the world of markdown"
date = 2026-09-06
[taxonomies]
tags = ["News", "markdown", "markup languages", "free", "open source", "hVmark"]
+++

hVmark is a tiny, opinionated markup language made by PJM in Chicago, with strict syntax and zero bloat. While it’s used all over his website, he primarily used it in posts in lieu of hard-coded HTML.

Here’s an example of how it works:

- Bold: `*text*`.
- Emphasis: `/text/` alternatively `%text%`.
- ~Strike~: `-text-`.
- Underline: `_text_`.
- `Code`: `` `text` ``.
- Lists (dotted): one item per line starting with `[+]`.
- Lists (plain): one item per line starting with `[-]`.
- Soft breaks are allowed inside items via `[]`.
- A backslash will escape an inline marker and output the literal symbol.
- Optional TOC: If two or more subheadings are found, a table of contents will be generated. The TOC is automatically placed under the main heading (`<h1>`) at the top of the page if a main heading isn’t present, or at the location of `<!--HV_TOC-->`.

Links and images use the same anchor plus fangs pattern. Links, for example, are defined as `@@https://example.com/^Link text^`. You can leave the fangs empty to use the URL as text, e.g. `@@https://example.com/^^`.

Similarly images are included as `@@img:/path/file.jpg^Caption^`. They are 85% width by default with the caption being optional. A fuller description of an image looks like `@@img:/path/file.jpg[50px|25% left|right|center|blank]^Caption^`.

For the full specification see the website or fork hVmark via the GitHub link below.

**Website**: [hisvirusness.com/hvmark](https://hisvirusness.com/hvmark)

**GitHub**: [github.com/HisVirusness/hvmark/](https://github.com/HisVirusness/hvmark/tree/main/)

*Haven’t found what you’re looking for? Try this site’s list of recommended [markdown editors](/markdown-editors).*