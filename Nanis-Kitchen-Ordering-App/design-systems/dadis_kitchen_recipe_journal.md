---
name: Dadi's Kitchen Recipe Journal
colors:
  surface: '#fff9ee'
  surface-dim: '#dfd9cf'
  surface-bright: '#fff9ee'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f9f3e8'
  surface-container: '#f3ede2'
  surface-container-high: '#ede8dd'
  surface-container-highest: '#e8e2d7'
  on-surface: '#1d1c15'
  on-surface-variant: '#56423c'
  inverse-surface: '#333029'
  inverse-on-surface: '#f6f0e5'
  outline: '#89726b'
  outline-variant: '#dcc1b8'
  surface-tint: '#9b4423'
  primary: '#984221'
  on-primary: '#ffffff'
  primary-container: '#b85936'
  on-primary-container: '#fffbff'
  inverse-primary: '#ffb59c'
  secondary: '#7d5700'
  on-secondary: '#ffffff'
  secondary-container: '#fdc254'
  on-secondary-container: '#725000'
  tertiary: '#3f644a'
  on-tertiary: '#ffffff'
  tertiary-container: '#577d61'
  on-tertiary-container: '#f6fff4'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffdbcf'
  primary-fixed-dim: '#ffb59c'
  on-primary-fixed: '#380c00'
  on-primary-fixed-variant: '#7c2d0d'
  secondary-fixed: '#ffdeaa'
  secondary-fixed-dim: '#f7bd4f'
  on-secondary-fixed: '#271900'
  on-secondary-fixed-variant: '#5f4100'
  tertiary-fixed: '#c3edcb'
  tertiary-fixed-dim: '#a7d0b0'
  on-tertiary-fixed: '#00210e'
  on-tertiary-fixed-variant: '#2a4e36'
  background: '#fff9ee'
  on-background: '#1d1c15'
  surface-variant: '#e8e2d7'
typography:
  display-lg:
    fontFamily: Epilogue
    fontSize: 44px
    fontWeight: '700'
    lineHeight: 52px
    letterSpacing: -0.01em
  display-lg-mobile:
    fontFamily: Epilogue
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
    letterSpacing: -0.01em
  headline-lg:
    fontFamily: Epilogue
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
  headline-lg-mobile:
    fontFamily: Epilogue
    fontSize: 26px
    fontWeight: '600'
    lineHeight: 34px
  headline-md:
    fontFamily: Epilogue
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  headline-sm:
    fontFamily: Epilogue
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
  body-xl:
    fontFamily: Nunito Sans
    fontSize: 20px
    fontWeight: '400'
    lineHeight: 32px
  body-lg:
    fontFamily: Nunito Sans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Nunito Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 26px
  label-lg:
    fontFamily: Nunito Sans
    fontSize: 16px
    fontWeight: '700'
    lineHeight: 24px
  label-md:
    fontFamily: Nunito Sans
    fontSize: 14px
    fontWeight: '700'
    lineHeight: 20px
    letterSpacing: 0.02em
  label-sm:
    fontFamily: Nunito Sans
    fontSize: 12px
    fontWeight: '700'
    lineHeight: 18px
    letterSpacing: 0.04em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1.5rem
  gutter-mobile: 1rem
  margin: 2.5rem
  margin-mobile: 1.25rem
  space-xs: 0.375rem
  space-sm: 0.75rem
  space-md: 1.25rem
  space-lg: 2rem
  space-xl: 3rem
---

## Brand & Style

This design system captures the sensory and emotional warmth of opening an heirloom family recipe journal kept carefully in a sunlit Pakistani courtyard kitchen. It blends the tactile charm of organic watercolour washes, sun-bleached cotton paper, and delicate handwritten margin notes with high-clarity modern interface architecture.

