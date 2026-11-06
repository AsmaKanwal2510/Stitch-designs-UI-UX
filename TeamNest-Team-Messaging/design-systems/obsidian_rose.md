---
name: Obsidian Rose
colors:
  surface: '#181216'
  surface-dim: '#181216'
  surface-bright: '#3f373c'
  surface-container-lowest: '#120c10'
  surface-container-low: '#201a1e'
  surface-container: '#241e22'
  surface-container-high: '#2f282c'
  surface-container-highest: '#3a3337'
  on-surface: '#ecdfe5'
  on-surface-variant: '#d7c1c3'
  inverse-surface: '#ecdfe5'
  inverse-on-surface: '#362e33'
  outline: '#9f8c8e'
  outline-variant: '#524345'
  surface-tint: '#ffb2bc'
  primary: '#ffb2bc'
  on-primary: '#551e29'
  primary-container: '#c77b86'
  on-primary-container: '#4c1722'
  inverse-primary: '#8c4b55'
  secondary: '#f0bba7'
  on-secondary: '#49281a'
  secondary-container: '#654031'
  on-secondary-container: '#e0ad99'
  tertiary: '#e6b9dd'
  on-tertiary: '#452542'
  tertiary-container: '#ad84a6'
  on-tertiary-container: '#3e1f3b'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#ffd9dd'
  primary-fixed-dim: '#ffb2bc'
  on-primary-fixed: '#3a0915'
  on-primary-fixed-variant: '#70343e'
  secondary-fixed: '#ffdbce'
  secondary-fixed-dim: '#f0bba7'
  on-secondary-fixed: '#301408'
  on-secondary-fixed-variant: '#623e2f'
  tertiary-fixed: '#ffd7f5'
  tertiary-fixed-dim: '#e6b9dd'
  on-tertiary-fixed: '#2e102c'
  on-tertiary-fixed-variant: '#5e3b59'
  background: '#181216'
  on-background: '#ecdfe5'
  surface-variant: '#3a3337'
typography:
  display-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 36px
    fontWeight: '700'
    lineHeight: 44px
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 28px
    fontWeight: '700'
    lineHeight: 36px
    letterSpacing: -0.01em
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 28px
    fontWeight: '600'
    lineHeight: 36px
    letterSpacing: -0.015em
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 22px
    fontWeight: '600'
    lineHeight: 28px
    letterSpacing: -0.01em
  headline-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 18px
    fontWeight: '600'
    lineHeight: 24px
    letterSpacing: '0'
  body-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
    letterSpacing: '0'
  body-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
    letterSpacing: 0.005em
  body-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 16px
    letterSpacing: 0.01em
  label-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.01em
  label-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.02em
  label-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 11px
    fontWeight: '700'
    lineHeight: 14px
    letterSpacing: 0.04em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1rem
  gutter-desktop: 1.5rem
  margin: 1rem
  margin-tablet: 1.5rem
  margin-desktop: 2rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
---

## Brand & Style
The design system establishes an atmospheric, high-end collaborative workspace tailored for creative directors, luxury agencies, and fashion-forward product teams. It balances executive sophistication with fluid productivity, departing from austere enterprise tools through warm, tactile luxury.

Visual hallmarks draw from contemporary dark-mode minimalism blended with subtle physical depth:
- **Atmospheric Darkness:** Anchored in deep velvet plum rather than sterile true blacks, evoking intimate studio environments.
- **Warm Metallic Accents:** Rose gold and burnished peach act as focused beacons of intent, providing tactile warmth against obsidian surfaces.
- **Editorial Restraint:** Generous negative space, whisper-thin dividers, and precise typographic tracking establish high-fashion editorial clarity without sacrificing information density.

## Colors
The palette leverages chromatic undertones of dried rose petals, dark plums, and radiant copper to create an immersive, low-strain canvas.

### Surface Architecture
- **Root Canvas (`#1A1418`):** Deep plum ground beneath floating panels and toolbars.
- **Sidebar & Navigation (`#0F0B0E`):** Pure obsidian with subtle warm violet inflection to isolate navigation anchors.
- **Primary Content & Stage (`#221A20`):** Soft plum surface providing contrast against root frames.
- **Card & Elevated Surface (`#2A2028`):** Mid-tier containers, inputs, and modal backgrounds.
- **Thread & Alternating Cards (`#33242E`, `#3B2A2A`):** Tonal variations used for direct messages, distinct thread levels, and conversational tempo.

### Accents & Metallics
- **Primary Rose Gold (`#B76E79`):** Interactive primary triggers, key highlights, and active states.
- **Luminous Rose Gold (`#E8B4A0`):** High-priority indicators, active channel pills, and badges. Pairs exclusively with deep espresso-plum text (`#2A1A16`) to guarantee WCAG AA 4.5:1+ contrast.
- **Atmospheric Gradient:** Transitions from plum velvet (`#3D1E3A`) to dusty rose (`#B76E79`) for banner highlights, send actions, and premium states.

### Content Contrast
- **Text High-Emphasis (`#F5EAE6`):** Delicate cream for primary text on dark backdrops, softening harsh light-bleed.
- **Sidebar Text (`#F2E4DE`):** Warm oyster tone for navigation labels.
- **Text Low-Emphasis (`#9C8A90`):** Muted mauve-gray for metadata, timestamps, and placeholder copy.
- **Border Structural (`#3A2D36`):** Low-contrast dividers and input perimeters.

## Typography
Plus Jakarta Sans serves as the universal type system across all hierarchies. Its geometric foundations provide clean functional rendering for rapid messaging, while its open apertures and subtle calligraphic details echo the elegance of modern luxury editorial layouts.

