# Inherited styles indicator

A design prototype for the WordPress block editor. In the block inspector, a ◇ next to a control's label shows where the block's style comes from:

- **Style from Styles element**: the site's Styles.
- **Style from Paragraph block** (or any block): that block type's styles in Styles → Blocks.
- **Style from parent block**: a parent block sets it, directly or through its block style (e.g. a section style).

Controls show the inherited value. When you set the style on the block itself, the ◇ disappears.

## Try it in your browser

**[Open the demo](https://fcoveram.github.io/inherited-styles-indicator/)** — a WordCamp Galicia 2026 sample site in WordPress Playground, with the plugin installed. Nothing to install; the first load takes about 30 seconds.

## Install on your own site

Download [`inherited-styles-indicator.zip`](inherited-styles-indicator.zip), then in WordPress go to Plugins → Add New Plugin → Upload Plugin. Needs WordPress 7.1 or later and a block theme (tested with Twenty Twenty-Five).

Prototype only: it works with the editor in English and relies on experimental editor internals that may change in future WordPress versions.

## What's here

- `inherited-styles-indicator/`: the plugin source.
- `blueprint.json`: the Playground setup (Twenty Twenty-Five, the plugin, the sample page with its template, image and Styles).
- `index.html`: the landing page at fcoveram.github.io/inherited-styles-indicator.
