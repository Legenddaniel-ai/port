---
name: Disciplined Monolith
colors:
  surface: '#041521'
  surface-dim: '#041521'
  surface-bright: '#2b3b48'
  surface-container-lowest: '#01101b'
  surface-container-low: '#0c1d29'
  surface-container: '#11212e'
  surface-container-high: '#1b2c38'
  surface-container-highest: '#263644'
  on-surface: '#d3e5f6'
  on-surface-variant: '#d2c4b8'
  inverse-surface: '#d3e5f6'
  inverse-on-surface: '#22323f'
  outline: '#9b8f84'
  outline-variant: '#4e453c'
  surface-tint: '#e5c099'
  primary: '#fcd5ac'
  on-primary: '#432c0f'
  primary-container: '#deb992'
  on-primary-container: '#63492a'
  inverse-primary: '#755939'
  secondary: '#b4c9dc'
  on-secondary: '#1e3341'
  secondary-container: '#354959'
  on-secondary-container: '#a2b8ca'
  tertiary: '#7cede4'
  on-tertiary: '#003734'
  tertiary-container: '#5ed1c8'
  on-tertiary-container: '#005753'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#ffddba'
  primary-fixed-dim: '#e5c099'
  on-primary-fixed: '#2b1701'
  on-primary-fixed-variant: '#5c4224'
  secondary-fixed: '#d0e5f9'
  secondary-fixed-dim: '#b4c9dc'
  on-secondary-fixed: '#071d2c'
  on-secondary-fixed-variant: '#354959'
  tertiary-fixed: '#84f5ec'
  tertiary-fixed-dim: '#66d8cf'
  on-tertiary-fixed: '#00201e'
  on-tertiary-fixed-variant: '#00504b'
  background: '#041521'
  on-background: '#d3e5f6'
  surface-variant: '#263644'
typography:
  display-hero:
    fontFamily: Syne
    fontSize: 4.5rem
    fontWeight: '700'
    lineHeight: 5rem
    letterSpacing: -0.03em
  display-hero-mobile:
    fontFamily: Syne
    fontSize: 2.75rem
    fontWeight: '700'
    lineHeight: 3.25rem
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Syne
    fontSize: 3rem
    fontWeight: '600'
    lineHeight: 3.5rem
    letterSpacing: -0.02em
  headline-lg-mobile:
    fontFamily: Syne
    fontSize: 2rem
    fontWeight: '600'
    lineHeight: 2.5rem
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Syne
    fontSize: 2rem
    fontWeight: '600'
    lineHeight: 2.5rem
    letterSpacing: -0.01em
  headline-sm:
    fontFamily: Syne
    fontSize: 1.5rem
    fontWeight: '500'
    lineHeight: 2rem
    letterSpacing: '0'
  title-editorial:
    fontFamily: Inter
    fontSize: 1.25rem
    fontWeight: '500'
    lineHeight: 1.75rem
    letterSpacing: -0.01em
  body-lg:
    fontFamily: Inter
    fontSize: 1.125rem
    fontWeight: '400'
    lineHeight: 1.875rem
    letterSpacing: '0'
  body-md:
    fontFamily: Inter
    fontSize: 0.9375rem
    fontWeight: '400'
    lineHeight: 1.625rem
    letterSpacing: '0'
  label-code:
    fontFamily: JetBrains Mono
    fontSize: 0.8125rem
    fontWeight: '500'
    lineHeight: 1.25rem
    letterSpacing: 0.04em
  label-index:
    fontFamily: JetBrains Mono
    fontSize: 0.75rem
    fontWeight: '600'
    lineHeight: 1rem
    letterSpacing: 0.12em
  caption:
    fontFamily: Inter
    fontSize: 0.75rem
    fontWeight: '400'
    lineHeight: 1.125rem
    letterSpacing: 0.01em
spacing:
  gutter: 1.5rem
  gutter-desktop: 2.5rem
  margin: 1.5rem
  margin-desktop: 4rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
  space-2xl: 4rem
  space-3xl: 6rem
---

## Brand & Style
The design system articulates an editorial, precision-engineered aesthetic tailored for a senior technologist. Rooted in disciplined minimalism, the interface evokes the intellectual gravitas of an architectural monograph paired with the rigorous technical precision of advanced systems engineering. 

The visual identity rejects gratuitous decoration, relying instead on deliberate negative space, razor-sharp hairline dividers, disciplined typographical cadence, and structural grid alignment. The emotional tone is authoritative, understated, focused, and profoundly competent—communicating high-level engineering craftsmanship through bespoke restraint rather than visual noise.

## Colors
The color palette establishes an atmospheric, high-contrast dark environment inspired by precision drafting on midnight parchment.

- **Neutral Canvas (`#051622`)**: The foundational deep navy void. It provides an immersive, low-strain backdrop that gives immense presence to foreground typography and structural frames.
- **Primary Accent (`#deb992`)**: Muted champagne / warm beige. Reserved strictly for key focal points, active states, indices, callouts, and tactile highlights. It brings human warmth and editorial luxury to the digital canvas.
- **Secondary Neutral (`#8ba0b2`)**: Muted slate gray. Dedicated to secondary prose, explanatory notes, captions, and structural hairline elements.
- **Tertiary Accent (`#1ba098`)**: Deep muted teal. Used sparingly for telemetry signals, live deployment indicators, commit hashes, or active code statuses.
- **Surface Elevation Variables**:
  - `surface-base`: `#051622`
  - `surface-elevated`: `#092032`
  - `surface-highlight`: `#0e2a42`
  - `border-hairline`: `rgba(222, 185, 146, 0.15)`
  - `text-primary`: `#f4f6f8`
  - `text-secondary`: `#8ba0b2`
  - `text-accent`: `#deb992`

