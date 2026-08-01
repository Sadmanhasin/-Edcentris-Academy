---
name: Academic Excellence System
colors:
  surface: '#f7f9fb'
  surface-dim: '#d8dadc'
  surface-bright: '#f7f9fb'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f2f4f6'
  surface-container: '#eceef0'
  surface-container-high: '#e6e8ea'
  surface-container-highest: '#e0e3e5'
  on-surface: '#191c1e'
  on-surface-variant: '#44474e'
  inverse-surface: '#2d3133'
  inverse-on-surface: '#eff1f3'
  outline: '#75777f'
  outline-variant: '#c5c6cf'
  surface-tint: '#4e5e81'
  primary: '#000002'
  on-primary: '#ffffff'
  primary-container: '#081b3a'
  on-primary-container: '#7484a9'
  inverse-primary: '#b6c6ee'
  secondary: '#006b5a'
  on-secondary: '#ffffff'
  secondary-container: '#6bf6d7'
  on-secondary-container: '#00705e'
  tertiary: '#000000'
  on-tertiary: '#ffffff'
  tertiary-container: '#00210c'
  on-tertiary-container: '#08984e'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d8e2ff'
  primary-fixed-dim: '#b6c6ee'
  on-primary-fixed: '#081b3a'
  on-primary-fixed-variant: '#364768'
  secondary-fixed: '#6ef9da'
  secondary-fixed-dim: '#4ddcbe'
  on-secondary-fixed: '#00201a'
  on-secondary-fixed-variant: '#005143'
  tertiary-fixed: '#83fba5'
  tertiary-fixed-dim: '#66dd8b'
  on-tertiary-fixed: '#00210c'
  on-tertiary-fixed-variant: '#005227'
  background: '#f7f9fb'
  on-background: '#191c1e'
  surface-variant: '#e0e3e5'
typography:
  display-lg:
    fontFamily: Playfair Display
    fontSize: 64px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Playfair Display
    fontSize: 48px
    fontWeight: '700'
    lineHeight: '1.2'
    letterSpacing: -0.01em
  headline-lg-mobile:
    fontFamily: Playfair Display
    fontSize: 32px
    fontWeight: '700'
    lineHeight: '1.2'
  headline-md:
    fontFamily: Playfair Display
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.3'
  body-lg:
    fontFamily: Manrope
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Manrope
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-md:
    fontFamily: Manrope
    fontSize: 14px
    fontWeight: '600'
    lineHeight: '1.4'
    letterSpacing: 0.05em
  caption:
    fontFamily: Manrope
    fontSize: 12px
    fontWeight: '500'
    lineHeight: '1.4'
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  unit: 8px
  container-max: 1280px
  gutter: 24px
  margin-mobile: 20px
  margin-desktop: 64px
  section-gap: 120px
---

## Brand & Style

The brand personality is **Elite, Insightful, and Transformative**. It targets high-achieving students and families navigating the competitive landscape of Ivy League and top-tier U.S. college admissions. The UI must evoke a sense of quiet confidence, scholarly authority, and the polished precision of an editorial publication.

The design style is a blend of **Minimalism and Modern Editorial**. It leverages the structural clarity of a "Bento-grid" layout—inspired by Stripe and Linear—while incorporating the premium, tactile softness of Apple’s interface design. This is achieved through generous whitespace, high-contrast typography, and subtle glassmorphic overlays that signify depth without clutter. The aesthetic is "New Ivy"—honoring tradition through color and serif type, while embracing the future through sleek, tech-forward interaction patterns.

## Colors

