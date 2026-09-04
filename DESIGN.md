---
name: Modern Architectural Craftsmanship
colors:
  surface: '#0f1417'
  surface-dim: '#0f1417'
  surface-bright: '#353a3d'
  surface-container-lowest: '#0a0f11'
  surface-container-low: '#171c1f'
  surface-container: '#1b2023'
  surface-container-high: '#262b2d'
  surface-container-highest: '#303538'
  on-surface: '#dfe3e6'
  on-surface-variant: '#bec8ce'
  inverse-surface: '#dfe3e6'
  inverse-on-surface: '#2c3134'
  outline: '#889298'
  outline-variant: '#3e484e'
  surface-tint: '#70d2fc'
  primary: '#70d2fc'
  on-primary: '#003546'
  primary-container: '#2e9bc3'
  on-primary-container: '#002e3d'
  inverse-primary: '#006684'
  secondary: '#a9ccdd'
  on-secondary: '#0f3442'
  secondary-container: '#2b4d5c'
  on-secondary-container: '#9bbecf'
  tertiary: '#ffb865'
  on-tertiary: '#482a00'
  tertiary-container: '#c58229'
  on-tertiary-container: '#3e2400'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#bee9ff'
  primary-fixed-dim: '#70d2fc'
  on-primary-fixed: '#001f2a'
  on-primary-fixed-variant: '#004d64'
  secondary-fixed: '#c4e8fa'
  secondary-fixed-dim: '#a9ccdd'
  on-secondary-fixed: '#001f2a'
  on-secondary-fixed-variant: '#294b5a'
  tertiary-fixed: '#ffddba'
  tertiary-fixed-dim: '#ffb865'
  on-tertiary-fixed: '#2b1700'
  on-tertiary-fixed-variant: '#663d00'
  background: '#0f1417'
  on-background: '#dfe3e6'
  surface-variant: '#303538'
typography:
  display-hero:
    fontFamily: Outfit
    fontSize: 64px
    fontWeight: '700'
    lineHeight: 72px
    letterSpacing: -0.03em
  display-hero-mobile:
    fontFamily: Outfit
    fontSize: 38px
    fontWeight: '700'
    lineHeight: 44px
    letterSpacing: -0.02em
  headline-xl:
    fontFamily: Outfit
    fontSize: 48px
    fontWeight: '600'
    lineHeight: 56px
    letterSpacing: -0.025em
  headline-xl-mobile:
    fontFamily: Outfit
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 38px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Outfit
    fontSize: 36px
    fontWeight: '600'
    lineHeight: 44px
    letterSpacing: -0.02em
  headline-lg-mobile:
    fontFamily: Outfit
    fontSize: 26px
    fontWeight: '600'
    lineHeight: 32px
    letterSpacing: -0.015em
  headline-md:
    fontFamily: Outfit
    fontSize: 24px
    fontWeight: '500'
    lineHeight: 32px
    letterSpacing: -0.01em
  title-sm:
    fontFamily: Outfit
    fontSize: 18px
    fontWeight: '500'
    lineHeight: 24px
    letterSpacing: 0em
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
    letterSpacing: -0.005em
  body-md:
    fontFamily: Inter
    fontSize: 15px
    fontWeight: '400'
    lineHeight: 24px
    letterSpacing: 0em
  body-sm:
    fontFamily: Inter
    fontSize: 13px
    fontWeight: '400'
    lineHeight: 20px
    letterSpacing: 0.01em
  label-caps:
    fontFamily: Outfit
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.12em
  metric-stat:
    fontFamily: Outfit
    fontSize: 56px
    fontWeight: '700'
    lineHeight: 60px
    letterSpacing: -0.03em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  space-2xs: 0.25rem
  space-xs: 0.5rem
  space-sm: 0.75rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2rem
  space-2xl: 3rem
  space-3xl: 4rem
  space-4xl: 6rem
  space-5xl: 8rem
  container-max: 1280px
  gutter-desktop: 2rem
  gutter-mobile: 1rem
---

## Brand & Style

This design system embodies contemporary minimalist industrialism fused with luxury architectural precision. Tailored for high-end residential renovations, structural transformations, and bespoke commercial construction, the experience projects unwavering stability, mastery of materials, and transparent execution.

The aesthetic marries deep monolithic charcoal neutrals with stark gallery whites and warm industrial blue/teal accents. It evokes quiet confidence, structural weight, and refined technical sophistication—avoiding generic builder cliches in favor of an editorial, architecturally rigorous tone. Interfaces feature razor-sharp alignment, balanced negative space, deliberate borders, and crisp tactile interactions that reassure discerning property owners and commercial stakeholders.

## Colors

The system uses a focused, high-contrast palette calibrated for an authoritative dark mode:

- **Primary Architectural Accent (`#0189B0`)**: High-impact architectural blue reserved strictly for critical call-to-actions, conversion focal points, active state highlights, and structural emphasis.
- **Surface Neutrals (`#12151A`, `#1C2128`, `#242B35`)**: Deep ironstone charcoals establishing physical depth and monolithic presence without the starkness of pure black.
- **Architectural Grays (`#E5E7EB`, `#9CA3AF`)**: Clean technical grays used for precision borders, auxiliary meta text, dimensional grid overlays, and subtle component backgrounds.
- **Pure White (`#FFFFFF`)**: Reserved for display typography, stark numerical metrics, and maximum-contrast focal elements.

