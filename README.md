<p align="center">
  <img src="https://raw.githubusercontent.com/ember-theme/vscode/main/assets/logo.svg" alt="Ember" width="80" />
</p>

<h1 align="center">Ember for VS Code</h1>

<p align="center">
  A warm, nearly monochrome VS Code theme.<br/>
  Muted tones, deliberate restraint, and one coral accent that cuts through everything.
</p>

<p align="center">
  <a href="https://embertheme.com">embertheme.com</a> ·
  <a href="https://github.com/ember-theme/ember">Palette</a> ·
  <a href="#installation">Installation</a> ·
  <a href="#variants">Variants</a> ·
  <a href="#syntax-mapping">Syntax Mapping</a>
</p>

---

## Preview

<p align="center">
  <img src="https://raw.githubusercontent.com/ember-theme/vscode/main/assets/banner.png" alt="Ember variants preview" width="800" />
</p>

## Screenshots

<table>
<tr>
<td align="center"><b>Ember</b><br><sub>dark graphite</sub></td>
<td align="center"><b>Ember Soft</b><br><sub>lifted graphite</sub></td>
<td align="center"><b>Ember Light</b><br><sub>warm ivory</sub></td>
</tr>
<tr>
<td><img src="https://raw.githubusercontent.com/ember-theme/vscode/main/screenshots/ember.png" alt="Ember Dark" width="300" /></td>
<td><img src="https://raw.githubusercontent.com/ember-theme/vscode/main/screenshots/ember-soft.png" alt="Ember Soft" width="300" /></td>
<td><img src="https://raw.githubusercontent.com/ember-theme/vscode/main/screenshots/ember-light.png" alt="Ember Light" width="300" /></td>
</tr>
</table>

## Variants

| Variant | Background | Description |
|---------|-----------|-------------|
| `Ember` | ![#1c1b19](https://img.shields.io/badge/%20-1c1b19?style=flat-square&color=1c1b19) `#1c1b19` | Dark graphite, L10% — the default |
| `Ember Soft` | ![#242320](https://img.shields.io/badge/%20-242320?style=flat-square&color=242320) `#242320` | Lifted graphite, L13% — softer contrast |
| `Ember Light` | ![#e6dac4](https://img.shields.io/badge/%20-e6dac4?style=flat-square&color=e6dac4) `#e6dac4` | Warm ivory, L84% — darkened accents for WCAG AA |

## Installation

<details>
<summary><b>VS Code Marketplace</b> <i>(coming soon)</i></summary>

Search for "Ember Theme" in the Extensions panel, or:

```
ext install ember-theme.ember-theme
```

</details>

<details>
<summary><b>Manual (from source)</b></summary>

```bash
git clone https://github.com/ember-theme/vscode.git ~/.vscode/extensions/ember-theme.ember-theme-0.1.0
```

Restart VS Code, then **Ctrl+K Ctrl+T** → select **Ember**, **Ember Soft**, or **Ember Light**.

</details>

## Syntax Mapping

All colors derive from [`palette.json`](https://github.com/ember-theme/ember/blob/main/palette.json) — the single source of truth for all ports.

| Token | Color | Dark | Light |
|-------|-------|------|-------|
| Keywords | Coral | `#e08060` | `#b84c30` |
| Functions / Types | Gold | `#c8b468` | `#7a6820` |
| Strings | Olive | `#8a9868` | `#4a6830` |
| Constants / Numbers | Orange | `#c09058` | `#946030` |
| Methods | Sage | `#80a090` | `#386858` |
| Properties | Orange | `#c09058` | `#946030` |
| Comments | base6 | `#706c61` | `#787060` |
| Doc comments | base7 | `#908a7e` | `#605848` |
| Operators | base7 | `#908a7e` | `#605848` |
| Variables | fg | `#d8d0c0` | `#282418` |
| Parameters | fg-alt | `#b0a898` | `#585040` |

## Scope Coverage

| Category | Details |
|----------|---------|
| Font-lock | Keywords (bold coral), functions (gold), types (bold italic gold), strings (olive), numbers (bold orange), comments (italic dim) |
| UI chrome | Cursor (coral), line numbers, line highlight, selection, search, breadcrumbs |
| Editor | Suggest widget, hover, peek view, diff editor, merge conflicts |
| Sidebar | Activity bar, side bar, tree view, list highlights |
| Terminal | Full ANSI 0-15 color mapping |
| Git | Added (olive), modified (gold), deleted (coral), untracked, ignored |
| Diagnostics | Error (rose), warning (gold), info (steel), hint (sage) |
| Markup | Markdown headings, bold, italic, code, links, lists |
| Languages | HTML tags, CSS selectors/properties, JSON keys, YAML tags |
| Semantic | Full semantic token support for variables, functions, methods, types, properties, decorators |

## Links

- [Ember core](https://github.com/ember-theme/ember) — palette, brand, ports
- [Website](https://embertheme.com)

## License

MIT — Hossam Saraya
