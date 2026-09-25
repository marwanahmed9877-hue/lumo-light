---
name: Lumo Artisanal Lighting & Textiles
colors:
  surface: '#fcf9f3'
  surface-dim: '#dcdad4'
  surface-bright: '#fcf9f3'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f6f3ed'
  surface-container: '#f0eee8'
  surface-container-high: '#ebe8e2'
  surface-container-highest: '#e5e2dc'
  on-surface: '#1c1c18'
  on-surface-variant: '#51443b'
  inverse-surface: '#31312d'
  inverse-on-surface: '#f3f0ea'
  outline: '#83746a'
  outline-variant: '#d5c3b7'
  surface-tint: '#82542d'
  primary: '#7f522b'
  on-primary: '#ffffff'
  primary-container: '#9b6a41'
  on-primary-container: '#fffbff'
  inverse-primary: '#f6ba8b'
  secondary: '#58624b'
  on-secondary: '#ffffff'
  secondary-container: '#d9e4c7'
  on-secondary-container: '#5c664f'
  tertiary: '#815215'
  on-tertiary: '#ffffff'
  tertiary-container: '#9d6a2c'
  on-tertiary-container: '#fffbff'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffdcc3'
  primary-fixed-dim: '#f6ba8b'
  on-primary-fixed: '#2f1500'
  on-primary-fixed-variant: '#663d18'
  secondary-fixed: '#dce6c9'
  secondary-fixed-dim: '#c0caae'
  on-secondary-fixed: '#161e0c'
  on-secondary-fixed-variant: '#404a34'
  tertiary-fixed: '#ffdcbb'
  tertiary-fixed-dim: '#faba75'
  on-tertiary-fixed: '#2b1700'
  on-tertiary-fixed-variant: '#673d00'
  background: '#fcf9f3'
  on-background: '#1c1c18'
  surface-variant: '#e5e2dc'
typography:
  display-lg:
    fontFamily: Playfair Display
    fontSize: 56px
    fontWeight: '500'
    lineHeight: 68px
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Playfair Display
    fontSize: 38px
    fontWeight: '500'
    lineHeight: 48px
    letterSpacing: -0.01em
  headline-lg:
    fontFamily: Playfair Display
    fontSize: 36px
    fontWeight: '600'
    lineHeight: 46px
    letterSpacing: -0.01em
  headline-lg-mobile:
    fontFamily: Playfair Display
    fontSize: 28px
    fontWeight: '600'
    lineHeight: 36px
  headline-md:
    fontFamily: Playfair Display
    fontSize: 24px
    fontWeight: '500'
    lineHeight: 32px
  title-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
  title-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 16px
    fontWeight: '600'
    lineHeight: 24px
    letterSpacing: 0.01em
  body-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 15px
    fontWeight: '400'
    lineHeight: 24px
  body-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 13px
    fontWeight: '400'
    lineHeight: 20px
  label-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.08em
  label-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 11px
    fontWeight: '500'
    lineHeight: 14px
    letterSpacing: 0.06em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  gutter: 1.5rem
  gutter-mobile: 1rem
  margin: 3rem
  margin-mobile: 1.25rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.75rem
  space-xl: 3rem
---

## Brand & Style

This design system establishes a warm, artisanal luxury presence tailored for curated interior spaces, handmade lighting, and organic bedding textiles. The brand personality embodies serene hospitality, tactile materiality, and heritage Arabic craftsmanship modernized with quiet editorial restraint. 

The aesthetic blends **Minimalism** with **Tactile Warmth** and **Editorial Luxury**:
- Tactile references drawn from natural woven flax, raw timber, hand-turned ceramic bases, and warm glowing filaments.
- Natural, unhurried negative space that mirrors serene architectural sanctuaries.
- Bilingual typographical harmony balancing Latin serif display elegance with fluid Arabic letterforms.
- A calm, elevated tone that builds intimate trust with interior designers, collectors, and design-conscious homeowners.

## Colors

The palette is derived from natural, unbleached organic textures, desert sand dunes, warm amber lamp glow, and dried olive botanicals:

- **Primary (`#B88358` / Soft Terracotta Earth):** Anchor for interactive focal points, narrative buttons, and key artisan callouts. Evokes fired clay and hand-dyed yarns.
- **Secondary (`#6B755D` / Muted Olive Canopy):** Accents, badges, product sustainability tags, and botanical lifestyle details.
- **Tertiary (`#DDA15E` / Amber Ambient Glow):** Highlights, luminous lighting toggles, interactive ratings, and illumination states.
- **Neutral (`#F9F6F0` / Linen Alabaster):** Foundations and canvas surfaces, replacing sterile pure white with rich, tactile unbleached paper and fabric tones. Deep charcoal-umber (`#2D2621`) provides contrast for reading and hierarchy without the harshness of pure black.

## Typography

