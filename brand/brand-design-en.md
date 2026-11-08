# flatphormesmedia.de — Brand Design Guide

> **Version:** 1.0 · **Date:** 2026-11-06 · **Status:** Brand foundation / Living document
>
> **Guiding idea:** *Less bla. More code. ❤️ Dresden.*

## 1. Purpose and scope

This document is the central visual reference for **flatphormesmedia.de**. It applies to websites, applications, GitHub profiles and READMEs, presentations, documentation, social media, icons, merchandise, and any other digital or printed brand materials.

**Priorities:** recognition, readability, technical clarity, and an approachable, distinctive personality. These rules establish the default, not a restriction on every creative idea. Deliberate deviations should be documented.

## 2. Brand identity

- **Name and spelling:** `flatphormesmedia.de` (always lowercase, including `.de`).
- **Origin:** Dresden, Germany.
- **Positioning:** Software and digital ideas crafted with passion, curiosity, and attention to detail.
- **Personality:** modern, minimal, clever, approachable, slightly cheeky; never sterile or cluttered.
- **Values:** simplicity, quality, creativity, pragmatism, passion.
- **Voice:** direct, concise, human; use technical terminology only when helpful. Humor should be subtle and natural.

### Copy and taglines

**Recommended short tagline:** `Less bla. More code. ❤️ Dresden.`

**Other options:**
- `Code with heart. Made in Dresden.`
- `Made in Dresden. Built with ❤️ & ☕. Powered by code.`
- `Keep it simple. Make it awesome.`

These are suggested taglines, not mandatory copy. Claims about specific services, clients, or references must be verified before publication.

## 3. Logo and brand mark

### Elements

1. **Symbol:** A substantial, evenly proportioned isometric 3D plus sign, tilted backward, with crisp dark outer edges, semi-transparent gray faces, and visible internal edges. No glow effects.
2. **Wordmark:** `flatphormesmedia.de` in fluid, handwritten-style lettering.
3. **Signature dot:** The dot before `de` is highlighted in **Signature Red**.
4. **Secondary motif:** An organic, yin-yang-inspired division between light and dark surfaces, derived from the existing profile image and banner.

### Variants

| Variant | Use |
|---|---|
| Horizontal logo (plus on left, wordmark on right) | Website headers, README banners, signatures |
| Stacked logo (plus above wordmark) | Profile images, square social media graphics |
| Symbol only | Favicons, small application icons, compact avatars |
| Light/dark composition | Hero banners, covers, branded backgrounds |

**Rules:** Preserve the plus sign's proportions and equal-width arms; do not alter or stretch the wordmark; favor the signature dot as the sole strong color accent. Maintain sufficient clear space around the logo. Avoid glow, neon, chrome-like 3D treatments, and excessive shadows.

**Important:** Images developed during the conversation are visual references, not verified vector master files. Before production, create approved SVG/PNG masters and verify actual alpha transparency. A checkerboard pattern in a preview does not prove that the image has a transparent background.

## 4. Color palette

### Core colors

| Token | Name | Hex | Role |
|---|---|---|---|
| `--brand-ink` | Obsidian | `#111318` | Primary dark background; text on light surfaces |
| `--brand-charcoal` | Charcoal | `#252A31` | Dark cards and secondary surfaces |
| `--brand-white` | Pure White | `#FFFFFF` | Light cards; text on dark surfaces |
| `--brand-soft-white` | Soft White | `#F5F6F7` | Light page background |
| `--brand-glass` | Glass Gray | `#C9CDD2` | Plus symbol and subtle neutral accents |
| `--brand-red` | Signature Red | `#FF2855` | Logo dot and selective highlights |
| `--brand-red-accessible` | Deep Signature Red | `#C9003D` | Small text and buttons on light surfaces |
| `--brand-muted` | Muted Gray | `#626873` | Secondary text on light surfaces |

**Suggested color distribution:** approximately 80% neutral base, 15% gray/glass, and 5% accent red. This is a visual guideline, not a strict mathematical requirement.

**Additional colors:** Functional success, warning, and error colors may be used for status communication, but are not part of the primary brand identity. Violet is **not** an official secondary brand color.

### Contrast and accessibility

- Aim for WCAG AA contrast: at least 4.5:1 for regular text and 3:1 for large text and relevant UI graphics.
- `#FF2855` works well for accent dots, lines, and larger decorative elements, but should not automatically be used behind small white button text.
- Prefer `#C9003D` for white text on red buttons or red text on white surfaces; test the final combination in context.
- Semi-transparent glass-gray effects must never compromise readability.

## 5. Dark and light mode

| UI element | Dark mode | Light mode |
|---|---|---|
| Page background | `#111318` | `#F5F6F7` |
| Card / surface | `#252A31` | `#FFFFFF` |
| Primary text | `#FFFFFF` | `#111318` |
| Secondary text | `#C9CDD2` | `#626873` |
| Decorative accent / signature dot | `#FF2855` | `#FF2855` |
| Text link / primary button | Contrast-verified variant | `#C9003D` |

- Treat both modes as equally important expressions of the same brand.
- Default to the system preference; offer a manual switch when appropriate for the product.
- Do not simply invert logo colors without checking outlines and legibility.
- Yin-yang-inspired surfaces may bridge light and dark areas, but must not obscure content.

## 6. Typography

**Principle:** Use a clean, modern sans-serif for interfaces and body copy. Reserve handwritten lettering primarily for the wordmark and occasional short highlights.

