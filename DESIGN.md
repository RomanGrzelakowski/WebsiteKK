---
name: Serene Path
colors:
  surface: '#fbf9f4'
  surface-dim: '#dbdad5'
  surface-bright: '#fbf9f4'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f5f3ee'
  surface-container: '#f0eee9'
  surface-container-high: '#eae8e3'
  surface-container-highest: '#e4e2dd'
  on-surface: '#1b1c19'
  on-surface-variant: '#424848'
  inverse-surface: '#30312e'
  inverse-on-surface: '#f2f1ec'
  outline: '#737878'
  outline-variant: '#c2c7c7'
  surface-tint: '#536162'
  primary: '#334142'
  on-primary: '#ffffff'
  primary-container: '#4a5859'
  on-primary-container: '#bfcece'
  inverse-primary: '#bac9ca'
  secondary: '#506167'
  on-secondary: '#ffffff'
  secondary-container: '#d1e3ea'
  on-secondary-container: '#55656c'
  tertiary: '#3c403b'
  on-tertiary: '#ffffff'
  tertiary-container: '#535752'
  on-tertiary-container: '#c9ccc6'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d6e5e6'
  primary-fixed-dim: '#bac9ca'
  on-primary-fixed: '#101e1f'
  on-primary-fixed-variant: '#3b494a'
  secondary-fixed: '#d4e5ed'
  secondary-fixed-dim: '#b8c9d1'
  on-secondary-fixed: '#0d1e23'
  on-secondary-fixed-variant: '#39494f'
  tertiary-fixed: '#e0e3dd'
  tertiary-fixed-dim: '#c4c7c1'
  on-tertiary-fixed: '#191d18'
  on-tertiary-fixed-variant: '#444843'
  background: '#fbf9f4'
  on-background: '#1b1c19'
  surface-variant: '#e4e2dd'
typography:
  display:
    fontFamily: Playfair Display
    fontSize: 48px
    fontWeight: '600'
    lineHeight: '1.2'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Playfair Display
    fontSize: 32px
    fontWeight: '500'
    lineHeight: '1.3'
  headline-lg-mobile:
    fontFamily: Playfair Display
    fontSize: 28px
    fontWeight: '500'
    lineHeight: '1.3'
  headline-md:
    fontFamily: Playfair Display
    fontSize: 24px
    fontWeight: '500'
    lineHeight: '1.4'
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
    lineHeight: '1.4'
    letterSpacing: 0.03em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  unit: 4px
  container-max-width: 1120px
  gutter: 24px
  margin-mobile: 20px
  margin-desktop: 40px
  section-gap-lg: 120px
  section-gap-md: 80px
---

## Brand & Style

The brand personality is rooted in radical empathy, professional stability, and quietude. It aims to reduce the cognitive load of users who may be in a state of distress, providing a "digital sanctuary" that feels safe, non-judgmental, and organized.

The design style is a blend of **Soft Minimalism** and **Modern Corporate**. It prioritizes generous whitespace to allow content to breathe, avoiding any aggressive visual stimuli. The aesthetic utilizes high-quality typography and a muted, nature-inspired palette to evoke a sense of organic growth and mental clarity. Every interaction should feel intentional and calm, utilizing soft transitions rather than abrupt changes.

## Colors

The color strategy relies on a low-contrast, earthy foundation to minimize eye strain and anxiety. 

- **Primary (#4A5859):** A deep, muted charcoal-teal used for high-importance text and primary actions. It represents grounding and authority.
- **Secondary (#7D8E95):** A soft slate blue for supporting elements and iconography, providing a sense of calm.
- **Surface/Tertiary (#E8EBE4):** A sage-tinted neutral used for subtle section backgrounds and decorative elements.
- **Base (#F9F7F2):** A warm, parchment-like beige used as the main background color to avoid the clinical harshness of pure white.

Functional colors (Success/Error) are desaturated to maintain the soothing atmosphere, ensuring that even alerts do not feel alarming.

## Typography

The typography system creates a balance between tradition (Serif) and clarity (Sans-serif). 

**Playfair Display** is reserved for headlines and editorial moments. Its elegant strokes communicate the wisdom and heritage of psychological practice. **Inter** is used for all functional text, body copy, and UI labels. It provides high legibility and a neutral, systematic feel that ensures information is easy to process.

For long-form reading, such as therapy descriptions or articles, use `body-lg` with the primary color at 90% opacity to reduce contrast-induced fatigue.

## Layout & Spacing

This design system uses a **Fixed Grid** approach for desktop to create a sense of containment and focus. 

- **Desktop:** A 12-column grid with a maximum width of 1120px. 
- **Tablet:** An 8-column fluid grid.
- **Mobile:** A 4-column fluid grid.

The spacing philosophy is "breathable." We utilize a 4px baseline shift but prioritize large section gaps (`section-gap-lg`) to prevent the interface from feeling cluttered. Alignment should be primarily left-aligned for readability, with centered layouts reserved for hero moments or simplified onboarding screens.

## Elevation & Depth

To evoke safety and tranquility, depth is achieved through **Tonal Layers** and **Ambient Shadows** rather than sharp borders.

Surfaces should feel soft. Use very low-opacity shadows (e.g., 4% - 6% alpha) with a large blur radius (20px+) and a slight vertical offset. This creates a "floating" effect that feels light and airy. 

Where stacking is required, use subtle shifts in background color (moving from `#F9F7F2` to `#E8EBE4`) to define hierarchy. Avoid heavy dark shadows; instead, use shadows tinted with the primary color (`#4A5859`) at very low intensities to maintain the color harmony.

## Shapes

The shape language is consistently **Rounded**. Sharp corners are avoided to remove any visual "hardness" or perceived aggression. 

Standard components like input fields and buttons utilize a 0.5rem (8px) radius. Larger containers, such as profile cards or booking modals, should use `rounded-xl` (1.5rem / 24px) to emphasize the soft, welcoming nature of the brand.

## Components

### Buttons
Primary buttons use the dark primary color with white text. Secondary buttons use a transparent background with a subtle 1px border in the secondary color. All buttons feature a 200ms transition on hover, where the background color softens slightly.

### Cards (Empathetic Cards)
Cards are the primary vehicle for practitioner profiles or service descriptions. They feature `rounded-xl` corners, a soft ambient shadow, and a subtle border (#E8EBE4). Images within cards should have a slight desaturation to match the UI.

### Navigation
The header is persistent but minimal. It uses a background blur (glassmorphism) effect with the base color at 80% opacity to maintain context of the page content as the user scrolls.

### Booking Calendar
The calendar must be functional and stress-free. Selected dates use a soft circular background in the primary color. Available dates are indicated with a subtle sage dot underneath the number. Avoid using "Red" for unavailable dates; use a light gray-out effect to signify "booked" without the negative connotation of a cross or red strike.

### Inputs
Fields should be tall and spacious with a 16px internal padding. Focus states are indicated by a soft glow in the secondary color rather than a thick border.