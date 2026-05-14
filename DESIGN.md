# Supply Pro — Design System

## Color palette

| Token | Value | Use |
|---|---|---|
| `--green` | `#006300` | Primary CTA, section tags, checkmarks |
| `--green-deep` | `#004a00` | Hover states, video section gradient |
| `--green-light` | `#30A04E` | Trust indicators, pulse dot |
| `--green-tint` | `#E8F2EA` | Step numbers bg, badge bg |
| `--acajou` | `#502007` | CTA banner (warm, urgent) |
| `--acajou-deep` | `#3a1705` | CTA banner gradient start |
| `--text` | `#0F1410` | Primary text |
| `--text-2` | `#4A5249` | Secondary text, body copy |
| `--text-3` | `#8A8F88` | Tertiary, placeholders |
| `--bg` | `#FFFFFF` | Page background |
| `--surface` | `#FAFAF8` | Alternating sections |
| `--line` | `#E8EAE6` | Card borders |
| `--line-2` | `#DEE2DC` | Stronger dividers |
| `--footer-bg` | `#0A0C0A` | Footer background |

## Typography

| Role | Font | Weight | Size |
|---|---|---|---|
| Display / Headings | Space Grotesk | 600 | clamp(44px, 6vw, 76px) for H1, clamp(34px, 4.5vw, 56px) for H2 |
| Body | Archivo | 400 | 17–19px for large body, 15px for supporting |
| Labels / Tags | Archivo | 600 | 12px, uppercase, letter-spacing 0.12em |
| Stats | Space Grotesk | 500 | 56px |

Letter spacing: `-0.035em` H1, `-0.03em` H2, `-0.025em` general headings.

## Spacing
- Section padding: `112px 0` (desktop), `72px 0` (mobile)
- Hero padding: `88px 0 100px`
- Container max-width: 1200px, padding 24px

## Elevation
- `--shadow-sm`: `0 1px 2px rgba(15,20,16,0.04), 0 1px 3px rgba(15,20,16,0.06)`
- `--shadow-md`: `0 8px 24px -10px rgba(15,20,16,0.12)`
- `--shadow-lg`: `0 30px 60px -25px rgba(0,99,0,0.25)`

## Border radius
- `--radius-sm`: 8px (buttons, step numbers)
- `--radius`: 12px (cards)
- `--radius-lg`: 20px (video wrap, large panels)

## Motion
- Easing: `cubic-bezier(0.22, 1, 0.36, 1)` — fast in, soft out
- Scroll reveal: 0.7s opacity + translateY(16px)
- Hover: 0.2–0.3s
- Stat counter: 1400ms cubic ease-out

## Component patterns
- **Cards**: white bg, 1px `--line` border, hover lifts 2–3px with stronger border
- **Buttons**: primary=green fill, secondary=white+border, ghost=transparent, white=white fill on dark bg
- **Tags**: `::before` horizontal rule + uppercase tracking text in green
- **Phone frames**: dark bg with dynamic island cutout, green gradient glow — placeholder until real screenshots
- **Section alternation**: white → `--surface` → white pattern

## Aesthetic philosophy
Serious craft tool, not consumer app. Clean Swiss-influenced grid. Greenish-black palette signals precision and sustainability. Acajou (dark mahogany red) used only for the final CTA — it reads as urgency without aggression.

No decorative illustrations. No rounded blob shapes. No rainbow gradients.
Allowed: radial gradient glows (subtle), italic accent text in headings, monospaced numbers.
