---
name: Luminous Strategy
colors:
  surface: '#fbf9f5'
  surface-dim: '#dbdad6'
  surface-bright: '#fbf9f5'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f5f3ef'
  surface-container: '#efeeea'
  surface-container-high: '#eae8e4'
  surface-container-highest: '#e4e2de'
  on-surface: '#1b1c1a'
  on-surface-variant: '#434655'
  inverse-surface: '#30312e'
  inverse-on-surface: '#f2f0ed'
  outline: '#737686'
  outline-variant: '#c3c6d7'
  surface-tint: '#0053db'
  primary: '#004ac6'
  on-primary: '#ffffff'
  primary-container: '#2563eb'
  on-primary-container: '#eeefff'
  inverse-primary: '#b4c5ff'
  secondary: '#565e74'
  on-secondary: '#ffffff'
  secondary-container: '#dae2fd'
  on-secondary-container: '#5c647a'
  tertiary: '#784b00'
  on-tertiary: '#ffffff'
  tertiary-container: '#996100'
  on-tertiary-container: '#ffeedd'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#dbe1ff'
  primary-fixed-dim: '#b4c5ff'
  on-primary-fixed: '#00174b'
  on-primary-fixed-variant: '#003ea8'
  secondary-fixed: '#dae2fd'
  secondary-fixed-dim: '#bec6e0'
  on-secondary-fixed: '#131b2e'
  on-secondary-fixed-variant: '#3f465c'
  tertiary-fixed: '#ffddb8'
  tertiary-fixed-dim: '#ffb95f'
  on-tertiary-fixed: '#2a1700'
  on-tertiary-fixed-variant: '#653e00'
  background: '#fbf9f5'
  on-background: '#1b1c1a'
  surface-variant: '#e4e2de'
typography:
  display-hero:
    fontFamily: Plus Jakarta Sans
    fontSize: 56px
    fontWeight: '800'
    lineHeight: 64px
    letterSpacing: -0.03em
  display-hero-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 38px
    fontWeight: '800'
    lineHeight: 44px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 40px
    fontWeight: '700'
    lineHeight: 48px
    letterSpacing: -0.025em
  headline-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 28px
    fontWeight: '700'
    lineHeight: 36px
    letterSpacing: -0.015em
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
    letterSpacing: -0.015em
  headline-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
    letterSpacing: -0.01em
  body-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
    letterSpacing: -0.005em
  body-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  body-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  label-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.01em
  label-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 12px
    fontWeight: '700'
    lineHeight: 16px
    letterSpacing: 0.05em
  metric-number:
    fontFamily: Plus Jakarta Sans
    fontSize: 48px
    fontWeight: '800'
    lineHeight: 52px
    letterSpacing: -0.03em
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
  margin: 3rem
  margin-mobile: 1.25rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
---

## Brand & Style

This design system establishes an editorial, high-performance digital presence tailored for a modern digital marketer and content strategist. It bridges the structured credibility of enterprise marketing with the dynamic, high-engagement sensibility of top-tier content creation. 

The aesthetic is grounded in **Polished Glassmorphic Modernism**: combining crisp typographic discipline, rich high-contrast typography, and layered frosted glass surfaces resting above warm, radiant off-white canvases. The visual mood evokes analytical rigor, creative flair, and effortless sophistication—rejecting generic template tropes in favor of bespoke personal branding with purposeful motion and tactility.

## Colors

The palette balances authoritative depth against warm, inviting baseline surfaces:

- **Primary (`#2563EB`)**: Drives interactive focus, primary actions, forward momentum, and active navigation indicators. Hover states step into `#1D4ED8`.
- **Secondary (`#0F172A`)**: The deep navy/indigo foundation anchor. Governs primary headers, high-emphasis text, high-contrast dark sections, and the anchoring footer.
- **Tertiary (`#F59E0B`)**: An amber-gold metric accent reserved for badges, analytical triumphs, star achievements, and KPI growth highlights. Never used for large body copy.
- **Neutral Canvas (`#FBF9F5`)**: A curated warm alabaster off-white providing rich editorial texture without the clinical sterility of `#FFFFFF`. Secondary card backgrounds step to semi-translucent whites (`rgba(255, 255, 255, 0.72)`).
- **Subtle Borders & Separators**: Tinted slate-blue borders (`#E2E8F0` or `rgba(15, 23, 42, 0.08)`) keep boundaries light and airy.

## Typography

Typographic scale is defined purely through **Plus Jakarta Sans**, utilizing its geometric clarity, tall x-height, and sculpted apertures. 

- **Display & Headlines**: Emphasize tight tracking (`-0.02em` to `-0.03em`) and heavy weights (`700` and `800`) in secondary navy (`#0F172A`) to communicate sharp strategic authority.
- **Body & Paragraphs**: Rely on generous line-height ratios (1.5–1.55) to optimize scanning ease for case studies and campaign briefs.
- **Badges & Microcopy**: Render in `label-sm` with upper-case styling and positive letter-spacing (`0.05em`) for quick tag readability across portfolio categories.