Color application must remain restrained: architectural blue should occupy no more than 5% of total screen real estate to retain its conversion potency and urgent physical precision.

## Typography

The typographic hierarchy bridges high-end architectural identity with effortless technical clarity:

- **Display & Headings (Outfit)**: Geometric, confident, and sculpted. Tight negative letter spacing (`-0.02em` to `-0.03em`) lends headings a chisel-cut, contemporary European feel suited for high-budget residential transformations.
- **Body & Data (Inter)**: Clean, neutral, and legibly spaced for technical specifications, scope descriptions, and trust markers.
- **Technical Overlines & Micro-Labels**: Set in uppercase Outfit with wide tracking (`0.12em`) to echo architectural drawings, blueprint references, and phase classifications.

## Layout & Spacing

The system is constructed on an 8-point base module within a structured 12-column fixed-maximum fluid grid (max width `1280px`).

- **Desktop (1024px+)**: 12 columns with 32px gutters and 48px to 64px page margins. Major conversion blocks and portfolio showcases leverage alternating asymmetric splits (7/5 or 8/4 ratios).
- **Tablet (768px - 1023px)**: 8 columns with 24px gutters and 32px horizontal margins.
- **Mobile (320px - 767px)**: 4 columns with 16px gutters and 16px page margins. Single-column stacks for cards, with vertical pacing compressed to `space-2xl` (48px) section separations.

Layout execution emphasizes rhythm and architectural order: content containers should favor structural, visible perimeter borders rather than arbitrary floating blocks.

## Elevation & Depth

Visual hierarchy uses a tactile, low-profile architectural depth framework rather than theatrical soft drop shadows:

- **Surface Tiers**: Base floor (`#12151A`), elevated structural panels (`#1C2128`), and interactive flyouts/overlays (`#242B35`).
- **Low-Contrast Outlines**: Surfaces are separated primarily by crisp 1px borders (`rgba(229, 231, 235, 0.12)`), establishing planar delineation resembling steel drafting frames.
- **Subtle Directional Shadow**: Card hover states and primary conversion buttons use tight, controlled shadows tinted toward obsidian and architectural blue:
  - Default card: `0 1px 3px rgba(0, 0, 0, 0.35)`
  - Elevated/interactive card: `0 8px 24px rgba(0, 0, 0, 0.45), 0 0 0 1px rgba(229, 231, 235, 0.22)`
  - Primary CTA glow: `0 8px 20px rgba(1, 137, 176, 0.25)`

## Shapes

The shape system adopts a restrained **Soft (`1`)** profile. Subtle 4px (`rounded-sm` / `0.25rem`) to 8px (`rounded-md` / `0.5rem`) corner radiuses retain structural precision and industrial solidity.

Pill shapes and heavy rounded bubbles are strictly prohibited, as they dilute the technical authority and craftsmanship of high-end construction. Inputs, buttons, and media viewports must maintain an engineered, crisp silhouette.

## Components

### Buttons
- **Primary CTA**: Background `#0189B0`, text `#FFFFFF`, font Outfit SemiBold (`15px`), height 48px, horizontal padding 28px, border-radius 4px. On hover: `#016f8f` with `box-shadow: 0 6px 20px rgba(1, 137, 176, 0.28)`.
- **Secondary / Outline**: Background transparent, border 1px solid `rgba(229, 231, 235, 0.28)`, text `#FFFFFF`. On hover: background `rgba(255, 255, 255, 0.05)`, border-color `#FFFFFF`.
- **Micro-CTA / Link**: Architectural blue text with an animated 1px underline that expands from 0% to 100% width on hover.

### Cards & Project Showcases
- **Background**: `#1C2128` with a 1px border of `rgba(229, 231, 235, 0.12)` and 4px corner radius.
- **Hover State**: Border shifts to `rgba(1, 137, 176, 0.5)` with an 8px upward translation and ambient shadow.
- **Before/After Renovation Slider**: Dual-layer container with a 2px vertical divider line (`#0189B0`) and an industrial circular drag handle with left/right arrows.

### Input Fields & Estimation Forms
- **Field Container**: Height 52px, background `#12151A`, border 1px solid `rgba(229, 231, 235, 0.18)`, border-radius 4px, text `#FFFFFF`.
- **Focus State**: Border-color `#0189B0`, subtle outer ring `0 0 0 1px #0189B0`.
- **Floating Label**: Outfit font, uppercase, `11px`, letter-spacing `0.08em`, color `#9CA3AF`.

### Badges & Technical Chips
- **Status/Scope Chips**: Height 26px, padding `0 10px`, border-radius 2px. Background `rgba(229, 231, 235, 0.06)`, border 1px solid `rgba(229, 231, 235, 0.14)`, text `#E5E7EB`, label-caps styling.
- **Highlight Badge**: Background `rgba(1, 137, 176, 0.15)`, border 1px solid `#0189B0`, text `#0189B0`.

### Trust Markers & Specification Counters
- **Metric Block**: Border-left 2px solid `#0189B0`, padding-left 16px. Number rendered in Outfit Bold (`metric-stat`), caption rendered in Inter Regular (`13px`) `#9CA3AF`.