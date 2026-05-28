---
name: Smart Invoicify
colors:
  surface: '#fbf8fc'
  surface-dim: '#dcd9dd'
  surface-bright: '#fbf8fc'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f6f2f7'
  surface-container: '#f0edf1'
  surface-container-high: '#eae7eb'
  surface-container-highest: '#e4e1e6'
  on-surface: '#1b1b1e'
  on-surface-variant: '#434655'
  inverse-surface: '#303033'
  inverse-on-surface: '#f3f0f4'
  outline: '#737686'
  outline-variant: '#c3c6d7'
  surface-tint: '#0053db'
  primary: '#004ac6'
  on-primary: '#ffffff'
  primary-container: '#2563eb'
  on-primary-container: '#eeefff'
  inverse-primary: '#b4c5ff'
  secondary: '#006b5f'
  on-secondary: '#ffffff'
  secondary-container: '#6df5e1'
  on-secondary-container: '#006f64'
  tertiary: '#525556'
  on-tertiary: '#ffffff'
  tertiary-container: '#6b6d6e'
  on-tertiary-container: '#eff0f1'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#dbe1ff'
  primary-fixed-dim: '#b4c5ff'
  on-primary-fixed: '#00174b'
  on-primary-fixed-variant: '#003ea8'
  secondary-fixed: '#71f8e4'
  secondary-fixed-dim: '#4fdbc8'
  on-secondary-fixed: '#00201c'
  on-secondary-fixed-variant: '#005048'
  tertiary-fixed: '#e1e3e4'
  tertiary-fixed-dim: '#c5c7c8'
  on-tertiary-fixed: '#191c1d'
  on-tertiary-fixed-variant: '#454748'
  background: '#fbf8fc'
  on-background: '#1b1b1e'
  surface-variant: '#e4e1e6'
  surface-off-white: '#FDFDFD'
  typography-charcoal: '#18181B'
  typography-muted: '#71717A'
  mint-success: '#D1FAE5'
  border-subtle: '#E4E4E7'
typography:
  display-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 64px
    fontWeight: '700'
    lineHeight: 72px
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 40px
    fontWeight: '700'
    lineHeight: 48px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 36px
    fontWeight: '600'
    lineHeight: 44px
    letterSpacing: -0.01em
  headline-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-sm:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '500'
    lineHeight: 20px
    letterSpacing: 0.02em
  label-xs:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '600'
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
  container-max: 1200px
  section-gap-lg: 120px
  section-gap-sm: 64px
  grid-gutter: 24px
  stack-space: 16px
---

## Brand & Style
The design system for the landing page transitions the product from its existing "luxury dark mode" aesthetic into a "Professional Light" identity that emphasizes trust, clarity, and business confidence. The brand personality is calm and competent—moving away from "tech-heavy" aesthetics toward a "business-friendly" atmosphere. It evokes the feeling of a well-organized physical office: clean desks, high-quality paper, and precise instruments.

The chosen style is **Corporate / Modern** with a focus on **Minimalism**. It utilizes generous whitespace to reduce cognitive load and subtle depth markers (soft shadows and translucent layers) to create a structured, professional hierarchy. The interface avoids aggressive gradients or complex textures, opting instead for a pristine, stable environment that suggests financial reliability.

## Colors
The palette is rooted in "Professional Blues" to establish immediate industry trust. The primary blue is used strategically for calls to action and critical brand markers. 

A high-contrast charcoal is reserved for typography to ensure maximum legibility, while the background remains a very light off-white to prevent the "starkness" of pure white. A soft mint/teal serves as the secondary accent, specifically for success states, secondary highlights, and "Growth" indicators, reinforcing a positive financial narrative. Use the neutral colors for borders and secondary text to maintain a low-noise environment.

## Typography
The system uses **Plus Jakarta Sans** for headlines to provide a friendly, modern, and approachable character. Its slightly rounded terminals complement the professional tone without feeling overly rigid. 

**Inter** is used for body copy and UI labels to ensure clinical legibility and a systematic feel. Line heights are kept generous (1.5x to 1.6x for body text) to support a relaxed reading pace. Narrative-style copy should be set in `body-lg` to maintain an editorial feel on the landing page.

## Layout & Spacing
The layout follows a **Fixed Grid** philosophy for the landing page to maintain a rhythmic, centered focal point that guides the eye. 

- **Desktop:** 12-column grid with a 1200px max-width. Sections are separated by a massive 120px vertical gap to create an air of premium quality.
- **Tablet:** 8-column grid with 32px margins. 
- **Mobile:** 4-column grid with 20px margins.

The spacing rhythm is strictly based on an 8px scale. Components like cards should use 32px or 40px internal padding to ensure content "breathes," preventing the dense look typical of older accounting software.

## Elevation & Depth
This design system uses **Tonal Layers** combined with **Ambient Shadows** to create a sense of organized hierarchy. 

Surfaces are primarily flat (Level 0), but primary interactive cards and modals use Level 1 and Level 2 elevation:
- **Level 1 (Subtle):** A very soft, diffused shadow (Blur 15px, Opacity 4%) used for feature cards.
- **Level 2 (Active):** Triggered on hover, using a slightly deeper shadow (Blur 30px, Opacity 8%) and a subtle scale-up (101%) to indicate interactivity.
- **Borders:** Instead of heavy shadows, use 1px "low-contrast outlines" in `#E4E4E7` to define boundaries cleanly.

## Shapes
A **Rounded** (8px to 24px) shape language is applied across the system. 
- **Standard UI (Inputs, Buttons):** 8px (`rounded-md`).
- **Feature Cards:** 16px (`rounded-lg`).
- **Large Sections/Containers:** 24px (`rounded-xl`).

This level of roundedness softens the professional edge of the finance-focused app, making it feel more like a modern tool and less like a legacy banking interface.

## Components
- **Buttons:** Primary buttons are solid `#2563EB` with white text. Secondary buttons use a "Ghost" style: a transparent background with a `#E4E4E7` border and charcoal text. Buttons should be "Pill-shaped" (100px radius) for the Hero section but "Soft-rounded" (8px) for functional UI.
- **Cards:** Use the "Sienna" logic from the brand but adapted for light mode—white backgrounds with a subtle border and Level 1 elevation. Include a 40px padding for feature content.
- **Chips/Badges:** Small, rounded-full indicators. For "Success" (e.g., Paid), use a `#D1FAE5` background with a darker teal text.
- **Inputs:** Clean fields with an 8px radius and a `#F9FAFB` fill. On focus, the border transitions to Primary Blue with a subtle 2px outer glow.
- **FAQ Accordion:** A minimalist vertical stack. Questions are bolded; answers appear with a smooth slide-down animation. Use a simple chevron icon that rotates 180 degrees.
- **Navigation:** A sticky top bar with a glassmorphism backdrop (blur: 10px, opacity: 80%) to maintain context as the user scrolls.