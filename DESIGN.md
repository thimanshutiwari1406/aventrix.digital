---
name: Synthetic Vanguard
colors:
  surface: '#14083d'
  surface-dim: '#14083d'
  surface-bright: '#3b3264'
  surface-container-lowest: '#0f0338'
  surface-container-low: '#1d1245'
  surface-container: '#211749'
  surface-container-high: '#2c2254'
  surface-container-highest: '#372d60'
  on-surface: '#e6deff'
  on-surface-variant: '#bacbb9'
  inverse-surface: '#e6deff'
  inverse-on-surface: '#32295b'
  outline: '#849584'
  outline-variant: '#3b4a3d'
  surface-tint: '#00e473'
  primary: '#f5fff2'
  on-primary: '#003918'
  primary-container: '#39ff88'
  on-primary-container: '#007236'
  inverse-primary: '#006d34'
  secondary: '#cabeff'
  on-secondary: '#31009a'
  secondary-container: '#4816cb'
  on-secondary-container: '#b9aaff'
  tertiary: '#fffbff'
  on-tertiary: '#33226f'
  tertiary-container: '#e4dbff'
  on-tertiary-container: '#6657a6'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#63ff95'
  primary-fixed-dim: '#00e473'
  on-primary-fixed: '#00210b'
  on-primary-fixed-variant: '#005225'
  secondary-fixed: '#e6deff'
  secondary-fixed-dim: '#cabeff'
  on-secondary-fixed: '#1c0062'
  on-secondary-fixed-variant: '#4816cb'
  tertiary-fixed: '#e7deff'
  tertiary-fixed-dim: '#cbbeff'
  on-tertiary-fixed: '#1e055a'
  on-tertiary-fixed-variant: '#4a3a87'
  background: '#14083d'
  on-background: '#e6deff'
  surface-variant: '#372d60'
typography:
  display:
    fontFamily: Inter
    fontSize: 72px
    fontWeight: '800'
    lineHeight: 80px
    letterSpacing: -0.03em
  display-mobile:
    fontFamily: Inter
    fontSize: 40px
    fontWeight: '800'
    lineHeight: 48px
    letterSpacing: -0.025em
  headline-lg:
    fontFamily: Inter
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.025em
  headline-lg-mobile:
    fontFamily: Inter
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Inter
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
    letterSpacing: -0.02em
  headline-sm:
    fontFamily: Inter
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
    letterSpacing: -0.015em
  title-lg:
    fontFamily: Inter
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
    letterSpacing: -0.01em
  title-md:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '600'
    lineHeight: 26px
    letterSpacing: -0.01em
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
    letterSpacing: -0.005em
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
    letterSpacing: 0em
  body-sm:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
    letterSpacing: 0em
  label-lg:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.04em
  label-md:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.06em
  label-sm:
    fontFamily: Inter
    fontSize: 11px
    fontWeight: '600'
    lineHeight: 14px
    letterSpacing: 0.08em
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
  margin: 4rem
  margin-tablet: 2rem
  margin-mobile: 1.25rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
---

## Brand & Style
The design system embodies high-voltage digital craft, engineered for an elite, futuristic web design agency. It projects visionary capability, technical precision, and unapologetic ambition. The visual language blends immersive cyber-luxe minimalism with high-end glassmorphism—grounded in void-depth purples and energized by razor-sharp neon green strikes. 

The emotional response is electric, exclusive, and undeniably cutting-edge: users should feel like they are piloting next-generation creative infrastructure rather than browsing a static portfolio.

## Colors
The palette leverages a deep photonic hierarchy tailored exclusively for dark surfaces:

- **Primary Accent (`#39FF88`)**: A high-voltage, radiant neon green reserved strictly for high-impact actions, critical signals, hyper-focused indicators, and interactive callouts.
- **Secondary / Radiance (`#7C5CFF`)**: Soft atmospheric purple used for interactive states, inner glows, directional card outlines, and ambient ambient light dispersion.
- **Surface Deep (`#2D1B69`)**: Upper bounds of canvas gradients and primary component containers.
- **Surface Void (`#1A0F42`)**: Canvas base level, deep card backgrounds, and heavy structural backdrops. Also functions as the crisp, high-contrast foreground text tone atop neon green surfaces.
- **Text Primary (`#FFFFFF`) & Text Muted (`#F5F3FF` at 70-85% alpha)**: Pure white drives primary hierarchy, while soft lavender delivers glare-free body readability across dense spatial backgrounds.

## Typography
Typography is strictly utilitarian and geometric, utilizing Inter's engineered clarity. 

Headlines employ tight, aggressive negative letter-spacing paired with authoritative weights (700–800) to create a commanding architectural stance. Micro-labels, meta indicators, and system tags use uppercase typesetting with positive letter-spacing (`+0.04em` to `+0.08em`) to mimic telemetry readouts and terminal precision.

