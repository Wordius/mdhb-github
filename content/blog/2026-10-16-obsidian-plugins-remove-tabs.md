+++
title = "Obsidian plugins: Remove Tabs"
description = "If you’re fed up with having lots of tabs open, Remove Tabs solves that. But beware, there are other issues to consider"
date = 2026-10-16
[taxonomies]
tags = ["News", "markdown", "markdown editors", "free", "open source", "Remove Tabs", "plugins", "utilities"]
+++

### The developer says

Remove tabs and the tab bar. Whatever you open replaces what’s currently open, so there is only ever one tab.

- No new tabs: anything that would open a new tab opens in the current one instead. That covers Cmd/Ctrl+click, middle-click, ‘Open in new tab’ and the New tab command.
- Extra tabs are closed: if a tab is created some other way (a saved workspace layout, dragging a file in, another plugin), the plugin keeps the tab you’re looking at and closes the rest.
- No tab bar: the tab bar is hidden in the main editor area and in pop out windows.

The sidebar toggle buttons still work. They float in the note’s header when a sidebar is collapsed. On macOS the header leaves room for the window buttons (close, minimise, full screen), and you can move the window by dragging the empty space beside the note title.

### Features

Remove Tabs leaves the following alone:

- Sidebars keep their tabs. Those tabs are how you switch between File explorer, Search, Outline and so on.
- Splits still work. Each pane holds one note and has no tab bar.
- Popout windows are allowed, each with one note and no tab bar.

### Our view

Remove tabs by all means, but if your concern is about switching tabs – and that’s your sole reason for not liking the feature – Obsidian offers a convenient way to [switch tabs](https://obsidian.md/help/tabs#Switch+to+a+different+tab). Although the ⌃⇧⇥ necessary to return to the previous tab does somewhat require the skills of a contortionist. But before you know it, these shortcuts become part of your muscle memory.

Alternatively, set shortcut keys for ‘Close others’ or ‘Close other tabs to the right’; both are revealed in a popover by right clicking the current tab.

The Remove Tabs plugin also removes the ability of Obsidian’s web viewer to open in a new tab. Instead it opens in the same tab, replacing the open document. It’s worth considering: check if that is the behaviour you are looking to achieve.

#### Links

- [GitHub](https://github.com/kuberrr0/obsidian-remove-tabs)
- [Obsidian Community Plugins](https://community.obsidian.md/plugins/remove-tabs)

*Haven’t found what you’re looking for? Try this site’s list of recommended [markdown editors](/markdown-editors/).*