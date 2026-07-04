# H2 OS

![H2 OS preview](screenshot.png)

> **A geometric aesthetics theme for Obsidian.** White surfaces, desaturated OnePlus red accents, and a circle / triangle / square geometry grammar inspired by the H2OS visual language — a calm, distinctive take on the knowledge base.

[中文介绍](https://github.com/elijahchan2019/obsidian-h2os-theme/blob/main/README.zh-CN.md) · Light only · Desktop &amp; Mobile · No plugin required

> **Status:** Early development. This README is a placeholder and will be expanded in Phase 5.

## Why H2 OS

- **Geometric grammar** — circle / triangle / square each carry a semantic role, not just decoration.
- **Desaturated red, restrained** — the OnePlus red serves only as punctuation (selection, hover, active, callouts), never as a large fill.
- **Hydrogen window** — an empty-state geometric composition as a quiet signature moment.
- **Modernized execution** — H2OS's discipline preserved, its 2015-era execution redone at 2026 precision.

## Installation

Not yet on the community theme browser. For now, manual install by placing `theme.css` and `manifest.json` in:

```text
<vault>/.obsidian/themes/H2 OS/
```

## Recommended fonts

H2 OS does not bundle fonts. For the intended geometric letterforms, install Poppins and Montserrat:

```bash
brew install --cask font-poppins font-montserrat
```

The theme falls back gracefully to system geometric sans (Avenir Next on macOS, Segoe UI Variable on Windows) when these are absent.

## Compatibility

- Obsidian 1.5.0+
- Light mode only (by design)
- Desktop and mobile
- No plugin required

> **Note:** Obsidian's Electron/Chromium follows the installer, not auto-updates. If parts of the theme appear to be missing, redownload the Obsidian installer to upgrade Chromium (the theme relies on CSS nesting, available since Chromium 112 / Safari 16.5).

## License

[MIT](LICENSE)
