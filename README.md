# Shimmering Focus ⟡

![](https://img.shields.io/github/v/release/chrisgrieser/shimmering-focus?label=Latest%20Release&style=plastic)

<img src="https://raw.githubusercontent.com/chrisgrieser/shimmering-focus/main/dual-theme-screenshot.png" alt="Screenshot">

## Features & Design Principles

### Minimalistic
- Removes as much clutter as possible – the theme is intended for users mainly using keyboard shortcuts and/or the command palette.
- Status bar, header bar, and collapse icons become visible when hovering
- Hides close button in the settings menu. Use `Esc` or click outside the menu area to leave the menu. 
- The settings can still be accessed via `cmd + ,` or `ctrl + ,`.
- You can permanently re-enable all hidden elements by using the [Style Settings Plugin](https://github.com/mgmeyers/obsidian-style-settings/).

<img src="https://user-images.githubusercontent.com/73286100/131692972-e523f2d4-40c7-452c-83ac-a7f2fbd546ae.gif" alt="headerbar visible on hover" width=50%>

### Numerous Useful Extra Features
- **Pseudo-Admonition**: `h6` blocks will become a pseudo-admonition box (only works with one-liners though)
- **Multi-Color-Highlighting**: surround highlights with `*` or `**` for alternative highlight colors (thanks to @Atlas for this!)
- **Pseudo-Spoiler-Tags**: Emphasized Strikthroughs (`*~~spoiler~~*`) will selectively hide text, except when hovered or the active line.
- Click & hold on an image to zoom
- Relationship lines in unordered lists & file explorer
- Wrapping of text in the file explorer
- Active line highlighting
- Material Icons to indicate folder and file types
- Display of the language of a code block in Preview Mode
- Spellcheck disabled in blockquotes, code blocks, and YAML frontmatter (only produces false positives there)
- **Annotation tags** (see below)
- **Max View**: Readable line length and smaller images when left sidebar is shown, full length and full-size images when sidebar is hidden. Useful when dealing with big tables. (Requires `Readable line length` editor setting to be *enabled*.)

<img src="https://user-images.githubusercontent.com/73286100/138562271-2f7d3589-d580-49e4-bea6-ca3e3004ab78.gif" alt="Promo Max View" width=60%>


### Particularly Suited Academics
- [Pandoc Citations](https://pandoc.org/MANUAL.html#citations-in-note-styles) (`[@citekey]`) and footnotes are visually emphasized
- the alt-text of images is used as caption text, in line with Pandoc's conversion behavior
- Lots of Styling specifically for the [Longform Plugin](https://github.com/kevboh/longform), among other things justified & hyphenated text, and [Crimson Pro](https://fonts.google.com/specimen/Crimson+Pro) as an easy-to-read serif font
- **Annotation tags**: type of of the following eight tags (e.g. `#definition`) to get a colored annotation tag. Also works in Edit Mode. Intended for Annotations when reading academic papers. You can add your own via adding a snippet [using this template](https://github.com/chrisgrieser/shimmering-focus/blob/main/annotation-tag-template.css).
<img width=12% alt="Screenshot 2021-10-23 16 18 49" src="https://user-images.githubusercontent.com/73286100/138560326-c1bd22c4-dda9-4f92-8edc-ba736524ea75.png">

### Condensed Display of Information
- Uses screen real estate more efficiently to display more information. Useful for Smaller Screens, Split Screens, Bigger Font sizes or simply if want to see more information without having to scroll.
- Smaller images in Preview Mode (click & hold an image to zoom, or use the aforementioned "Max View").

<img width=40% alt="Screenshot 2021-10-23 17 06 22" src="https://user-images.githubusercontent.com/73286100/138561771-1067d041-eeb2-4dfe-8d79-f7fa754ca419.png">

### Tailored for Maximum Readability
- increased contrast throughout, especially with the [annoying grey font on light grey background](https://forum.obsidian.md/t/enhance-default-color-contrast-of-the-icons/23045/3)
- decreased font size variation to increase readability & information density
- at the same time increased distinguishability of different classes through subtle variation in typeface, font style, or backgrounds
- easy-to-read fonts for every usecase
  - [iA Writer Quattro](https://github.com/iaolo/iA-Fonts/tree/master/iA%20Writer%20Quattro) for regular text.
  - [Input Mono](https://input.djr.com/) as monospace font for code
  - [Optima](https://en.wikipedia.org/wiki/Optima) as humanist heading font
  - [Crimson Pro](https://fonts.google.com/specimen/Crimson+Pro) as serif font for longform projects
- minor coloring of bold in dark mode to make it more readable, since bold in dark mode is harder to distinguish form normal text than  in light mode
- slightly thicker lines (icons, hr, tables, etc.)
- Dark Mode for PDFs (when using the theme in dark mode)

### Subtle Design
- Stylistically, the theme pretty much follows Obsidian's default theme, with mostly suble changes – like the eponymous shimmering green as secondary accent.

## Style Settings Plugin
- This themes supports the [Style Settings Plugin](https://github.com/mgmeyers/obsidian-style-settings/) for customization.
- **If this theme is *too* minimalistic for you, you can use this plugin to re-enable hidden elements.**

<img width=40% alt="Screenshot 2021-10-21 00 52 35" src="https://user-images.githubusercontent.com/73286100/138183481-e9a07d48-5db9-40a0-ae4e-dbfa4f4ed345.png">

## Tested with & styled for the following Plugins

**Community Plugins**
- Longform
- Kanban (right click to edit cards)
- Calendar
- Sliding Panes (enable `Swap Rotated Header Direction`)
- Advanced Tables
- Templater
- Ozan's Image in Editor
- MySnippets
- Another Quick Switcher Plugin
- CodeMirror Options
- Drag and Drop Blocks
- Recent Files
- Quick Explorer (re-enable the title bar for breadcrumbs)
- Map of Content
- Dangling Links
- Advanced Cursors

**Core Plugins**
- File Explorer
- Graph View
- Starred
- Tag Pane
- Backlinks
- Outgoing Links
- Outline
- Search Pane
- Command Palette
- Quick Switcher
- Page Preview (Popover)
- File Recovery

## Installation
You can find *Shimmering Focus* in Obsidian's community themes browser under `Settings ➞ Appearance ➞ Themes`.

## Credits
For help and/or CSS snippets, thanks to:
- **@SlRvb**
- **@javalent**
- @kepano
- @Mara
- @Chetachie
- @Atlas
- @jdaniel
- @só erick mesmo
- @NothingIsLost
- @phibr0
- @Damian Korcz

This theme has been created by @pseudometa#9546 ([Discord](https://discord.gg/veuWUTm)) aka [@pseudo_meta (Twitter)](https://twitter.com/pseudo_meta) aka Chris Grieser (rl). If you find this theme to be useful, feel free to donate [via PayPal](https://www.paypal.com/paypalme/ChrisGrieser). In my day job, I am a PhD student in sociology, studying the governance of the app economy. If you are interested in this subject, check out [my academic homepage](https://chris-grieser.de/) and get in touch.