### Target Audience & Emotional Intent
- **Audience:** Intergenerational home cooks, diaspora families rediscovering cultural culinary heritage, and elder cooks who demand generous touch targets, clear contrasts, and comforting clarity.
- **Emotional Resonance:** Intimate, reassuring, deeply nostalgic, and lovingly personal. The interface should feel less like a software application and more like a cherished physical keepsake.

### Style Direction: Tactile Storybook Skeuomorphism
- **Materiality:** Soft, fibrous textured paper canvases with deckled or torn edges and gentle organic pigment bleeds.
- **Micro-Touches:** Subtle stamps, aged saffron specks, and warm ink accents balanced by structured, senior-friendly readability standards.

## Colors

The palette is drawn directly from natural culinary elements: clay handis, fragrant blooming saffron threads, bruised sage, dried rose petals, and sun-baked earthen courtyards. High contrast is rigorously preserved by anchoring all typography in rich roasted espresso brown rather than synthetic black.

### Palette Architecture
- **Canvas & Surface Neutral (`#FBF5EA`):** Aged handmade ivory cotton rag. Never use pure `#FFFFFF` across cards or primary backdrops.
- **Surface Elevation Neutral (`#F4EAD6`):** Deeper parchment used for recessed inputs, recipe step dividers, and stacked layers.
- **Primary Ink (`#3E2723`):** Deep roasted walnut brown providing AAA-compliant legibility across pale cream foundations.
- **Primary Spice Terracotta (`#D9734E`):** Baked clay pots and ground chili. Primary calls-to-action, active indicator states, and key navigational landmarks.
- **Secondary Saffron Bloom (`#F2B84B`):** Warm golden undertones for badges, star ratings, saved favorites, and warm highlight ribbons.
- **Tertiary Garden Sage (`#8DB596`):** Fresh coriander and mint leaves. Ideal for dietary tags, herbal tips, preparation status, and completed steps.
- **Accent Gulab Rose (`#E8A5A5`):** Soft dusty pink wash used for delicate category flags, heart states, and decorative borders.

## Typography

The type scale combines expressive, artisanal heading letterforms with exceptionally legible body typography tuned for senior readability and comfortable kitchen prep at arm's length.

### Editorial Hierarchy
- **Expressive Titles & Recipe Headers (`Epilogue`):** Distinctive, geometric-yet-humanist weights that capture the artisanal, hand-lettered storybook cadence without sacrificing structural stability or clarity.
- **Reading & Measurement Standards (`Nunito Sans`):** Softened terminals, wide counter spaces, and open x-height ensure effortless skimming of ingredient measurements and multi-step recipes. Minimum body size on mobile is locked at `16px`.
- **Nutritional & Utility Labels:** Upweighted to `600` or `700` weight to guarantee legibility under dimmer kitchen lighting.

## Layout & Spacing

A forgiving, unhurried spatial rhythm that evokes generous margins around physical paper pages. Layouts preserve generous negative space so tap zones never collide.

### Grid Rhythm & Responsive Adaptations
- **Mobile (< 768px):** 4-column layout with 20px outer margin, single-card vertical scroll, sticky quick-action bars pinned at bottom for one-handed thumb interaction.
- **Tablet (768px - 1024px):** 8-column layout with 32px outer margin, supporting side-by-side recipe step execution and dynamic ingredient checklist panels.
- **Desktop (> 1024px):** 12-column layout with 40px outer margin, max container width constrained to `1200px` to maintain a readable two-page open-cookbook proportion.

### Touch Accessibility Rule
All interactive elements adhere strictly to a minimum target size of `48px × 48px`, supplemented by a minimum `8px` spatial cushion around all active hot zones.

## Elevation & Depth

Depth is conveyed through layered physical stationery, warm atmospheric ambient cast-shadows, and organic ink edges rather than harsh synthetic elevations.

