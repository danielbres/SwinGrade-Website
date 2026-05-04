---
name: Signal Intelligence
colors:
  surface: '#0d1513'
  surface-dim: '#0d1513'
  surface-bright: '#333b38'
  surface-container-lowest: '#08100e'
  surface-container-low: '#161d1b'
  surface-container: '#1a211f'
  surface-container-high: '#242c29'
  surface-container-highest: '#2f3634'
  on-surface: '#dce4e0'
  on-surface-variant: '#bbcac5'
  inverse-surface: '#dce4e0'
  inverse-on-surface: '#2a3230'
  outline: '#859490'
  outline-variant: '#3c4a46'
  surface-tint: '#41dcc8'
  primary: '#46dfca'
  on-primary: '#003731'
  primary-container: '#0bc3af'
  on-primary-container: '#004a42'
  inverse-primary: '#006b5f'
  secondary: '#9ed1c6'
  on-secondary: '#003731'
  secondary-container: '#1b4f47'
  on-secondary-container: '#8cbfb5'
  tertiary: '#c9c9c9'
  on-tertiary: '#2f3131'
  tertiary-container: '#adaeae'
  on-tertiary-container: '#404242'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#66f9e3'
  primary-fixed-dim: '#41dcc8'
  on-primary-fixed: '#00201c'
  on-primary-fixed-variant: '#005047'
  secondary-fixed: '#b9ede2'
  secondary-fixed-dim: '#9ed1c6'
  on-secondary-fixed: '#00201c'
  on-secondary-fixed-variant: '#1b4f47'
  tertiary-fixed: '#e2e2e2'
  tertiary-fixed-dim: '#c6c6c7'
  on-tertiary-fixed: '#1a1c1c'
  on-tertiary-fixed-variant: '#454747'
  background: '#0d1513'
  on-background: '#dce4e0'
  surface-variant: '#2f3634'
typography:
  display-lg:
    fontFamily: Inter
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.2'
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Inter
    fontSize: 24px
    fontWeight: '500'
    lineHeight: '1.3'
    letterSpacing: -0.01em
  title-sm:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '500'
    lineHeight: '1.4'
  body-main:
    fontFamily: Inter
    fontSize: 15px
    fontWeight: '400'
    lineHeight: '1.6'
  body-compact:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: '1.5'
  label-caps:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '600'
    lineHeight: '1'
    letterSpacing: 0.05em
  data-mono:
    fontFamily: Inter
    fontSize: 13px
    fontWeight: '500'
    lineHeight: '1'
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  unit: 4px
  xs: 4px
  sm: 8px
  md: 16px
  lg: 24px
  xl: 40px
  container-margin: 24px
  gutter: 16px
---

## Brand & Style
The design system is engineered for high-stakes decision-making. The visual narrative centers on **Professionalism** and **Precision**, moving away from retail trading hype toward an institutional, data-first aesthetic. 

The style is a hybrid of **Minimalism** and **Glassmorphism**. It utilizes a "Dark Cockpit" approach—where the interface recedes into the background to allow critical data points and trading signals to emerge with absolute clarity. The transition to a teal-based palette moves the brand toward a more technical, "cyber-medical" precision feel. Depth is created through translucent layers and hair-line strokes rather than heavy shadows, ensuring the UI feels lightweight and modern. The emotional response should be one of focused calm, providing the trader with a sense of control and technological superiority.

## Colors
This design system utilizes a sophisticated dark-palette hierarchy designed to reduce eye strain during long trading sessions. 

- **Primary Canvas:** The muted neutral sage (#717976) and its derived dark variants act as the foundation, providing a softer, more organic dark mode than pure black or blue-slates.
- **Action Teal:** The vibrant teal (#0bc3af) is used for primary interface actions, active states, and premium feature highlights.
- **Signal Semantics:** Secondary Muted Teal (#4f8077) provides supporting context, while Tertiary White (#ffffff) is reserved for high-priority highlights, neutral price levels, or maximum-contrast signals.
- **Neutral Scale:** Grays are tinted with a slight sage/green hue to maintain a cohesive temperature, ensuring text remains legible without the harshness of high-contrast white-on-black.

## Typography
The typography strategy prioritizes **Functional Readability**. Inter is selected for its exceptional performance in data-heavy environments. 

For numerical data, the system utilizes "Tabular Numbers" (tnum) to ensure that columns of prices and percentages align perfectly for vertical scanning. High-contrast hierarchy is maintained by using Uppercase Labels for metadata and slightly increased line-heights for body text to prevent information density from becoming overwhelming.

## Layout & Spacing
The layout follows a **Rigid Grid** philosophy to mirror the precision of financial charts. 

A 4px baseline grid ensures consistent vertical rhythm. Components and modules are organized within a 12-column fluid system for dashboards, while the indicator panels themselves use a "Compact Fixed" layout to maximize screen real estate for the price action. Content density should be high but organized, utilizing generous margins between distinct functional groups to allow the eye to rest.

## Elevation & Depth
Depth is expressed through **Z-axis Layering** rather than traditional drop shadows. 

1.  **Level 0 (Base):** Deep Muted Sage (#1A1D1C) for the global background.
2.  **Level 1 (Surface):** Darker container fills with a 1px solid border at 10% white opacity.
3.  **Level 2 (Overlay/Glass):** Translucent background (alpha 0.6) with a 20px backdrop blur and a more prominent inner glow to simulate glass.

Shadows, if used, are extremely subtle (0px 4px 20px rgba(0,0,0, 0.4)) and reserved only for floating modals or context menus that sit atop the chart area.

## Shapes
To maintain a "Serious and Modern" tone, the design system employs **Soft edges** (4px - 8px radius). 

This subtle rounding removes the clinical harshness of sharp corners while remaining significantly more professional and structured than "bubbly" or pill-shaped consumer apps. Buttons and input fields should strictly adhere to the 4px (sm) or 8px (md) standard to ensure a unified architectural feel across the indicator's settings and dashboard components.

## Components
- **Primary Buttons:** Solid Teal (#0BC3AF) with dark text. High-contrast, 4px border radius, no gradient.
- **Signal Chips:** Semi-transparent backgrounds of Secondary Teal or White (15% opacity) with a 1px solid border of the same color at 40% opacity. Text remains the bright accent color for legibility.
- **Data Rows:** Alternating background fills (Zebra striping) using subtle luminance differences to guide the eye across horizontal data points.
- **Input Fields:** Deep muted background with a 1px border. On focus, the border transitions to Teal with a subtle outer glow.
- **Status Indicators:** Small, circular dots. Pulsing animations are reserved only for "Live" connection states to avoid distracting the trader.
- **Charts:** Professional-grade candle sticks. The palette uses Teal (#0BC3AF) for bullish moves and White (#FFFFFF) for neutral price discovery or breakout volatility signals.