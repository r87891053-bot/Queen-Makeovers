---
name: Pro-Tech Bharat
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
  on-surface-variant: '#454650'
  inverse-surface: '#2d3133'
  inverse-on-surface: '#eff1f3'
  outline: '#767681'
  outline-variant: '#c6c5d1'
  surface-tint: '#4d5b96'
  primary: '#00041f'
  on-primary: '#ffffff'
  primary-container: '#071952'
  on-primary-container: '#7583c1'
  inverse-primary: '#b7c4ff'
  secondary: '#006877'
  on-secondary: '#ffffff'
  secondary-container: '#8debff'
  on-secondary-container: '#006b7a'
  tertiary: '#0a0500'
  on-tertiary: '#ffffff'
  tertiary-container: '#2b1c00'
  on-tertiary-container: '#b07d00'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#dde1ff'
  primary-fixed-dim: '#b7c4ff'
  on-primary-fixed: '#03154f'
  on-primary-fixed-variant: '#35437c'
  secondary-fixed: '#a3eeff'
  secondary-fixed-dim: '#76d4e7'
  on-secondary-fixed: '#001f25'
  on-secondary-fixed-variant: '#004e5a'
  tertiary-fixed: '#ffdea9'
  tertiary-fixed-dim: '#ffba27'
  on-tertiary-fixed: '#271900'
  on-tertiary-fixed-variant: '#5e4100'
  background: '#f7f9fb'
  on-background: '#191c1e'
  surface-variant: '#e0e3e5'
typography:
  headline-xl:
    fontFamily: Hanken Grotesk
    fontSize: 48px
    fontWeight: '800'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  headline-xl-mobile:
    fontFamily: Hanken Grotesk
    fontSize: 36px
    fontWeight: '800'
    lineHeight: '1.2'
  headline-lg:
    fontFamily: Hanken Grotesk
    fontSize: 32px
    fontWeight: '700'
    lineHeight: '1.2'
  headline-md:
    fontFamily: Hanken Grotesk
    fontSize: 24px
    fontWeight: '600'
    lineHeight: '1.3'
  body-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-md:
    fontFamily: Hanken Grotesk
    fontSize: 14px
    fontWeight: '600'
    lineHeight: '1'
    letterSpacing: 0.05em
  button:
    fontFamily: Hanken Grotesk
    fontSize: 16px
    fontWeight: '700'
    lineHeight: '1'
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  base: 8px
  section-gap-desktop: 120px
  section-gap-mobile: 64px
  container-max: 1280px
  gutter: 24px
  margin-mobile: 20px
---

## Brand & Style
The design system is engineered for a professional, high-trust digital solutions platform targeting small business owners in India. The personality is a balance of **Corporate Reliability** and **Technological Innovation**. 

The aesthetic follows a **Modern / Corporate** style with subtle **Glassmorphism** and high-precision layouts. It prioritizes clarity and approachability to ensure users feel confident in the digital transformation services offered. The interface utilizes high-contrast accents to guide decision-making while maintaining a sophisticated, stable foundation.

## Colors
The palette is rooted in a Deep Navy (#071952) to evoke authority and permanence. Vibrant Teal (#088395) serves as the primary action and brand identifier, bridge-linking the deep navy with modern tech aesthetics. 

**Bright Gold (#FFB703)** is reserved strictly for primary Calls to Action (CTAs) to ensure maximum conversion visibility against the cooler background tones. Gradients should be used sparingly for hero sections and decorative background shapes to add depth without compromising readability.

## Typography
This design system pairs **Hanken Grotesk** for headings and labels with **Plus Jakarta Sans** for body copy. 

- **Hanken Grotesk** provides a sharp, contemporary professional feel, ideal for conveying precision. 
- **Plus Jakarta Sans** adds a touch of warmth and approachability for longer-form content, essential for building trust with business owners. 
- Tighten letter-spacing on larger headlines to maintain a "locked-in" editorial look. Ensure ample line-height for body text to cater to mobile readability across various device qualities.

## Layout & Spacing
The layout follows a **Fluid Grid** model with a strict 8px base unit. 

- **Desktop:** 12-column grid with 24px gutters. Center-aligned with a max-width of 1280px.
- **Mobile:** Single column with 20px side margins. 
- **Vertical Rhythm:** Use generous section gaps (120px on desktop) to allow the "Web Creator" expertise to breathe. Cards should use a consistent 32px internal padding to maintain a premium feel. 
- Overlap elements slightly when using the Navy-to-Teal gradient backgrounds to create a sense of three-dimensional space.

## Elevation & Depth
The design system employs **Tonal Layering** and **Ambient Shadows**. 

1. **Surface Level 0:** The primary light neutral background (#F8FAFC).
2. **Surface Level 1 (Cards):** Pure white surfaces with a soft, diffused shadow (0px 10px 30px rgba(7, 25, 82, 0.05)).
3. **Surface Level 2 (Interactive):** Elevated state with a more pronounced teal-tinted shadow to indicate hover or focus.

Use **Glassmorphism** for navigation bars: a white semi-transparent fill (80% opacity) with a 12px backdrop blur ensures the content remains legible while scrolling over colorful hero sections.

## Shapes
The shape language is **Rounded**, communicating modern friendliness without sacrificing the structural integrity expected of a professional service. 

- **Standard Elements:** 0.5rem (8px) radius for inputs and small cards.
- **Large Containers:** 1.5rem (24px) for main content sections and feature cards to create a distinct, modern "soft-tech" silhouette.
- **CTAs:** Use fully rounded (pill-shaped) ends for primary buttons to make them feel more "clickable" and distinct from structural UI elements.

## Components
- **Primary Button:** Pill-shaped, Bright Gold (#FFB703) background, Navy text, bold weight. Use a slight lift-on-hover effect.
- **Secondary Button:** Navy (#071952) outline with 2px stroke, Navy text.
- **Service Cards:** White background, 24px rounded corners, subtle shadow. Top-left placement for icons using Teal (#088395) circular backgrounds.
- **Feature Chips:** Small, 14px text, Light Teal background (10% opacity) with Teal text for categorizing services or tech stacks.
- **Input Fields:** 8px rounded corners, 1px border (#E2E8F0). On focus, the border transitions to Vibrant Teal with a soft glow.
- **Trust Bar:** A horizontal strip of grayscale partner/client logos with 50% opacity, transitioning to full color on hover.