- **UI / body text:** Prefer `Inter`; alternatives include `Manrope`, `system-ui`, `Arial`, and `sans-serif`.
- **Logo:** Use the approved handwritten wordmark master; do not recreate it using an arbitrary script font.
- **Hierarchy:** Strong headlines, short paragraphs, and clear distinctions between headings, body copy, and metadata.
- **Weights:** Primarily Regular, Medium, and Semibold; avoid excessive Extra Bold.
- **Capitalization:** Favor clear sentence case; concise English taglines are welcome.

## 7. Layout and UI language

- Use generous whitespace and a calm, consistent grid.
- Group a small number of meaningful elements instead of adding decorative clutter.
- Use subtly rounded cards; apply shadows sparingly and only where depth adds value.
- Make buttons and links distinguishable; provide visible keyboard focus states.
- Keep animations brief, subtle, and functional; honor `prefers-reduced-motion`.
- Prefer simple line or geometric icons with consistent stroke widths.
- Avoid arbitrary gradients, loud color blocks, and generic stock-tech imagery.

### Example design tokens (CSS)

```css
:root {
  --brand-ink: #111318;
  --brand-charcoal: #252a31;
  --brand-white: #ffffff;
  --brand-soft-white: #f5f6f7;
  --brand-glass: #c9cdd2;
  --brand-red: #ff2855;
  --brand-red-accessible: #c9003d;
  --brand-muted: #626873;

  --page-bg: var(--brand-soft-white);
  --surface-bg: var(--brand-white);
  --text-primary: var(--brand-ink);
  --text-secondary: var(--brand-muted);
  --action-bg: var(--brand-red-accessible);
  --action-text: var(--brand-white);
  --radius-card: 14px;
  --radius-control: 9px;
  --font-body: Inter, system-ui, Arial, sans-serif;
}

[data-theme="dark"] {
  --page-bg: var(--brand-ink);
  --surface-bg: var(--brand-charcoal);
  --text-primary: var(--brand-white);
  --text-secondary: var(--brand-glass);
  --action-bg: var(--brand-red-accessible);
  --action-text: var(--brand-white);
}
```

## 8. Imagery and graphics

- Favor graphic compositions, real projects, and authentic visual details.
- **3D plus:** clean geometry, symmetric arms, subtle gray transparency, crisp black edges.
- **Black-and-white wave:** organic, refined, and understated; avoid literal clip-art yin-yang symbols.
- **Signature Red:** use as a small focal point, such as a dot, cursor, line, or selected UI detail.
- **Image treatment:** crisp edges; avoid exaggerated glow, HDR, or neon effects.

## 9. Applications

### Websites and web apps

- Use the horizontal logo lockup in headers.
- Implement dark and light modes using semantic tokens.
- Keep calls to action selective but visible; verify contrast and keyboard access.
- Express the brand through typography, whitespace, the plus symbol, and small red details.

### GitHub organization and repositories

- **Avatar:** use a square or circle-safe composition with a clearly recognizable plus; include the wordmark only when readable at small sizes.
- **Organization README:** banner, short tagline, two or three sentences, and a link.
- **Recommended tagline:** **Less bla. More code. ❤️ Dresden.**
- **Example paths:** `.github/profile/README.md` and `.github/profile/assets/banner.png`.

### Social media and presentations

- Consistently reuse the plus, wordmark, Signature Red, and black-and-white wave.
- Keep copy short and legible on small screens.
- Create platform-specific crops rather than distorting master artwork.

### Print and merchandise

- Provide a simplified single-color version of the plus.
- Test stroke widths and transparency effects for the actual printing method.
- Do not reproduce the symbol or wordmark at unreadably small sizes.

## 10. Voice and writing guidelines

**Do:** Be concise, distinctive, friendly, technically competent, and human.

**Don't:** Use empty superlatives, marketing clichés, forced coolness, or unsubstantiated promises.

Example:

> We build software with passion, curiosity, and a little bit of magic.  
> Made with ❤️ & ☕ in Dresden.

Short English taglines can accompany German descriptions. For longer content, maintain the language appropriate to the intended audience.

## 11. Rules for designers and coding agents

For every new deliverable related to **flatphormesmedia.de**:

1. Use this document as the design source of truth.
2. Reuse approved logo masters and design tokens rather than recreating them from scratch.
3. Build primarily with neutral colors; apply Signature Red intentionally and sparingly.
4. Consider both dark and light modes whenever the medium supports them.
5. Verify readability, contrast, responsiveness, and accessibility.
6. Do not use the handwritten wordmark style as the default UI font.
7. Explain intentional visual deviations and update this guide where appropriate.
8. Do not invent claims about services, customers, or products.

### Reusable prompt for new work

> Create [artifact] for **flatphormesmedia.de**. Follow `brand-design.md`: a minimal, premium black/white/charcoal aesthetic; a geometric, semi-transparent gray 3D plus with dark outlines; the handwritten wordmark; Signature Red `#FF2855` as a restrained accent; and, when suitable, an organic light/dark wave. Account for contrast, readability, the intended medium, and dark/light mode. Reuse existing master assets instead of inventing replacements.

## 12. Assets, maintenance, and open decisions

**Suggested structure:**

```text
brand/
├── brand-design.md
├── assets/
│   ├── logo-horizontal-light.png
│   ├── logo-horizontal-dark.png
│   ├── logo-stacked.png
│   ├── symbol-only.png
│   ├── github-avatar.png
│   └── banner-yinyang.png
└── README.md
```

These filenames are suggestions, not claims that the files already exist.

**Still to be finalized:** approved vector masters; the exact wordmark font or vector paths; minimum logo size; mandatory clear space; approved avatar version; print-ready color values; and legal brand-use requirements.

**Change policy:** Treat colors, logo proportions, and other identity-defining decisions as version-controlled changes. Add new applications without diluting the core identity.
