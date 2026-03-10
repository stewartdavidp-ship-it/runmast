# Mast Brand Assets

This folder is the canonical source for all Mast brand files. Every surface (Shir Glassworks app, future Mast-powered apps, marketing, etc.) should reference these files for logo usage.

## Mark Specs

**The Mast Mark:** Vertical pole with two right-facing flags (pennants).
- Upper flag: amber `#e8a84c` (the primary accent)
- Lower flag: ghost/muted (navy at ~18% opacity in light mode, cream at ~30% opacity in dark mode)
- Pole: navy `#0e1c2e` in light mode, cream `#f0ebe0` in dark mode
- No crossbeam. Flags are triangular pennants attached to the right side of the pole.

**Inline SVG (nav size, light mode):**
```html
<svg width="20" height="38" viewBox="0 0 20 38" fill="none">
  <rect x="8.5" y="0" width="3" height="38" rx="1.5" fill="#0e1c2e"/>
  <path d="M11.5 1.5 L20 6.5 L11.5 13 Z" fill="#e8a84c"/>
  <path d="M11.5 15.5 L18 19.5 L11.5 24 Z" fill="#0e1c2e" opacity="0.18"/>
</svg>
```

## Wordmark

- Font: **Archivo**, weight 800
- Letter-spacing: `-0.025em`
- Text: "Mast"
- Color: navy `#0e1c2e` (light mode) / cream `#f0ebe0` (dark mode)

## Colors

| Name   | Hex       | Usage                                     |
|--------|-----------|-------------------------------------------|
| Navy   | `#0e1c2e` | Primary text, backgrounds, pole           |
| Cream  | `#f0ebe0` | Dark-mode text, dark-mode backgrounds     |
| Amber  | `#e8a84c` | Accent, upper flag, CTAs, highlights      |
| Amber2 | `#b8742a` | Secondary amber for eyebrows, badges      |
| BG     | `#faf7f3` | Light-mode page background                |

## Tagline

> You built it, we help you run it.

## Files

| File | Description |
|------|-------------|
| `coming-soon-v2.html` | Deployed coming soon page (reference copy) |
| `logo-v5.html` | The approved final logo with light/dark modes, all size variants (96/72/48/32px), and app icon. Source of truth for the Mast mark. |
| `powered-by-v2.html` | "Powered by Mast" badge — full/medium/small sizes + in-context footer mockups, light and dark modes. |

## Powered-by Badge

See `powered-by-v2.html` for full/medium/small sizes and in-context footer mockups in both light and dark modes.

## Usage Notes

- Always use the inline SVG from `logo-v5.html` (once saved) for web usage
- The mark works at all sizes — nav (20x38), hero (240x400), favicon (32x32)
- The favicon uses a data URI version of the mark (see `index.html` `<head>`)
- For dark backgrounds, swap navy fill to cream and adjust ghost flag opacity
