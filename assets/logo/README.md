# CS3C Logo Assets

Official SVG assets for the CS3C Engineering Knowledge System.

## Files

| File | Purpose |
| --- | --- |
| `cs3c-mark.svg` | Standalone five-layer CS3C Mark |
| `cs3c-logo.svg` | CS3C Mark with the dark wordmark for light backgrounds |
| `cs3c-logo-light.svg` | CS3C Mark with the white wordmark for dark backgrounds |
| `favicon.svg` | Square favicon treatment of the standalone mark |
| `BRAND.md` | Canonical usage and construction rules |

## Usage

Use SVG files without changing their internal geometry or colors. Scale them
proportionally by setting either width or height and allowing the other
dimension to remain automatic.

```html
<img src="/assets/logo/cs3c-logo.svg" alt="CS3C" width="120" height="32" />
```

Use an empty `alt` value when the same accessible name is already present
next to the asset. Do not rely on the embedded SVG title instead of appropriate
HTML alternative text.

## Minimum sizes

- CS3C Mark: 24 px high
- CS3C Logo — Recommended minimum: 120 px wide

The favicon is browser-controlled and must retain all five layers at every
rendered size.

## Typography

The combined logo uses Inter Semibold with the existing CS3C wordmark tracking.
Arial is included as a system fallback. For consistent rendering, load Inter
before displaying either combined logo.

## Color variants

- Use `cs3c-logo.svg` on white and other light backgrounds.
- Use `cs3c-logo-light.svg` on dark backgrounds.
- The five green layers are identical in every asset.

Do not recolor, rotate, stretch, compress, outline, animate, or add effects to
the assets.