### Tonal Stratification
1. **Underlay (Base Canvas):** Raw `#FBF5EA` cream paper with a faint, repeating natural fiber grain simulation.
2. **Surface Level 1 (Recipe Cards & Sheets):** `#FFFDF9` paper cutouts with soft, organic drop shadows tinted with warm clay: `0 4px 16px -2px rgba(62, 39, 35, 0.08), 0 2px 6px -1px rgba(217, 115, 78, 0.06)`.
3. **Surface Level 2 (Floating Ingredients / Active Timers):** Slightly angled (+0.5deg or -0.5deg) elevated cards using deeper tinted diffusion: `0 12px 28px -4px rgba(62, 39, 35, 0.12), 0 4px 10px -2px rgba(62, 39, 35, 0.05)`.
4. **Modals & Drawers:** Grounded by a rich, warm umber overlay at 40% opacity (`rgba(62, 39, 35, 0.40)`), featuring torn-top borders mimicking recipes torn cleanly from vintage spiral bindings.

## Shapes

The geometry reflects softened handmade parchment cards and smooth terracotta kitchenware. Edges are gentle and comforting without dissolving into completely generic modern pills.

### Edge Details
- **Corner Radii:** Cards, modals, and container panels use `16px` to `24px` radius to reflect rounded paper corners that have softened over decades of thumbing through pages.
- **Torn & Deckle Edge Masks:** Applied to card top-headers or floating banner edges via repeating irregular CSS mask paths for an authentic storybook impression.
- **Stamp & Pill Tags:** Specialty badges (such as "Dadi's Secret" or "Slow Dum") utilize `9999px` full-capsule pill enclosures.

## Components

### Buttons
- **Primary ("Start Cooking", "Save Heirloom"):** Solid `#D9734E` terracotta fill, `#FBF5EA` text, minimum height `52px`. Soft drop shadow `0 4px 12px rgba(217, 115, 78, 0.28)`. On hover/tap, scales subtly to `0.98` with a deepened shade `#C4623E`.
- **Secondary ("Browse Spices"):** Cream-filled button with a double-line stitched terracotta border (`2px solid #D9734E`), `#3E2723` text.
- **Ghost Action:** Saffron wash (`#F2B84B` at 15% opacity), deep brown text, no hard outline.

### Recipe Cards
- Ivory white background (`#FFFDF9`) framed by a subtle, soft decorative inset border (`1px dashed #D9734E` at 30% opacity).
- Card headers feature an accent stamp ribbon in Dusty Rose (`#E8A5A5`) or Sage (`#8DB596`).
- Minimum tap area spans the entire card, preventing precision-tap frustration.

### Input Fields & Search Bars
- Background set to recessed warm parchment `#F4EAD6` with a soft inner shadow simulating debossed handmade paper.
- Border is `1.5px solid #D9734E` at 40% resting opacity, expanding to full terracotta with a saffron glow halo on focus.
- Placeholder text in softened umber (`#3E2723` at 60% opacity), font size minimum `18px`. Minimum height is `54px`.

### Checkboxes & Step Counters
- Generous `28px × 28px` target checkbox boxes with soft `6px` rounded corners.
- Checked state fills with Garden Sage (`#8DB596`) featuring an ink-drawn off-white checkmark.
- Step numbers appear within a circle reminiscent of a spice seal in Terracotta (`#D9734E`) with white lettering.

### Category Chips & Dietary Badges
- High-contrast pill tags with generous `8px 16px` padding and `48px` minimum height when interactive.
- Filter chips default to `#F4EAD6` with `#3E2723` text; active chips switch to `#F2B84B` background with deep brown typography.

### Specialized Components
- **"Dadi's Note" Tip Box:** Styled like an off-center index card pinned to the recipe with a soft rose paper wash (`#FBEAEA`), dashed border, and conversational italic styling for cooking wisdom.
- **Spice Intensity Gauge:** Custom tactile meter styled like painted brass spoons filled with saffron and chili shades.
- **Kitchen Timer Widget:** Large `36px` numbers on a parchment plate with oversized `48px` pause/reset buttons designed for wet or floured fingers.