The palette is anchored by **Deep Navy (#081B3A)**, serving as the foundation for text and primary branding to establish trust and institutional permanence. 

*   **Primary Accent:** Teal (#27C3A6), sampled from the brand identity, is used for primary actions and focused highlights.
*   **Secondary Accent:** Soft Emerald (#50C878) represents growth and success, used sparingly for positive status indicators and success states.
*   **Backgrounds:** The interface defaults to Pure White (#FFFFFF) to maximize "breathing room." Subtle Light Gray (#F8FAFC) is used to differentiate content sections and create the base for containerized layouts.
*   **Semantic Colors:** Success (Emerald), Error (Soft Red), and Warning (Amber) should maintain a muted, professional saturation level to avoid disrupting the premium feel.

## Typography

This design system uses a high-contrast typographic pairing to balance heritage with modernity.

*   **Headlines:** **Playfair Display** provides a sophisticated, editorial character. Use tight line heights and slight negative letter spacing for large display text to create a high-end, "magazine" feel.
*   **Body & Labels:** **Manrope** is used for its exceptional legibility and neutral, geometric structure. It ensures that dense information—such as admissions requirements or application timelines—remains easy to digest.
*   **Scaling:** On mobile, reduce display sizes by roughly 30-40% while maintaining the serif style to preserve brand identity across devices.

## Layout & Spacing

The layout follows a **Fixed Grid** philosophy for desktop to maintain editorial control over line lengths, transitioning to a fluid model for tablet and mobile.

*   **Bento-Grid Pattern:** Use a 12-column grid. Components should be grouped into cards of varying sizes (spanning 4, 6, or 8 columns) to create a structured yet dynamic information hierarchy.
*   **Whitespace:** Prioritize "oversized" vertical spacing between sections (120px+) to signal premium positioning.
*   **Rhythm:** All spacing is based on an 8px baseline. Use larger padding within cards (min 32px) to prevent content from feeling cramped.

## Elevation & Depth

Depth is achieved through a combination of **Tonal Layering** and **Ambient Shadows**.

1.  **Surfaces:** Use #F8FAFC as the base surface. Cards and primary containers use Pure White (#FFFFFF).
2.  **Shadows:** Shadows must be extremely soft and diffused. Use a multi-layered shadow approach (e.g., `0 10px 40px rgba(8, 27, 58, 0.04)`) to create a natural, "floating" effect.
3.  **Glassmorphism:** For navigation bars and overlay modals, use a backdrop filter (blur: 20px) with a 70% opaque white fill. This maintains a sense of context and modern sophistication.
4.  **Hover States:** When hovering over interactive cards, increase the shadow spread and slightly shift the element Y-axis (-4px) to provide tactile feedback.

## Shapes

The system uses a **Rounded** shape language to soften the serious nature of the Deep Navy color palette, making the academy feel approachable.

*   **Standard Radius:** 16px (1rem) for secondary buttons and small containers.
*   **Large Radius:** 24px (1.5rem) for primary cards and bento-grid sections.
*   **Full Radius:** Used exclusively for tags, chips, and pill-shaped primary CTA buttons to create a distinctive, friendly interaction point.

## Components

### Buttons
*   **Primary:** Pill-shaped, Deep Navy background, White text. High-contrast and authoritative.
*   **Secondary:** Pill-shaped, Transparent with a 1px Navy border or Teal text. 
*   **Transitions:** Use smooth 300ms cubic-bezier transitions for background color and shadow shifts.

### Cards
*   White background, 24px corner radius, and subtle ambient shadows. 
*   Inner padding should be generous (32px to 48px).
*   For "Success Stories," incorporate a subtle Soft Emerald gradient border (1px).

### Input Fields
*   Minimalist design with a focus on typography. 
*   Use a light #F1F5F9 background and 12px corner radius. 
*   Focus state: 1px Navy border with a soft Teal outer glow.

### Chips & Tags
*   Small, all-caps labels (Manrope) inside pill-shaped containers. 
*   Use low-saturation background tints of Teal and Emerald for category markers.

### Bento Items
*   Visual headers within grid items should use Playfair Display Medium.
*   Incorporate icons with a thin 1.5pt stroke weight in the Primary Navy color to match the refined aesthetic.