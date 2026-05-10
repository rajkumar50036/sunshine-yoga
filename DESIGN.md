---
name: Sunshine Yoga
colors:
  surface: '#fbfbe2'
  surface-dim: '#dbdcc3'
  surface-bright: '#fbfbe2'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f5f5dc'
  surface-container: '#efefd7'
  surface-container-high: '#eaead1'
  surface-container-highest: '#e4e4cc'
  on-surface: '#1b1d0e'
  on-surface-variant: '#454742'
  inverse-surface: '#303221'
  inverse-on-surface: '#f2f2d9'
  outline: '#767872'
  outline-variant: '#c6c7c0'
  surface-tint: '#5e5e5c'
  primary: '#5e5e5c'
  on-primary: '#ffffff'
  primary-container: '#fdfbf7'
  on-primary-container: '#747471'
  inverse-primary: '#c8c6c3'
  secondary: '#576159'
  on-secondary: '#ffffff'
  secondary-container: '#d8e3d8'
  on-secondary-container: '#5b655d'
  tertiary: '#5c5d6e'
  on-tertiary: '#ffffff'
  tertiary-container: '#fdfaff'
  on-tertiary-container: '#717283'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#e4e2de'
  primary-fixed-dim: '#c8c6c3'
  on-primary-fixed: '#1b1c1a'
  on-primary-fixed-variant: '#474744'
  secondary-fixed: '#dae5db'
  secondary-fixed-dim: '#bec9bf'
  on-secondary-fixed: '#141e17'
  on-secondary-fixed-variant: '#3f4941'
  tertiary-fixed: '#e1e1f5'
  tertiary-fixed-dim: '#c5c5d8'
  on-tertiary-fixed: '#191b29'
  on-tertiary-fixed-variant: '#444655'
  background: '#fbfbe2'
  on-background: '#1b1d0e'
  surface-variant: '#e4e4cc'
typography:
  display-lg:
    fontFamily: Playfair Display
    fontSize: 64px
    fontWeight: '600'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Playfair Display
    fontSize: 48px
    fontWeight: '500'
    lineHeight: '1.2'
  headline-md:
    fontFamily: Playfair Display
    fontSize: 32px
    fontWeight: '500'
    lineHeight: '1.3'
  headline-sm:
    fontFamily: Playfair Display
    fontSize: 24px
    fontWeight: '500'
    lineHeight: '1.4'
  headline-lg-mobile:
    fontFamily: Playfair Display
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.2'
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
    fontWeight: '600'
    lineHeight: '1.2'
    letterSpacing: 0.05em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  base: 8px
  container-max: 1280px
  gutter: 24px
  margin-desktop: 64px
  margin-mobile: 20px
  section-padding: 120px
---

## Brand & Style

This design system embodies the intersection of ancient wellness practices and cutting-edge SaaS technology. It targets a high-discerning audience that values tranquility, exclusivity, and digital seamlessness. The brand personality is "Enlightened Tech"—sophisticated yet grounded, premium yet accessible.

The visual style is a refined **Glassmorphism**, utilizing translucent layers to create a sense of breathability and openness. Cinematic lighting is simulated through directional soft gradients that mimic the "golden hour," providing a warm, inviting glow that guides the eye. The interface feels weightless, utilizing heavy whitespace to reduce cognitive load and evoke a sense of mental clarity.

## Colors

The palette is rooted in nature and luxury. The primary "Cream" base provides a softer, more premium alternative to pure white, reducing eye strain. The secondary "Pastel Green" and tertiary "Lavender" are used for subtle categorization and environmental cues (e.g., restorative vs. active sessions).

"Light Gold" is reserved for high-impact accents, such as active states, primary call-to-actions, and brand-defining iconography. Gradients should transition between these soft pastels and transparent whites to achieve the glassmorphic depth required.

## Typography

This system utilizes a classic high-contrast pairing. **Playfair Display** provides the editorial authority and luxury feel for headlines, reflecting the boutique nature of the brand. **Inter** handles the functional aspects of the SaaS experience, ensuring maximum legibility for class schedules, bio-data, and navigation.

Headlines should utilize slightly tighter letter-spacing to maintain a modern startup aesthetic. Labels and captions use Inter with increased tracking and uppercase styling to denote technical or functional information clearly.

## Layout & Spacing

The layout follows a **Fixed Grid** model on desktop to maintain an editorial, magazine-like feel. We employ a 12-column grid with generous margins to create a "contained" luxury experience.

Spacing is expansive. The design prioritizes vertical rhythm, using significant padding between sections to allow content to "breathe," mirroring the meditative focus of yoga. Elements are often center-aligned or offset in a masonry style to break the rigidity of a standard SaaS dashboard.

## Elevation & Depth

Hierarchy is achieved through **Glassmorphism** and soft environmental shadows. 

1.  **Base Layer:** Soft Cream solid background.
2.  **Mid Layer (Cards):** Translucent white (#FFFFFF80) with a 20px backdrop-blur. These containers use a 1px soft-white border to define edges against light backgrounds.
3.  **Top Layer (Modals/Popovers):** Higher opacity white with a more pronounced, extra-diffused shadow tinted with Lavender (#E6E6FA) to simulate cinematic backlighting.

Avoid harsh blacks; all shadows should be low-opacity and color-matched to the ambient palette.

## Shapes

The shape language is organic and approachable. We utilize a "Rounded" (0.5rem base) strategy to soften the technical nature of the SaaS platform. 

Cards and primary containers utilize `rounded-xl` (1.5rem) to emphasize the wellness aesthetic. Buttons and chips are often fully rounded (pill-shaped) to provide a tactile, "pebble-like" feel that is comfortable to interact with.

## Components

*   **Buttons:** Primary buttons are pill-shaped with a Gold to Pale-Yellow gradient. Secondary buttons use the glass effect with a subtle gold border.
*   **Cards:** "Yoga Session" cards feature a large image background with a glassmorphic overlay at the bottom for session details.
*   **Input Fields:** Ghost-style inputs with a subtle bottom border in Gold or a fully enclosed glassmorphic container with rounded corners.
*   **Glass Chips:** Used for tags (e.g., "Vinyasa", "Intermediate"). They feature a 40% opaque background of the Lavender or Green palette.
*   **Progress Indicators:** Circular, thin-stroke rings using Gold to track meditation or class progress.
*   **Cinematic Dividers:** Instead of lines, use soft gradient fades or wide whitespace to separate content blocks.