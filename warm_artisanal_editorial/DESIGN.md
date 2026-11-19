---
name: Warm Artisanal Editorial
colors:
  surface: '#fff8f8'
  surface-dim: '#e1d8d9'
  surface-bright: '#fff8f8'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#fbf1f2'
  surface-container: '#f5eced'
  surface-container-high: '#efe6e7'
  surface-container-highest: '#e9e0e1'
  on-surface: '#1e1b1c'
  on-surface-variant: '#4d444b'
  inverse-surface: '#342f30'
  inverse-on-surface: '#f8eeef'
  outline: '#7e747c'
  outline-variant: '#cfc3cc'
  surface-tint: '#F5EFE6'
  primary: '#331736'
  on-primary: '#ffffff'
  primary-container: '#4a2c4d'
  on-primary-container: '#ba94bb'
  inverse-primary: '#e3b9e3'
  secondary: '#7d5700'
  on-secondary: '#ffffff'
  secondary-container: '#ffc55f'
  on-secondary-container: '#755100'
  tertiary: '#1b2500'
  on-tertiary: '#ffffff'
  tertiary-container: '#303b0f'
  on-tertiary-container: '#98a66f'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffd6fe'
  primary-fixed-dim: '#e3b9e3'
  on-primary-fixed: '#2c1030'
  on-primary-fixed-variant: '#5b3c5e'
  secondary-fixed: '#ffdeaa'
  secondary-fixed-dim: '#f5bd58'
  on-secondary-fixed: '#271900'
  on-secondary-fixed-variant: '#5f4100'
  tertiary-fixed: '#dbe9ac'
  tertiary-fixed-dim: '#bfcd92'
  on-tertiary-fixed: '#161f00'
  on-tertiary-fixed-variant: '#404b1e'
  background: '#fff8f8'
  on-background: '#1e1b1c'
  surface-variant: '#e9e0e1'
  bg-canvas: '#FAF6F0'
  surface-card: '#FFFFFF'
  accent-amber-subtle: '#F7EBD3'
  border-subtle: '#E5DCce'
  text-muted: '#6E6663'
typography:
  headline-xl:
    fontFamily: Playfair Display
    fontSize: 40px
    fontWeight: '700'
    lineHeight: 48px
    letterSpacing: -0.02em
  headline-xl-mobile:
    fontFamily: Playfair Display
    fontSize: 30px
    fontWeight: '700'
    lineHeight: 38px
    letterSpacing: -0.015em
  headline-lg:
    fontFamily: Playfair Display
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
    letterSpacing: -0.01em
  headline-lg-mobile:
    fontFamily: Playfair Display
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
    letterSpacing: 0em
  headline-md:
    fontFamily: Playfair Display
    fontSize: 22px
    fontWeight: '600'
    lineHeight: 28px
  headline-sm:
    fontFamily: Playfair Display
    fontSize: 18px
    fontWeight: '600'
    lineHeight: 24px
  body-lg:
    fontFamily: DM Sans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: DM Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  body-sm:
    fontFamily: DM Sans
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  label-md:
    fontFamily: DM Sans
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 18px
    letterSpacing: 0.02em
  label-sm:
    fontFamily: DM Sans
    fontSize: 12px
    fontWeight: '700'
    lineHeight: 16px
    letterSpacing: 0.06em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  gutter: 1rem
  gutter-desktop: 1.5rem
  margin: 1rem
  margin-desktop: 2.5rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
  space-2xl: 4rem
---

## Brand & Style

The design system establishes a warm, intimate, and artisanal neighbourhood presence. It caters directly to two core users: a mobile passerby making a split-second decision to walk in, and an office administrator on a desktop evaluating catering options. The aesthetic pairs the tactile warmth of an independent roasting house and daily bakery with the clarity and discipline of modern editorial layouts.

The design movement is **Editorial Minimalist with Warm Tactile Accents**. It avoids excessive embellishments, digital gimmicks, or aggressive tech-oriented interactions. Instead, it relies on generous, airy whitespace, grounded serif typography, deliberate color discipline, and restrained structural boundaries. The UI prioritises clear legibility, quiet confidence, and tactile authenticity over digital sheen.

## Colors

The palette is strictly anchored in natural, roasted tones: deep fig purple provides weight and authority, warm amber creates golden-hour focal points, and an unbleached linen canvas serves as the neutral backdrop.

### Application Rules
- **Canvas & Surfaces:** The default page canvas is `#FAF6F0`. Elevated groupings, data callouts, and grouped pricing containers leverage `#F5EFE6` or clean `#FFFFFF`.
- **Primary CTA Rule:** Deep Fig Purple (`#4A2C4D`) is reserved for the single primary call-to-action per page. It carries high visual weight and contrasts against the background with off-white text (`#FAF6F0`).
- **Warm Amber (`#D9A441`):** Strictly restricted to badges, dietary tags, small focal highlights, and selected accent markers. It must **never** be used for body copy or low-contrast backgrounds containing light text.
- **Text & Contrast:** Near-black (`#221E1F`) serves as primary copy to maintain WCAG AAA compliance against `#FAF6F0`. Secondary explanatory text uses `#6E6663`.

## Typography

The type scale combines the literary, timeless craftsmanship of **Playfair Display** for headings with the clean, legible geometry of **DM Sans** for all operational copy, menus, and directional guidance.