### Usage Rules
- **Headlines:** Display and Headline roles employ negative letter spacing (`-0.01em` to `-0.02em`) to bind character forms tightly, lending authority to workspace titles and view headers.
- **Readability & Chat Body:** `body-md` is the conversational standard. The 20px line-height on 14px size ensures sustained reading comfort without visual vibration.
- **Labels & Microcopy:** `label-sm` utilizes bold weights (`700`) and expanded letter spacing (`0.04em`) in all-caps scenarios for timestamps, category headers, and metadata chips.

## Layout & Spacing
The layout model employs a responsive, multi-tier fluid frame strategy calibrated for collaborative workspaces:

### Pane Architecture
- **Sidebar (Workspace & Channels):** Fixed width of 260px on desktop screens (>1024px); collapsible into an off-canvas drawer on mobile and tablet.
- **Primary Stage (Feed & Active Conversation):** Fluid canvas that scales between a minimum 400px and maximum 960px reading column to prevent excessive line lengths.
- **Context Panel (Threads & User Profile):** Rigid 340px right dock on desktop screens (>1280px); replaces main view or stacks as an overlay on smaller viewports.

### Rhythm
All spatial gaps strictly adhere to a 4px/8px incremental base:
- `space-xs` (4px) for inline badge gaps and icon pairings.
- `space-sm` (8px) for conversational message clusters and input interior padding.
- `space-md` (16px) for module separation, structural gutters, and card interiors.
- `space-lg` (24px) for panel header padding and section boundaries.
- `space-xl` (40px) for layout margins and hero empty states.

## Elevation & Depth
Depth avoids artificial drop shadows, relying instead on **tonal stepping** and **warm ambient halos**.

### Layering Hierarchy
1. **Foundation Level (0dp):** App Sidebar (`#0F0B0E`) and root gutters (`#1A1418`).
2. **Surface Level (1dp):** Main chat stage (`#221A20`) framed with a subtle 1px outline (`#3A2D36`) to cleanly segregate navigational channels.
3. **Elevated Elements (2dp):** Message bubbles (`#33242E` / `#3B2A2A`), input composer (`#2A2028`), and card lists. Raised subtly using an ambient shadow: `0 4px 20px -2px rgba(15, 11, 14, 0.65)`.
4. **Overlay Elements (3dp):** Popovers, dropdown menus, and active modal overlays (`#2A2028`) featuring an intensified warm-cast shadow: `0 12px 32px -4px rgba(10, 6, 9, 0.85)` paired with a soft rose perimeter glow (`0 0 0 1px rgba(183, 110, 121, 0.2))`.

### Focus Rings
All keyboard-focused elements project a 2px offset ring in `#E8B4A0` with a 2px gap in `#1A1418`.

## Shapes
The shape hierarchy follows standard rounded geometry (`0.5rem` / `8px` baseline), balancing crisp structure with tactile softness.

### Shape Scaling
- **Default (`0.5rem` / `8px`):** Input fields, message bubbles, context menus, and contextual cards.
- **Medium (`0.75rem` / `12px`):** Modal windows, media cards, and contextual workspace boards.
- **Full Pill (`9999px`):** Navigation indicator badges, active channel selections, status pills, and interactive chips.

## Components

### Buttons
- **Primary:** Background in `#B76E79` with `#F5EAE6` text. Hover transitions to `#C9828D`; active state scales to 0.98. Border radius: `0.5rem`.
- **Accent / Highlight:** Background in `#E8B4A0` with high-contrast text in `#2A1A16`. Reserved for conversion actions, upgrades, and pinned alerts.
- **Gradient Trigger (Send / Primary Action):** Linear gradient from `#3D1E3A` to `#B76E79` at 135deg. Hover shifts gradient brightness by 10%.
- **Ghost / Tertiary:** Transparent base with `#F5EAE6` label; hover introduces `#2A2028` fill.

### Channel Navigation Pills
- **Inactive Channels:** `#F2E4DE` at 70% opacity with transparent background. Hover renders `#221A20` backing.
- **Active Channel:** Fully saturated `#E8B4A0` pill spanning the row item, featuring high-contrast `#2A1A16` text and bold weight (`600`).

### Message Bubbles
- **Incoming Messages:** Backed by `#33242E` with text `#F5EAE6`. 8px corner radii, with bottom-left corner tightened to 2px for speaker grounding.
- **Outgoing / Alternate Messages:** Backed by `#3B2A2A` with text `#F5EAE6`. Bottom-right corner tightened to 2px.
- **Interactive Metadata / Chips:** Solid `#3B2A2A` containers with `#F5EAE6` typography and 1px border `#3A2D36`.

### Input Composer
- **Canvas:** `#2A2028` solid background with a persistent 1px border in `#3A2D36`.
- **Focus State:** Border transitions to `#B76E79` with a subtle outward halo: `0 0 0 3px rgba(183, 110, 121, 0.15)`.
- **Text & Placeholder:** `#F5EAE6` primary input text, `#9C8A90` placeholder copy.
- **Action Icons:** Muted mauve `#9C8A90` with hover state brightening to `#E8B4A0`.

### Selection Controls (Checkboxes & Radios)
- **Resting:** 1px border `#3A2D36` on `#1A1418` fill.
- **Selected:** Solid `#B76E79` background with `#F5EAE6` check glyph.

### Cards & Panels
- **Structure:** Encased in `#221A20` or `#2A2028` with 1px border `#3A2D36`.
- **Header Accents:** Optional top edge 1px highlight gradient transitioning from `#B76E79` to transparent.