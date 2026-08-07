---
name: Regal Beauty
colors:
  surface: '#fcf9f8'
  surface-dim: '#dcd9d9'
  surface-bright: '#fcf9f8'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f6f3f2'
  surface-container: '#f0eded'
  surface-container-high: '#eae7e7'
  surface-container-highest: '#e4e2e1'
  on-surface: '#1b1c1c'
  on-surface-variant: '#544249'
  inverse-surface: '#303030'
  inverse-on-surface: '#f3f0f0'
  outline: '#877179'
  outline-variant: '#dac0c8'
  surface-tint: '#a2356d'
  primary: '#700545'
  on-primary: '#ffffff'
  primary-container: '#8e245d'
  on-primary-container: '#ffa7cc'
  inverse-primary: '#ffb0d0'
  secondary: '#ab286d'
  on-secondary: '#ffffff'
  secondary-container: '#fc6aaf'
  on-secondary-container: '#6c0040'
  tertiary: '#3a373a'
  on-tertiary: '#ffffff'
  tertiary-container: '#524e51'
  on-tertiary-container: '#c6c0c3'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffd8e6'
  primary-fixed-dim: '#ffb0d0'
  on-primary-fixed: '#3d0023'
  on-primary-fixed-variant: '#831a54'
  secondary-fixed: '#ffd9e5'
  secondary-fixed-dim: '#ffb0ce'
  on-secondary-fixed: '#3e0022'
  on-secondary-fixed-variant: '#8b0454'
  tertiary-fixed: '#e7e1e4'
  tertiary-fixed-dim: '#cbc5c8'
  on-tertiary-fixed: '#1d1b1d'
  on-tertiary-fixed-variant: '#494648'
  background: '#fcf9f8'
  on-background: '#1b1c1c'
  surface-variant: '#e4e2e1'
typography:
  headline-xl:
    fontFamily: Hanken Grotesk
    fontSize: 40px
    fontWeight: '700'
    lineHeight: 48px
    letterSpacing: -0.02em
  headline-xl-mobile:
    fontFamily: Hanken Grotesk
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 38px
    letterSpacing: -0.01em
  headline-lg:
    fontFamily: Hanken Grotesk
    fontSize: 28px
    fontWeight: '600'
    lineHeight: 34px
  headline-md:
    fontFamily: Hanken Grotesk
    fontSize: 22px
    fontWeight: '600'
    lineHeight: 28px
  body-lg:
    fontFamily: Work Sans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Work Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-md:
    fontFamily: Work Sans
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.05em
  label-sm:
    fontFamily: Work Sans
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  base-unit: 8px
  container-padding-mobile: 20px
  container-padding-desktop: 64px
  gutter: 16px
  card-gap: 24px
---

## Brand & Style

The design system is centered on a premium, editorial aesthetic tailored for professional makeup artistry. It balances the authority of a "Queen" with the approachable warmth of a beauty consultant. The style is **Modern/Minimalist** with high-end tactile touches, utilizing generous white space to let portfolio imagery act as the primary visual driver.

The emotional response should be one of confidence, luxury, and meticulous care. The UI employs a "mobile-first, card-based" architecture, treating every service and gallery item as a curated physical invitation.

## Colors

The palette is anchored by "Royal Magenta" (#8e245d) for primary actions and brand identity, signifying depth and professional expertise. "Petal Pink" (#d84d91) is used for accents, highlights, and soft calls to action. 

The background uses a "Silk White" (#fff8fb) to prevent the clinical feel of pure white, providing a soft, cosmetic-tinted canvas. Text is rendered in a deep charcoal (#2d2d2d) rather than pure black to maintain a sophisticated, low-strain reading experience.

## Typography

This design system uses **Hanken Grotesk** for headlines to provide a sharp, contemporary, and premium edge that far surpasses standard system fonts. For body text and functional labels, **Work Sans** is used for its exceptional legibility and professional, grounded feel.

Large headlines should use slight negative letter spacing to feel "tighter" and more editorial. Labels (like category headers or price tags) should be set in uppercase with increased letter spacing to create a sense of organized luxury.

## Layout & Spacing

The layout follows a **Fluid Grid** model with a heavy emphasis on vertical rhythm. On mobile, content is housed in full-width or inset cards with 20px side margins. On desktop, the content is constrained to a maximum width of 1200px to maintain readability.

Spacing follows an 8px linear scale. Section blocks should be separated by large padding (80px+) to maintain the minimalist, airy feel. Components within a card should use tighter spacing (8px, 12px, 16px) to maintain proximity and visual grouping.

## Elevation & Depth

Hierarchy is achieved through **Ambient Shadows** and tonal layering. Since the background is "Silk White," cards use a pure white background to subtly pop forward. 

Shadows must be "long and soft"—specifically using a 10-15% opacity of the Primary Magenta color instead of pure gray. This "tinted shadow" technique creates a glow effect that mimics professional studio lighting. Depth is used sparingly to signify interactivity; buttons and active cards "lift" slightly on hover/touch.

## Shapes

The shape language is defined by **High Radii (20px)**. This softness mirrors the organic curves of the face and the application of makeup. 

- **Cards & Large Containers:** 20px (Standardized for all portfolio and service blocks).
- **Buttons & Inputs:** 12px (Slightly sharper than cards to suggest precision and utility).
- **Images:** Must always carry the container's 20px radius; sharp corners are strictly prohibited to maintain the brand's softness.

## Components

### Buttons
Primary buttons use the "Royal Magenta" background with white text. They should have a subtle 4px vertical offset shadow that matches the button color. Secondary buttons use a "Petal Pink" ghost style (1px border, no fill).

### Cards
Service cards are the core component. They feature a top-aligned image, followed by a title in Headline-MD, and a price label in Label-MD. The card container has a white background and the "Ambient Shadow" described in the Elevation section.

### Form Fields
Input fields are "Silk White" with a 1px border of #d84d91. On focus, the border thickens to 2px. Labels sit above the field in Label-SM Charcoal.

### Chips & Tags
Used for "Service Categories" (e.g., "Bridal," "Editorial"). These are small, pill-shaped elements with a light Petal Pink background (#d84d91 at 10% opacity) and dark magenta text.

### Image Gallery
Images should use a "Masonry" layout on desktop and a vertical stack on mobile, always maintaining the 20px rounded corners and a subtle hover-zoom effect to emphasize the detail of the makeup work.