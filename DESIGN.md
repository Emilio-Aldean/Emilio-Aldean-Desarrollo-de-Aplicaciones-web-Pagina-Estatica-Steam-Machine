---
name: Aether Dark
colors:
  surface: '#131314'
  surface-dim: '#131314'
  surface-bright: '#3a3939'
  surface-container-lowest: '#0e0e0f'
  surface-container-low: '#1c1b1c'
  surface-container: '#201f20'
  surface-container-high: '#2a2a2a'
  surface-container-highest: '#353435'
  on-surface: '#e5e2e2'
  on-surface-variant: '#c6c6cb'
  inverse-surface: '#e5e2e2'
  inverse-on-surface: '#313031'
  outline: '#909095'
  outline-variant: '#45474b'
  surface-tint: '#c4c6d0'
  primary: '#c4c6d0'
  on-primary: '#2d3038'
  primary-container: '#171a21'
  on-primary-container: '#80828b'
  inverse-primary: '#5c5e67'
  secondary: '#bac7dd'
  on-secondary: '#243142'
  secondary-container: '#3d4a5b'
  on-secondary-container: '#acb9ce'
  tertiary: '#d2c4b3'
  on-tertiary: '#372f23'
  tertiary-container: '#20190e'
  on-tertiary-container: '#8d8171'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#e0e2ec'
  primary-fixed-dim: '#c4c6d0'
  on-primary-fixed: '#191c23'
  on-primary-fixed-variant: '#44474f'
  secondary-fixed: '#d6e3f9'
  secondary-fixed-dim: '#bac7dd'
  on-secondary-fixed: '#0f1c2c'
  on-secondary-fixed-variant: '#3b4859'
  tertiary-fixed: '#efe0ce'
  tertiary-fixed-dim: '#d2c4b3'
  on-tertiary-fixed: '#221a0f'
  on-tertiary-fixed-variant: '#4f4538'
  background: '#131314'
  on-background: '#e5e2e2'
  surface-variant: '#353435'
typography:
  display-lg:
    fontFamily: Inter
    fontSize: 48px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  headline-xl:
    fontFamily: Inter
    fontSize: 32px
    fontWeight: '700'
    lineHeight: '1.2'
    letterSpacing: -0.01em
  headline-lg:
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
  label-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '500'
    lineHeight: '1.4'
    letterSpacing: 0.01em
  label-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '600'
    lineHeight: '1.2'
    letterSpacing: 0.05em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  base: 4px
  xs: 8px
  sm: 16px
  md: 24px
  lg: 40px
  xl: 64px
  gutter: 20px
  margin: 32px
---

## Brand & Style

This design system is engineered for high-performance gaming environments, prioritizing immersion through a tech-forward, cinematic aesthetic. The brand personality is authoritative yet approachable, evoking the feeling of a premium digital cockpit. 

The style utilizes a sophisticated blend of **Modern Minimalism** and **Glassmorphism**. Depth is achieved not through heavy shadows, but through layered semi-transparent surfaces and subtle linear gradients that mimic the refraction of light on high-end hardware. The user interface should feel like an integrated part of the hardware experience—responsive, sleek, and focused on content discovery.

## Colors

The palette is anchored in a dual-tone dark foundation. The primary background uses the deep navy (#171a21) for absolute stability, while the slate black (#1b2838) is reserved for container surfaces and structural elements to provide subtle contrast.

Vibrant electric blue (#66c0f4) serves as the primary action color, used sparingly for CTAs, focus states, and progress indicators to ensure high visibility without causing eye strain. For text, pure white is reserved for high-level headings and critical information, while a light blue-gray (#c7d5e0) provides a softer, high-readability experience for long-form descriptions and secondary labels.

## Typography

This design system utilizes **Inter** for its exceptional readability on high-resolution displays and its neutral, systematic character. The typographic hierarchy is intentionally tight, using weight and color rather than drastic size changes to denote importance.

Headings should always be rendered in white (#ffffff) to punch through the dark background. Body text uses the blue-gray (#c7d5e0) at a medium line-height to reduce "haloing" effects common in dark mode environments. Label styles incorporate slight letter spacing and occasional uppercase transformations to create a technical, "data-rich" feel suitable for library management and settings menus.

## Layout & Spacing

The layout philosophy follows a **Fixed-Fluid Hybrid Grid**. Main navigation and content hubs conform to a 12-column grid with a maximum width of 1600px to ensure accessibility on large 4K monitors and TVs. 

Spacing is governed by a 4px baseline, but primary rhythmic movements occur in increments of 8px (sm) and 24px (md). Margins are generous (32px+) to provide "breathing room" for large game keyart, preventing the interface from feeling cluttered. Gutters are kept tight at 20px to maintain a cohesive, "tiled" look across content galleries.

## Elevation & Depth

In this design system, depth is communicated through **Tonal Layering** and **Glassmorphism** rather than traditional drop shadows.

- **Level 0 (Base):** Deep navy (#171a21) for the main application canvas.
- **Level 1 (Containers):** Slate black (#1b2838) with a 1px inner border of 5% white to define edges.
- **Level 2 (Modals/Overlays):** Semi-transparent slate black (85% opacity) with a 20px backdrop-blur and a subtle linear gradient (Top-Left: 10% white to Bottom-Right: 0% white).
- **Level 3 (Interactive):** Elements that are focused or active receive a soft outer glow using the electric blue accent color (#66c0f4) at 20% opacity, simulating a "lit" hardware state.

## Shapes

The design system adopts a **Soft** shape language. A standard 0.25rem (4px) radius is applied to buttons and small input fields to maintain a technical, precise feel. Larger containers like game cards or modal windows use a 0.5rem (8px) radius. This conservative rounding ensures that the UI feels modern and premium without leaning into the overly friendly or organic aesthetic found in mobile-first social apps.

## Components

### Buttons & Actions
Primary CTAs use a solid electric blue (#66c0f4) with bold navy text. Secondary buttons utilize a "Ghost" style: transparent backgrounds with a 1px border in #c7d5e0, transitioning to a light fill on hover.

### Game Cards
Cards are the primary content vehicle. They feature a 1px internal border and use subtle scale transforms (1.02x) on hover. Information overlays on cards should use a bottom-to-top black gradient to ensure text readability over game art.

### Input Fields
Inputs are recessed, using the primary navy color as a fill with a slate black border. On focus, the border transitions to electric blue with a subtle outer glow.

### Chips & Tags
Used for categories (e.g., "RPG", "Multiplayer"), these are small, low-contrast pills with a dark slate background and blue-gray text.

### Navigation Rails
Side navigation should use semi-transparent backgrounds and high-contrast icons. Active states are indicated by a vertical electric blue "light bar" on the leading edge of the menu item.