## Layout & Spacing
The layout follows a 12-column responsive fluid grid anchored by a 1440px maximum viewport lock, ensuring panoramic expansiveness without degradation on ultra-wide viewports.

- **Desktop (1024px+)**: 12 columns, 24px (`1.5rem`) gutters, dynamic section margin of 64px (`4rem`).
- **Tablet (768px – 1023px)**: 8 columns, 24px (`1.5rem`) gutters, 32px (`2rem`) screen margins. Complex showcases collapse from horizontal tiers to stacked split-views.
- **Mobile (<768px)**: 4 columns, 16px (`1rem`) gutters, 20px (`1.25rem`) outer canvas margins. Multi-column metric decks and showcases cascade strictly into single-column flows.

## Elevation & Depth
Elevation eschews conventional neutral drop shadows in favor of translucent chromatic layering, chromatic refraction, and energetic luminescence.

- **Canvas Base**: Linear multi-stop gradient spanning `135deg` from `#2D1B69` down to `#1A0F42`.
- **Glassmorphic Tier 1 (Cards & Modules)**: Surfaces use `#1A0F42` at 65% opacity combined with `backdrop-filter: blur(24px) saturate(160%)`. Borders are 1px solid, tinted with `#7C5CFF` at 30% alpha.
- **Glassmorphic Tier 2 (Floating Nav, Modals)**: `#2D1B69` at 75% opacity, `backdrop-filter: blur(32px)`, 1px solid `#7C5CFF` at 50% opacity, enhanced by an interior highlight rim (`inset 0 1px 1px 0 rgba(245, 243, 255, 0.15)`).
- **Luminescent Accent Shadow**: Active, featured, or focused states activate a signature high-energy drop shadow: `box-shadow: 0 0 20px rgba(57, 255, 136, 0.35)`.
- **Soft Ambient Glow**: Hovering interactive elements activates an expansive violet halo: `box-shadow: 0 8px 32px rgba(124, 92, 255, 0.25)`.

## Shapes
Shapes strike a modern balance between technical structure and ergonomic elegance. Structural containers, interactive cards, and media wrappers standardize on 16px (`1rem`) to 24px (`1.5rem`) corner radii (`rounded-lg` and `rounded-xl`). 

Secondary elements such as pill tags, action chips, and circular icon nodes leverage full roundedness (`rounded-full`) to punctuate the grid with sleek, organic counter-forms.

## Components

### Buttons
- **Primary Electric**: Solid `#39FF88` background, `#1A0F42` bold text, rounded at 16px. On hover: shifts brightness up, initiates `0 0 20px rgba(57, 255, 136, 0.45)`, scale transition `1.02`.
- **Secondary Ghost / Border**: Translucent surface (`rgba(26, 15, 66, 0.4)`), 1px stroke of `#7C5CFF`, text `#F5F3FF`. On hover: border switches to `#39FF88`, text shifts to pure `#FFFFFF`, casting a soft violet halo.
- **Icon Buttons**: Strict 1:1 aspect ratio, glassmorphic backing, `#7C5CFF` border, with iconography illuminated in `#39FF88`.

### Glass Cards & Showcase Modules
- Multi-layered surfaces featuring 20px corner radius, background blurred with `#1A0F42` at 60% opacity. 
- 1px border gradient transitioning from `#7C5CFF` (top-left) to transparent (bottom-right).
- On card hover: border illuminates uniformly in `#7C5CFF` at 70% opacity, accompanied by `0 12px 32px rgba(124, 92, 255, 0.2)`.

### Form Controls & Input Fields
- Inputs feature a dark tint (`rgba(26, 15, 66, 0.8)`), 16px radius, and a 1px border using `#7C5CFF` at 30% alpha.
- Placeholder text in `#F5F3FF` at 40% opacity; typed text is crisp `#FFFFFF`.
- Focus state: border turns into `#39FF88` with a tight `0 0 12px rgba(57, 255, 136, 0.3)` glow. No default browser ring.

### Chips & Meta Badges
- Pill-shaped (`rounded-full`), padded with `0.375rem 0.875rem`.
- Background: `#2D1B69` at 50% opacity, stroke 1px `#7C5CFF` at 40%. Text set in `label-sm` uppercase, rendered in `#F5F3FF`.
- Active / Status Variant: 6px pulsing dot in `#39FF88` preceding the label text.

### Checkboxes & Radios
- 20px boxes / circles with 1px `#7C5CFF` border.
- Selected state: solid fill with `#39FF88`, displaying a `#1A0F42` centered checkmark or dot, radiating `0 0 10px rgba(57, 255, 136, 0.4)`.

### Interactive Telemetry & Metric Displays
- Custom component for client statistics and agency performance indices.
- Framed in Tier 1 glass panels with large numeric displays set in bold Inter (`display` size) rendered in `#FFFFFF`, flanked by micro neon green accent lines (`#39FF88`).