## Typography
The typographical hierarchy balances structural modernism with mechanical exactitude. 

1. **Display & Headings (Syne)**: Distinctive, geometric, and high-impact. Used for oversized hero statements and section titles. Rendered in crisp off-white (`#f4f6f8`), tightly tracked to produce an architectural presence.
2. **Body & Reading Flow (Inter)**: Rational, legible, and unadorned. Set with generous line-height to provide effortless readability across case studies, architectural deep-dives, and technical essays.
3. **Metadata, Metrics & Code (JetBrains Mono)**: Mechanical, monospaced, and authoritative. Applied to technical specifications, index numbering (e.g., `[01/06]`), timestamps, terminal outputs, and structural labels. Always tracked outwards for maximum clarity.

## Layout & Spacing
The layout employs an asymmetric, fluid 12-column architectural grid with generous breathing room and explicit grid boundaries.

- **Horizontal Alignment**: Section containers align strictly to vertical hairline guide rules. Outer margins transition dynamically from `1.5rem` on mobile viewports up to `4rem` (or max-width container caps of `1280px` / `1440px`) on ultra-wide displays.
- **Rhythm & Cadence**:
  - Compact data density within technical parameter blocks (`space-xs` to `space-sm`).
  - Standard component interior padding (`space-md` to `space-lg`).
  - Major section demarcations leverage dramatic negative space (`space-2xl` to `space-3xl`) to establish cadence without graphic clutter.
- **Breakpoints**:
  - `Mobile` (< 768px): Single-column stack, nested borders collapse into simple vertical stacks with `1.5rem` gutters.
  - `Tablet` (768px – 1024px): 6-column hybrid layout, metadata runs in parallel side-rails.
  - `Desktop` (> 1024px): Full 12-column layout with fixed-width engineering sidebars and expansive narrative panels.

## Elevation & Depth
Depth is articulated through planar layering and disciplined hairlines, explicitly rejecting skeuomorphic drop shadows.

- **Hairline Framing**: Structural surfaces are demarcated using `1px` solid borders set to `rgba(222, 185, 146, 0.15)`. Active or focused states step up to `rgba(222, 185, 146, 0.5)`.
- **Tonal Stepping**:
  - Canvas floor: `#051622`
  - Structural cards / Code panels: `#092032`
  - Floating overlays / Flyouts / Command palettes: `#0e2a42`
- **Ambient Focus Glows**: Shadows are replaced by ultra-subtle optical highlights. High-priority elements use a faint champagne ambient glow: `box-shadow: 0 0 24px -6px rgba(222, 185, 146, 0.08)`.
- **Dividers & Axis Rules**: Horizontal and vertical hairline dividers run across entire viewports to ground content in a drafting table motif.

## Shapes
The shape language is strictly sharp (`roundedness: 0`). 

Corners are unapologetically orthogonal (0px radius) across all interactive cards, buttons, badges, code snippets, and modal dialogs. This hard-edged geometric treatment reinforces the feeling of raw blueprint drafting, monolithic brutalist precision, and unyielding code execution. Micro-details, such as active selection markers, use square indicator blocks (`4px × 4px`) instead of circular dots.

## Components

### Buttons & Interactive Links
- **Primary Action**: Sharp rectangular container. Background: `#deb992`; text: `#051622` (`label-code`, uppercase, bold). Border: `1px solid #deb992`. Hover: `#f4f6f8` background, `#051622` text.
- **Secondary / Ghost Action**: Transparent background with `1px solid rgba(222, 185, 146, 0.3)`. Text: `#deb992`. Hover: Border shifts to `#deb992`, background tint of `rgba(222, 185, 146, 0.06)`.
- **Inline Text Link**: Underlined with a `1px` offset border in `rgba(222, 185, 146, 0.4)`. Transitions to `100%` opacity on hover with an arrow glyph (`→`).

### Badges, Chips & Meta Tags
- Monospace typographic tags (`JetBrains Mono`, `0.75rem`).
- Framed in `1px solid rgba(222, 185, 146, 0.15)`. Background: `rgba(9, 32, 50, 0.6)`. Text: `#8ba0b2`.
- Category index tags prepend section names with zero-padded numerals (e.g., `SYS.01 // DISTRIBUTED ARCHITECTURE`).

### Cards & Project Showcases
- Surface set to `#092032` wrapped in a crisp `1px solid rgba(222, 185, 146, 0.15)`.
- Sharp grid divisions: internal sections separated by explicit horizontal/vertical hairline cuts rather than whitespace alone.
- Hover state: Border shifts to `rgba(222, 185, 146, 0.4)`, slight internal tint transition, and cursor reveals an architectural crosshair.

### Form Inputs & Terminal Command Fields
- Inset field with `#051622` background and `1px solid rgba(222, 185, 146, 0.2)`.
- Text: `#f4f6f8` in `JetBrains Mono`. Placeholder: `#8ba0b2` with opacity `0.6`.
- Focus state: Border illuminates to `1px solid #deb992` with an ambient glow (`box-shadow: 0 0 12px rgba(222, 185, 146, 0.1)`). No default browser outlines.

### Lists & Technical Indexes
- Projects, experience timelines, and essays are rendered as tabular row items.
- Top and bottom dividers: `1px solid rgba(222, 185, 146, 0.12)`.
- Columns structured into: Index (`[01]`), Title/Role, Technology Stack / Artifact, and Year.
- Hovering an entire row triggers a subtle champagne text highlight and reveals deep metadata.

### System Telemetry & Status Badges
- Compact rectangular indicator. Live state signaled by a sharp `6px × 6px` square in `#1ba098` with a subtle static ping outline (`1px solid rgba(27, 160, 152, 0.4)`).