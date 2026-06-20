---
name: KGN Kinetic
colors:
  surface: '#051424'
  surface-dim: '#051424'
  surface-bright: '#2c3a4c'
  surface-container-lowest: '#010f1f'
  surface-container-low: '#0d1c2d'
  surface-container: '#122131'
  surface-container-high: '#1c2b3c'
  surface-container-highest: '#273647'
  on-surface: '#d4e4fa'
  on-surface-variant: '#bac9cc'
  inverse-surface: '#d4e4fa'
  inverse-on-surface: '#233143'
  outline: '#849396'
  outline-variant: '#3b494c'
  surface-tint: '#00daf3'
  primary: '#c3f5ff'
  on-primary: '#00363d'
  primary-container: '#00e5ff'
  on-primary-container: '#00626e'
  inverse-primary: '#006875'
  secondary: '#d7ffc5'
  on-secondary: '#053900'
  secondary-container: '#2ff801'
  on-secondary-container: '#0f6d00'
  tertiary: '#ececef'
  on-tertiary: '#2f3133'
  tertiary-container: '#d0d0d3'
  on-tertiary-container: '#57595b'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#9cf0ff'
  primary-fixed-dim: '#00daf3'
  on-primary-fixed: '#001f24'
  on-primary-fixed-variant: '#004f58'
  secondary-fixed: '#79ff5b'
  secondary-fixed-dim: '#2ae500'
  on-secondary-fixed: '#022100'
  on-secondary-fixed-variant: '#095300'
  tertiary-fixed: '#e2e2e5'
  tertiary-fixed-dim: '#c6c6c9'
  on-tertiary-fixed: '#1a1c1e'
  on-tertiary-fixed-variant: '#454749'
  background: '#051424'
  on-background: '#d4e4fa'
  surface-variant: '#273647'
typography:
  display-lg:
    fontFamily: Sora
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Sora
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Sora
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  body-lg:
    fontFamily: Hanken Grotesk
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Hanken Grotesk
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-sm:
    fontFamily: Geist
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: 0.05em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  unit: 8px
  gutter: 24px
  margin-mobile: 16px
  margin-desktop: 64px
  max-width: 1440px
---

## Brand & Style
The design system is engineered to bridge the gap between high-performance electric mobility and professional enterprise management. It targets both high-intent showroom customers and internal operators who require a reliable, high-tech interface.

The aesthetic follows a **Corporate / Modern** direction with a **Futuristic** edge. It utilizes a sophisticated "Dark Mode first" philosophy for customer-facing interfaces to highlight the luminosity of electric blue accents, while maintaining a structured, clean approach for management dashboards. The emotional response is one of trust, environmental consciousness (Eco-Green), and technological superiority. Precision is prioritized through ample whitespace, crisp typography, and subtle glassmorphism to suggest transparency and modernity.

## Colors
This palette is grounded in **Sleek Charcoal Gray** (#1A1C1E) to serve as a high-contrast foundation that feels premium and solid. 

- **Electric Blue (#00E5FF):** Used for primary actions, progress indicators, and core brand elements. It represents electricity and high-speed data.
- **Eco-Green (#39FF14):** A highly saturated, "neon-natural" green used for success states, battery indicators, and environmental impact metrics.
- **Neutral Accents:** Slate and cool grays provide hierarchy for secondary text and borders.

The default color mode is **dark** for the showroom experience to create a high-end "cockpit" feel. The enterprise dashboard may transition to a high-contrast light mode, swapping the charcoal base for a clean white/gray surface while retaining the vibrant primary and secondary accents.

## Typography
The typography system uses a tri-font strategy to balance character with technical precision.

1.  **Sora (Headlines):** A geometric sans-serif with a futuristic DNA. It is used for hero sections and large headers to establish a bold brand presence.
2.  **Hanken Grotesk (Body):** A highly legible, contemporary sans-serif for long-form content, specifications, and dashboard data.
3.  **Geist (Labels/Data):** A technical, developer-friendly font used for UI labels, table headers, and numerical values to emphasize a "measured" and accurate feel.

Text rendering should prioritize high contrast. On dark backgrounds, use pure white for headlines and 70% opacity for body text to reduce eye strain.

## Layout & Spacing
The design system utilizes a **12-column Fluid Grid** for desktop and a **4-column grid** for mobile. 

- **Rhythm:** A strict 8px baseline grid ensures vertical consistency across dashboard widgets and showroom galleries.
- **Margins:** Large 64px margins on desktop create a "boutique" feel, preventing the content from feeling cramped.
- **Components:** Dashboard cards and showroom items use 24px gutters to allow the eye to rest between technical data points.
- **Mobile:** Margins tighten to 16px to maximize the utility of limited horizontal space while maintaining a high touch-target area for buttons.

## Elevation & Depth
Depth is conveyed through **Tonal Layers** and **Glassmorphism**, avoiding traditional heavy shadows to maintain a clean, technical look.

- **Base Level:** Charcoal Gray (#1A1C1E).
- **Surface Level:** Slightly lighter gray (#25282C) with a 1px inner border of 10% white to simulate a "beveled" edge.
- **Overlays:** Navigation bars and modal windows use a 40px backdrop blur with 60% opacity backgrounds.
- **Interactive Depth:** Instead of shadows, interactive elements use a "glow" (outer blur) of the Primary Electric Blue when hovered or focused, mimicking the lighting of an EV instrument cluster.

## Shapes
The shape language is **Rounded** (0.5rem base), striking a balance between the organic "eco" feel and the structured "engineering" feel. 

- **Standard Buttons:** 0.5rem (8px) radius.
- **Cards & Containers:** 1rem (16px) radius for a modern, friendly appearance.
- **Inputs:** 0.5rem (8px) to maintain a consistent professional look.
- **Selection Indicators:** Use pill-shaped (rounded-full) geometry for toggle switches and status chips to distinguish them from structural layout elements.

## Components
- **Buttons:** Primary buttons use a solid Electric Blue background with black text for maximum punch. Secondary buttons are "ghost" style with a 1px Electric Blue border.
- **Chips:** Status chips (e.g., "In Stock," "Charging") use the Eco-Green for positive states, with a subtle low-opacity green background and solid green text.
- **Input Fields:** Dark backgrounds with a 1px stroke that glows Electric Blue on focus. Labels use the Geist font in uppercase for a "spec-sheet" look.
- **Cards:** Dashboard cards have no shadows; they use a solid background color (Surface Level) and a faint border.
- **Data Visualizations:** Charts and graphs exclusively use Electric Blue and Eco-Green against the Charcoal background to ensure the "Eco-Tech" brand is reinforced in every data point.
- **Additional Components:** "Battery Level" indicators and "Carbon Savings" calculators should be treated as high-priority custom components with animated fills.