# Shimmering Focus ⟡

A minimalistic [Obsidian](https://obsidian.md/) theme focused on readability and condensed information display.

<!-- manually updated-->
![](https://img.shields.io/badge/downloads-4873-6E4E9B?style=plastic) ![](https://img.shields.io/github/last-commit/chrisgrieser/shimmering-focus?style=plastic)

<img src="https://raw.githubusercontent.com/chrisgrieser/shimmering-focus/main/dual-theme-screenshot.png" alt="Promo Screenshot">

## Table of Content
<!-- MarkdownTOC -->

- [Features](#features)
  - [Hiding/Showing UI Elements](#hidingshowing-ui-elements)
  - [Annotation Tags](#annotation-tags)
  - [Max View](#max-view)
  - [Image-related Features](#image-related-features)
  - [Fine-tuned Spellcheck](#fine-tuned-spellcheck)
  - [Multi-Color-Highlighting & Spoiler Syntax](#multi-color-highlighting--spoiler-syntax)
  - [Features for Academic Work](#features-for-academic-work)
  - [Further Features](#further-features)
- [Design Principles](#design-principles)
  - [Extreme Minimalism](#extreme-minimalism)
  - [Condensed Display of Information](#condensed-display-of-information)
  - [Maximum Readability](#maximum-readability)
  - [Subtle Design](#subtle-design)
- [Customization](#customization)
- [Plugin Compatibility](#plugin-compatibility)
  - [List of Compatible Plugins](#list-of-compatible-plugins)
  - [Instructions for specific Plugins](#instructions-for-specific-plugins)
- [Installation](#installation)
- [Contribute](#contribute)
- [Credits](#credits)
  - [About the Developer](#about-the-developer)
  - [Donations](#donations)
  - [Thanks](#thanks)

<!-- /MarkdownTOC -->

## Features

### Hiding/Showing UI Elements
- The Status bar, Header bar, and collapse arrows become visible upon hovering.
- You can re-enable all hidden elements by using the [Style Settings Plugin](#Customization).

💡 The settings can still be accessed via `cmd + ,` or `ctrl + ,`.

<img src="https://user-images.githubusercontent.com/73286100/131692972-e523f2d4-40c7-452c-83ac-a7f2fbd546ae.gif" alt="headerbar visible on hover" width=50%>

### Annotation Tags
Type one of the following eight tags (e.g. `#definition`) to get a colored annotation tag. Also works in Edit Mode. Intended for Annotations when reading academic papers.

<img width=12% alt="Screenshot 2021-10-23 16 18 49" src="https://user-images.githubusercontent.com/73286100/138560326-c1bd22c4-dda9-4f92-8edc-ba736524ea75.png">

💡 You can add your own Annotation Tags via adding a snippet [using this template](https://github.com/chrisgrieser/shimmering-focus/blob/main/annotation-tag-template.css).

### Max View
- By default, the theme uses readable line length as well as smaller images & PDFs when the left sidebar is visible. __When it is hidden, line length is extended to full length__, and images & PDFs to full size. (Requires `Readable line length` editor setting to be *enabled*.)
- Useful when dealing with big tables or many images.

💡 You can turn this feature off or adjust the size of images & PDFs with the [Style Settings Plugin](#Customization).

<img src="https://user-images.githubusercontent.com/73286100/138562271-2f7d3589-d580-49e4-bea6-ca3e3004ab78.gif" alt="Promo Max View" width=60%>

### Image-related Features
- Click & hold an image to zoom.
- Alt Text is automatically used as image caption.
- You can set default Image Size via Style Settings Plugin.

### Fine-tuned Spellcheck
Using the [Style Settings Plugin](#Customization), you can deactivate the spellcheck in specific areas like YAML or blockquotes.

<img src="https://i.imgur.com/9XPEUQq.png" alt="Spellcheck settings" width=50%>

### Multi-Color-Highlighting & Spoiler Syntax
- Surround highlights with `*` or `**` for alternative highlight colors (e.g. `*==cyan==*`).[^2]
- You can use the [Extra Markdown Commands Plugin](https://github.com/chrisgrieser/obsidian-extra-md-commands) to get hotkeys for them.
- Spoiler Syntax: Emphasized Strikethroughs (`*~~spoiler~~*`) will selectively hide text, except when hovered or the active line.

### Features for Academic Work
- [Pandoc Citations](https://pandoc.org/MANUAL.html#citations-in-note-styles) (`[@citekey]`) and footnotes are visually emphasized
- The alt-text of images is used as caption text, in line with Pandoc's conversion behavior
- Extensive Styling specifically for the [Longform Plugin](https://github.com/kevboh/longform), among other things justified & hyphenated text, and [Crimson Pro](https://fonts.google.com/specimen/Crimson+Pro) as an easy-to-read serif font

### Further Features
- **Pseudo-Admonition**: `h6` blocks will become a pseudo-admonition box (only works with one-liners though)
- Relationship lines in lists & File Explorer
- Active line highlighting
- Dark Mode for PDFs[^3] (when using the theme in dark mode)
- Styled [progress bars (`<progress>`)](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/progress)
- Resizable Graph View Controls[^1] ([See this explanation image.](https://media.discordapp.net/attachments/855181471643861002/909861241055481857/lmao.gif))

## Design Principles

### Extreme Minimalism
- This theme is mainly intended for experienced users using mainly the keyboard for navigation.
- As much clutter as possible is removed, letting you focus on content & information that matters.
- You can re-enable all hidden elements by using the [Style Settings Plugin](#Customization).
- 💡 The settings can still be accessed via `cmd + ,` or `ctrl + ,`.

### Condensed Display of Information
- Screen real estate is used much more efficiently to display more information at the same time.
- Useful for smaller screens, Split Screens, bigger font sizes or simply if want to see more information without having to scroll.
- Smaller images/PDFs. Click-and-Hold or use the [Max View Feature](#Max-View) to enlarge them again.
- Wider input boxes

<img width=60% alt="Screenshot 2021-10-23 17 06 22" src="https://user-images.githubusercontent.com/73286100/138561771-1067d041-eeb2-4dfe-8d79-f7fa754ca419.png">

### Maximum Readability
- increased contrast throughout, especially with the [annoying grey font on light grey background](https://forum.obsidian.md/t/enhance-default-color-contrast-of-the-icons/23045/3)
- decreased font size variation to increase readability & information density
- at the same time increased distinctiveness of different classes through subtle variation in typeface, font style, or backgrounds
- alternating row colors in tables, Command Palette, and Quick Switchers
- easy-to-read fonts for every use case
  - [iA Writer Quattro](https://github.com/iaolo/iA-Fonts/tree/master/iA%20Writer%20Quattro) as proportional yet clear font for regular text
  - [Input Mono](https://input.djr.com/) as monospace font for code
  - [Optima](https://en.wikipedia.org/wiki/Optima) as humanist font for heading
  - [Crimson Pro](https://fonts.google.com/specimen/Crimson+Pro) as serif font for Longform notes
- minor coloring of bold in dark mode to make it more readable, since bold in dark mode is harder to distinguish form normal text than  in light mode
- slightly thicker lines (icons, hr, tables, etc.)

### Subtle Design
Stylistically, the theme pretty much follows Obsidian's default color theme, with mostly subtle changes – like the eponymous shimmering green as secondary accent. 

## Customization
- This themes supports dozens of customization options via the [Style Settings Plugin](https://github.com/mgmeyers/obsidian-style-settings/).
- [Preview of available style settings.](https://publish.obsidian.md/hub/02+-+Community+Expansions/02.05+All+Community+Expansions/Themes/Shimmering+Focus#Customization+Options+Style+Settings+Plugin)
- You can add your own Annotation Tags via adding a snippet [using this template](https://github.com/chrisgrieser/shimmering-focus/blob/main/annotation-tag-template.css).

## Plugin Compatibility

### List of Compatible Plugins
*Shimmering Focus* is compatible with and has includes styling for all core plugins, the most common community plugins, as well as about a dozen more community plugins.

➡️ [Full list of compatible plugins.](https://publish.obsidian.md/hub/02+-+Community+Expansions/02.05+All+Community+Expansions/Themes/Shimmering+Focus#Plugin+Compatibility+1)

### Instructions for specific Plugins
In accordance with the minimalistic philosophy of the theme, unnecessary UI elements of some plugins have also been removed. However, you can still access the full plugin functionality.

- Kanban: Right-click cards to edit them.
- Sliding Panes: Enable `Swap Rotated Header Direction` in the Sliding pane Settings.
- Breadcrumbs: Refresh the index via Command Palette
- Quick Explorer: Re-enable the title bar with the Style Settings Plugin for the breadcrumbs
- Ozan's Image in Editor: Image Sizes are affected by the Image Settings & the Max View Feature.

## Installation
You can find *Shimmering Focus* in Obsidian's community themes browser under `Obsidian Settings ➞ Appearance ➞ Themes ➞ Manage`.

## Contribute
Pull requests are welcome, especially for plugins or features I haven't implemented since I do not use them myself.

- Try to follow the [design philosophy](#design-principles) of the theme.
- All sections have a `< ` as prefix for quicker navigation. This means you can search for `< font` to navigate to the font section.
- For consistency and code quality, use [stylelint](https://stylelint.io/) with the provided configuration (the `.stylelintrc.json` file). 
- Before making the pull request, please run `stylelint --fix obsidian.css`. This will auto-fix minor problems and present a list of problems, if there are any. 
- I recommend using an [editor integration for stylelint](https://stylelint.io/user-guide/integrations/editor/).

```shell
# clone
git clone git@github.com:chrisgrieser/shimmering-focus.git
cd ./shimmering-focus

# install stylelint + prerequisites
npm install -g stylelint postcss stylelint-config-recommended
```

## Credits

### About the Developer
My ([Discord](https://discord.gg/veuWUTm)) handle is `@pseudometa#9546` and you can find me on Twitter as [@pseudo_meta (Twitter)](https://twitter.com/pseudo_meta).

In my day job, I am a researcher and sociology. In my phD project, I investigate the governance of the app economy and how software ecosystems manage the tension between innovation and compatibility. If you are interested in this subject, feel free to visit [my academic homepage](https://chris-grieser.de/) and get in touch!

### Donations
**Donations** are welcome via [PayPal](https://www.paypal.com/paypalme/ChrisGrieser) or [Ko-Fi](https://ko-fi.com/pseudometa). 🙏

### Thanks
Thanks for help and/or CSS snippets:
- **@SlRvb**
- **@javalent**
- @kepano
- @Mara
- @Chetachie
- @Atlas
- @jdaniel
- @NothingIsLost

[^1]: Thanks to @Manedblackwolf.
[^2]: Thanks to @Atlas.
[^3]: Thanks to @phibr0.
