---
name: AIRINDEX
colors:
  surface: '#101415'
  surface-dim: '#101415'
  surface-bright: '#363a3b'
  surface-container-lowest: '#0b0f10'
  surface-container-low: '#191c1e'
  surface-container: '#1d2022'
  surface-container-high: '#272a2c'
  surface-container-highest: '#323537'
  on-surface: '#e0e3e5'
  on-surface-variant: '#c4c5d5'
  inverse-surface: '#e0e3e5'
  inverse-on-surface: '#2d3133'
  outline: '#8e909f'
  outline-variant: '#444653'
  surface-tint: '#b8c4ff'
  primary: '#b8c4ff'
  on-primary: '#002584'
  primary-container: '#1e40af'
  on-primary-container: '#a8b8ff'
  inverse-primary: '#3755c3'
  secondary: '#ddfcff'
  on-secondary: '#00363a'
  secondary-container: '#00f1fe'
  on-secondary-container: '#006a70'
  tertiary: '#bfc6dd'
  on-tertiary: '#293042'
  tertiary-container: '#444b5e'
  on-tertiary-container: '#b5bbd2'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#dde1ff'
  primary-fixed-dim: '#b8c4ff'
  on-primary-fixed: '#001453'
  on-primary-fixed-variant: '#173bab'
  secondary-fixed: '#74f5ff'
  secondary-fixed-dim: '#00dbe7'
  on-secondary-fixed: '#002022'
  on-secondary-fixed-variant: '#004f54'
  tertiary-fixed: '#dce2fa'
  tertiary-fixed-dim: '#bfc6dd'
  on-tertiary-fixed: '#141b2c'
  on-tertiary-fixed-variant: '#40465a'
  background: '#101415'
  on-background: '#e0e3e5'
  surface-variant: '#323537'
typography:
  display-lg:
    fontFamily: Inter
    fontSize: 48px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Inter
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.2'
  headline-md:
    fontFamily: Inter
    fontSize: 24px
    fontWeight: '600'
    lineHeight: '1.3'
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-sm-uppercase:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '700'
    lineHeight: '1.4'
    letterSpacing: 0.08em
  data-mono:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '500'
    lineHeight: '1.0'
    letterSpacing: -0.01em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  unit: 8px
  xs: 0.5rem
  sm: 1rem
  md: 1.5rem
  lg: 2rem
  xl: 3rem
  gutter: 1.5rem
  margin-mobile: 1rem
  margin-desktop: 2.5rem
---

## Brand & Style

The design system is engineered for **AIRINDEX**, a premium aviation-themed economic intelligence platform. The visual narrative balances the precision of an aerospace cockpit with the authoritative weight of a high-stakes financial terminal. It targets institutional investors, government agencies, and aviation stakeholders who require absolute clarity and real-time reliability.

The aesthetic utilizes a refined **Glassmorphism** approach, where information is layered on semi-transparent surfaces to create a sense of depth without sacrificing structural integrity. The tone is serious and analytical, evoking the feeling of a sophisticated mission control center focused on the Indian airfare market.

## Colors

The palette is anchored in a deep, nocturnal spectrum. The **Background Base (#050810)** provides a void-like depth, allowing the **Surface Containers (#0D1425)** to emerge as distinct structural zones. 

**Aviation Blue (#1E40AF)** serves as the primary brand signal, used for stable interactive states and structural highlights. **Cyan (#00F2FF)** is the "Active Intelligence" accent, reserved for real-time data fluctuations, primary calls to action, and critical indicators. Functional neutrals range from pure white for high-readability text to muted slate for secondary metadata.

## Typography

This design system utilizes **Inter** exclusively to maintain a utilitarian, highly legible environment. The typographic hierarchy is strictly organized to prioritize data scanning.

- **Data Points:** Specific data metrics utilize `label-sm-uppercase` to create a rhythmic "instrument panel" look.
- **Headlines:** Use tight letter-spacing and semi-bold weights to convey authority.
- **Body:** Open line-heights ensure readability against the dark background.
- **Emphasis:** Cyan tinting is applied to typography only when it represents live data or an active navigation state.

## Layout & Spacing

The layout is governed by a strict **8px grid system**, ensuring mathematical precision across all viewport sizes. 

- **Desktop:** A 12-column fluid grid with 24px gutters. Content is typically housed in "modules" that span 3, 4, or 6 columns.
- **Data Density:** In analytical views, the spacing tightens to a 4px internal rhythm to maximize the information density without clutter.
- **Margins:** Large outer margins (40px+) on desktop focus the user's attention on the central data intelligence hub, while mobile transitions to a 16px margin to preserve horizontal space for charts.

## Elevation & Depth

Elevation is communicated through **Tonal Layering** and **Glassmorphism** rather than traditional drop shadows.

1.  **Level 0 (Floor):** The base background (#050810).
2.  **Level 1 (Cards):** Surface containers (#0D1425) with a subtle backdrop blur (8px) and a 1px border (#1E293B).
3.  **Level 2 (Modals/Popovers):** Higher opacity surfaces with a secondary glow effect—a faint 20px cyan outer blur—simulating light emission from a screen.

Interaction is signaled by increasing border brightness or adding a soft cyan inner-glow to the active element.

## Shapes

The shape language is precise and "Soft" (Roundedness: 1). This ensures that while the interface feels modern, it retains the rigid structure expected of a financial tool.

- **Standard Elements:** 4px (0.25rem) radius for buttons and input fields.
- **Containers:** 8px (0.5rem) radius for data cards and main navigation panels.
- **Accents:** 12px (0.75rem) for large modals or feature highlights.

Sharp corners are avoided to prevent an overly "aggressive" look, but radii never reach pill-shapes to maintain a professional, desktop-first architecture.

## Components

### Buttons
- **Primary:** Solid Aviation Blue (#1E40AF) with white text. On hover, a Cyan (#00F2FF) outer glow appears.
- **Secondary:** Transparent background with a 1px Cyan border and Cyan text. 
- **Ghost:** Minimal text buttons with `label-sm-uppercase` styling for utility actions.

### Data Cards
Cards are the core of the system. They feature a 1px border (#1E293B) and use `label-sm-uppercase` for the title. Values are displayed in high-contrast white.

### Input Fields
Darker than the surface (#050810) to create an inset look. Focus state is indicated by a 1px Cyan border and a subtle internal Cyan tint.

### Data Visualizations
Charts utilize Cyan (#00F2FF) as the primary trend line. Comparative data uses Aviation Blue. Grid lines in charts should be kept at 10% opacity white to remain unobtrusive.

### Chips/Indicators
Used for flight status or market volatility. These are small, semi-transparent capsules with colored text (Cyan for positive, Aviation Blue for neutral, and a functional Red for negative trends).