## Layout & Spacing

The architecture operates on an 8pt spatial grid configured across an asymmetric 12-column layout for desktop and a 4-column layout for mobile:

- **Desktop (min-width: 1024px)**: Max container width pinned to `1280px` with `margin: 3rem`. Primary case studies employ staggered 7/5 column pairings to break repetitive blocks.
- **Tablet (768px – 1023px)**: 8-column layout with `gutter: 1.5rem`, reflowing multi-card metric grids into 2-column segments.
- **Mobile (< 768px)**: 4-column fluid layout with `margin: 1.25rem` and `gutter: 1rem`. Glassmorphism cards shift to full-width stacked arrangements with tight internal padding.

## Elevation & Depth

Visual hierarchy uses frosted glassmorphism stacked against high-clarity ambient depth:

- **Surface Level 0 (Base)**: Warm natural canvas (`#FBF9F5`) with occasional radial gradients of muted royal blue (`rgba(37, 99, 235, 0.04)`) and warm amber (`rgba(245, 158, 11, 0.03)`).
- **Surface Level 1 (Frosted Glass Cards)**: Background `rgba(255, 255, 255, 0.72)`, backdrop filter blur `16px`, enclosed by a fine translucent light boundary (`1px solid rgba(255, 255, 255, 0.8)` on top/left, `rgba(15, 23, 42, 0.06)` on bottom/right) paired with an ambient shadow: `0 10px 30px -10px rgba(15, 23, 42, 0.06)`.
- **Surface Level 2 (Elevated & Active States)**: On hover or active focus, cards escalate with backdrop blur `24px`, background opacity `0.85`, and an elevated drop shadow: `0 20px 40px -12px rgba(15, 23, 42, 0.12)`.
- **Surface Level 3 (Navbars & Modals)**: Sticky navigation utilizes high-refraction glass (`rgba(251, 249, 245, 0.82)`, backdrop filter `20px`, border bottom `1px solid rgba(15, 23, 42, 0.06)`).

## Shapes

A balanced `roundedness: 2` form language ensures modern approachability while avoiding excessive cartoonishness:

- **Buttons & Interactive Tags**: Standard buttons carry `rounded-lg` (1rem / 16px) or full circular pills for floating micro-actions.
- **Cards & Case Study Frames**: Apply `rounded-xl` (1.5rem / 24px) to soften analytical content while framing creative photography and metrics cleanly.
- **Input Fields & Dropdowns**: Standardized at `0.75rem` (12px) to harmonize with form elements and contact containers.

## Components

### Buttons
- **Primary**: Solid blue (`#2563EB`), text `#FFFFFF`, font `label-md`. Subtle hover elevation to `#1D4ED8` with a micro-transition (`all 200ms cubic-bezier(0.16, 1, 0.3, 1)`).
- **Secondary / Ghost**: Background `rgba(255, 255, 255, 0.65)`, border `1px solid rgba(15, 23, 42, 0.12)`, text `#0F172A`. On hover, background shifts to pure white with ambient rim lighting.
- **CTA Icon Support**: Subtle trailing micro-arrow (`16px`) that translates 4px rightward on hover.

### Metric & KPI Cards
- Large numerical values set in `metric-number` using `#0F172A`, topped with a small amber-accented metric pill (`#FEF3C7` background, `#D97706` text, label-sm).
- Subtle upward-trend indicator arrows and clean data labels positioned directly beneath the figure.

### Achievement Badges & Chips
- **Status/Topic Chips**: Background `rgba(37, 99, 235, 0.08)`, text `#2563EB`, border `1px solid rgba(37, 99, 235, 0.2)`.
- **Top Achievement Badges**: Background `rgba(245, 158, 11, 0.1)`, text `#B45309`, border `1px solid rgba(245, 158, 11, 0.3)`. Compact rounded pill styling with an optional leading star or trophy icon.

### Portfolio Project Cards
- Dual-zone construction: Top 60% dedicated to high-resolution campaign assets/mockups with a subtle inner border; bottom 40% frosted container containing industry category chip, headline-sm title, concise description, and an inline live link.

### Input Fields & Contact Elements
- Surfaces employ subtle translucent white (`rgba(255, 255, 255, 0.8)`), inset padding `0.875rem 1rem`, border `1px solid rgba(15, 23, 42, 0.12)`.
- Active focus state: Crisp focus ring `0 0 0 3px rgba(37, 99, 235, 0.2)` with border color shifting to `#2563EB`.

### Footer
- High-contrast transition: Rich Navy (`#0F172A`) backdrop, crisp white typography, subtle gray secondary links (`#94A3B8`), and vibrant primary blue hover accents.