### Hierarchy & Styling Rules
- **Display & Headings:** Use `Playfair Display` for page titles, menu section breaks, and the hero wordmark. Preserve natural letterforms without artificial expansion, using slight negative tracking (`-0.01em` to `-0.02em`) on large scale titles.
- **Body & Data:** Use `DM Sans` for continuous reading, ingredients, pricing, addresses, and hours. Line height is kept spacious (`1.5` minimum) to allow effortless scanning on small hand-held devices.
- **Dietary & Context Labels:** Small uppercase tokens (e.g. `V`, `VG`, `GF`) use `label-sm` with slight positive tracking (`0.06em`) for immediate recognition.

## Layout & Spacing

The layout philosophy prioritises a **mobile-first single column** optimized for 390px viewports, scaling up to a tightly constrained, centered layout on desktop viewports (maximum container width 768px for single-column editorial, 1024px for multi-card catering spreads).

### Grid and Viewport Rules
- **Mobile (< 768px):** Single-column vertical flow with `margin: 1rem` (16px) and `gutter: 1rem`. High-priority conversion content (address, opening hours, primary action) must sit within the initial viewport fold without mandatory scrolling.
- **Desktop (>= 768px):** 
  - Standard pages (Home, About, Visit): Center-constrained column (max 720px) to maintain readable line lengths.
  - Menu: Transitions to a balanced two-column staggered layout (maximum 880px container).
  - Catering: Three pricing packages sit side by side in a 3-column equal grid with `gutter-desktop: 1.5rem`.
- **Rhythm:** Spacing follows a 4px base increment. Inter-section gaps leverage `space-2xl` (64px) on desktop and `space-xl` (40px) on mobile to cleanly delineate content blocks without visual clutter.

## Elevation & Depth

Visual hierarchy is maintained through **tonal surface separation and low-contrast borders** rather than drop shadows or saturated blurs. 

- **Surface Layering:** The primary page canvas rests at `#FAF6F0`. Grouped content blocks, catering package cards, and operational tables use pure `#FFFFFF` or tinted `#F5EFE6`.
- **Outlines & Dividers:** Subtle, tactile boundaries use `#E5DCCE` at 1px thickness. High-contrast harsh borders are prohibited.
- **Shadow Treatment:** Pure elevation shadows are avoided. A minimal ambient diffusion may be applied solely to floating mobile navigation bars or hero imagery using: `box-shadow: 0 4px 20px -4px rgba(74, 44, 77, 0.08)`. The purple tint anchors the shadow into the primary brand tone.

## Shapes

The design system employs a **Soft (`roundedness: 1`)** geometric language. This provides an approachable, hand-crafted feel that stays structured, rejecting overly bubbly pill shapes or sharp, brutalist corners.

- **Standard Elements (Buttons, Inputs, Cards):** `0.25rem` (4px) border radius.
- **Feature Surfaces (Catering Packages, Photo Containers):** `0.5rem` (8px) border radius (`rounded-lg`).
- **Dietary Badges & Tags:** Fully circular or small capsule radii with minimal internal padding to maintain crisp alignment next to menu pricing.

## Components

### Buttons & Interactive CTAs
- **Primary Action Button:** Only one primary CTA is allowed per page (e.g. "Find us" on Home, "Order catering" on Catering). Built with Deep Fig Purple (`#4A2C4D`), text in `#FAF6F0`, font weight 600 (`label-md`), padded at `0.75rem 1.5rem`, with a 4px corner radius. Hover/active states transition smoothly to `#361F38`.
- **Secondary & Text Links:** Plain, understated typographic links using Near-black (`#221E1F`) with a thin bottom underline in `#D9A441` (1px offset by 2px) to denote interactivity without competing with the primary CTA.

### Dietary Chips & Badges
- Small inline status tags (`V`, `VG`, `GF`) rendered in `label-sm`.
- Contained within a subtle `#F7EBD3` background with Warm Amber (`#D9A441`) border and text color deepened to `#8A6014` for accessible legibility.

### Menu List Items
- Structured as clean horizontal rows: Item name and dietary chips on the left, dotted leader line or whitespace separation, with price aligned right in `label-md` bold.
- Short descriptions (1–2 lines) sit beneath the title in `body-sm` (`#6E6663`).

### Operational Cards (Hours & Catering)
- **Hours Table:** A clean tabular layout with alternating border dividers (`#E5DCCE`). Today's hours are highlighted with a soft left-border accent in `#D9A441`.
- **Catering Tier Cards:** Built on `#FFFFFF` surfaces with a 1px `#E5DCCE` perimeter. Package name in `headline-md`, price per person in `headline-lg` (`#4A2C4D`), followed by an unbulleted, spaced ingredient checklist.

### Header & Mobile Navigation
- Narrow 56px to 64px tall header anchored at the top of the viewport.
- Contains the "Fig & Filter" serif wordmark and a simple, uncluttered horizontal nav row or compact slide drawer with equal spacing between Home, Menu, Catering, About, and Visit.

### Global Footer
- Background in `#F5EFE6` bordered on top with 1px `#E5DCCE`.
- Clear vertical stack on mobile: café identity, opening hours summary, physical address (8 Chalk Lane), direct email link, and a dedicated, plain-text styled "Order catering" link.