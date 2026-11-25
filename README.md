# Pizdec Dark

A cool-graphite dark theme for Obsidian. Depth comes from surface tone and shadow, not from grey
outlines.

## Palette

| Colour | Role |
|---|---|
| `#161a1f` | main background (editor, sidebars, board) |
| `#212427` | foreground 1: panels, modals |
| `#414a4c` | foreground 2: raised cards and fields, dividers |
| `#1e88e5` | main accent: links, buttons, tags, focus rings, selection, bullets, quote bars |
| `#3bb8e2` | sky, halfway between the two accents: inline code and code text, checkboxes, scrollbars |
| `#59e7df` | secondary accent, small pops only: caret, `==highlights==`, checkbox hover |

All headings are white. Grey outline borders are removed everywhere. Blue focus rings stay, and
`---` dividers in notes stay visible.

## Customising colours

Install the [Style Settings](https://github.com/mgmeyers/obsidian-style-settings) community plugin, then open
**Settings → Style Settings → Pizdec Dark**. Every colour has a picker, grouped into Surfaces, Text, Accents
and Code highlighting, with a reset arrow to go back to the default. Colours ripple: change the editor
background and the sidebars follow (unless you set Sidebars separately), and hover tints, highlights and
scrollbars are mixed from their base colours.

**Palettes.** The **Palette** dropdown at the top switches every colour at once: *Pizdec* (default), *Navy*
(navy base, magenta pops, yellow keywords), *Cyberpunk* (violet-black, neon cyan and hot pink, glowing
headings; pairs well with Accent color `#ff2a6d`), or **My palette 1 / 2**, your own. Each of those has its own section
at the bottom of the page (collapsed); it starts as a copy of the Pizdec colours, so change only the ones you want.
The pickers at the top still apply on top of whichever palette is active; reset them to see the palette as it is.
To back a palette up or move it to another device, use Style Settings' **Export** on the Pizdec Dark section and
**Import** it there.

The main accent (links, tags, buttons, selection) is Obsidian's own **Settings → Appearance → Accent color**;
the theme's default is `#1e88e5`.

## NoteBoard

If the [NoteBoard](https://github.com/sennafaris28/noteboard) plugin (1.1.0+) is installed, the
theme also styles the board: `#161a1f` base, `#212427` columns and panels, `#414a4c` cards and
fields, and cyan "today" markers. Quest colours stay your own picks. Without the plugin those
variables do nothing.

## Install

**By hand:** copy `theme.css` and `manifest.json` into `<vault>/.obsidian/themes/Pizdec Dark/`, then
pick **Pizdec Dark** in Settings → Appearance → Themes.

The theme is built for dark mode.

## License

MIT