The typographical direction embraces deliberate bilingual harmony:
- **Latin Display:** **Playfair Display** introduces editorial poise, capturing the nuanced delicacy of artisanal boutique catalogs.
- **Arabic Display & Body Pairing:** When rendering Arabic scripts, utilize classical fonts such as **Amiri** or **Cairo** mapped directly to the corresponding sizes, ensuring harmonious x-height and natural fluid baselines alongside **Plus Jakarta Sans**.
- **Body & UI Elements:** **Plus Jakarta Sans** provides a clean, open, approachable geometric foundation that keeps e-commerce specifications, cart details, and navigation clear across all viewports.
- Uppercase tracking is applied sparingly on `label-*` tokens to reflect haute-couture and fine-art labeling.

## Layout & Spacing

The layout is built upon an adaptable 12-column responsive fluid grid designed to elevate visual rhythm and tactile media:

- **Desktop (≥ 1024px):** 12 columns with `margin` of `3rem` and `gutter` of `1.5rem`. Editorial product stories can alternate asymmetrical columns (e.g., 7 columns for imagery, 5 columns for crafting lore and specifications).
- **Tablet (768px – 1023px):** 8 columns with `margin` of `2rem` and `gutter` of `1.25rem`.
- **Mobile (≤ 767px):** 4 columns with `margin-mobile` of `1.25rem` and `gutter-mobile` of `1rem`. Product lookbooks reflow from multi-item carousels to rich single-column vertical cards.
- **Bidirectional Support:** Symmetrical grid gutters support standard LTR and Arabic RTL reading directions natively without structural reflow anomalies.

## Elevation & Depth

Visual hierarchy does not rely on synthetic drop-shadows or stark dark elevations; instead, it utilizes **tonal layers**, **subtle luminous glows**, and **tactile ambient diffusion**:

- **Level 0 (Base Canvas):** Unbleached raw linen tint (`#F9F6F0`).
- **Level 1 (Card & Surface Tiers):** Warm alabaster container (`#FFFDF9`) bounded by micro-fine natural sand borders (`rgba(184, 131, 88, 0.12)`).
- **Ambient Lighting Glow (Interactive/Lamps):** Ambient shadows utilize a tinted terracotta-amber drop (`box-shadow: 0 16px 36px -10px rgba(184, 131, 88, 0.18)`), mimicking warm light passing through handwoven fabric shades.
- **Floating Modals & Overlays:** Supported by soft 12px backdrop blur over warm semi-translucent scrims (`rgba(45, 38, 33, 0.4)`).

## Shapes

The design system incorporates **Soft (Level 1)** geometry, emphasizing structured craft, architectural balance, and fine textile folding:

- Standard cards, interactive inputs, and buttons leverage subtle `0.25rem` (4px) to `0.5rem` (8px) corner softening.
- Arched imagery masks (`rounded-t-full` or large architectural radii) may be applied exclusively to hero lifestyle photography, echoing Middle Eastern archways and artisan lamp silhouettes.
- Product tags and micro-chips utilize gentle soft borders rather than synthetic modern pills, retaining an organic hand-labeled character.

## Components

### Buttons
- **Primary:** Solid soft terracotta (`#B88358`) background with light linen text (`#FFFDF9`). Subtle hover shifts to warm umber with a faint amber light bleed.
- **Secondary (Artisan Outline):** Unfilled button with a 1px border in `#B88358` and text in `#B88358`. Transitions to soft sand wash (`rgba(184, 131, 88, 0.08)`) on hover.
- **Text Link:** Understated serif or high-kerning label accompanied by a subtle directional hairline arrow that flips effortlessly for Arabic RTL layouts.

### Chips & Material Filters
- Outlined tags showcasing fabric types (Raw Linen, Egyptian Cotton, Handwoven Wool) and light warmth (2700K Warm Glow).
- Active state transitions to muted olive green (`#6B755D`) or soft terracotta fills with low-contrast, legible typography.

### Input Fields & Selectors
- Background filled with neutral linen-container (`#FFFDF9`), edged with a delicate border (`rgba(45, 38, 33, 0.15)`).
- On focus, border color shifts smoothly to `#B88358` with an amber ambient halo glow (`0 0 0 3px rgba(221, 161, 94, 0.2)`).
- Full support for Arabic right-aligned floating labels.

### Product & Showcase Cards
- Generous internal padding (`space-md` to `space-lg`), image-dominant display with warm beige tone backings.
- Price tags formatted with refined letter spacing.
- Material swatches (wood grains, linen thread previews) displayed as micro circular tactile discs below product titles.

### Ambient Lamp Toggle / Lighting Previewer
- Dedicated bespoke component enabling users to toggle a simulated "Room Ambient Light" mode (daylight neutral vs. evening warm glow) to observe how the lamp shades and textiles behave under authentic 2700K warm incandescent temperatures.