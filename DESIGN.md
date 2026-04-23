---
name: Premium Editorial Consultant
colors:
  surface: '#faf9f5'
  surface-dim: '#dbdad6'
  surface-bright: '#faf9f5'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f4f4f0'
  surface-container: '#efeeea'
  surface-container-high: '#e9e8e4'
  surface-container-highest: '#e3e2df'
  on-surface: '#1b1c1a'
  on-surface-variant: '#3e494a'
  inverse-surface: '#2f312e'
  inverse-on-surface: '#f2f1ed'
  outline: '#6f797a'
  outline-variant: '#bec8ca'
  surface-tint: '#006972'
  primary: '#00535b'
  on-primary: '#ffffff'
  primary-container: '#006d77'
  on-primary-container: '#9becf7'
  inverse-primary: '#82d3de'
  secondary: '#765a05'
  on-secondary: '#ffffff'
  secondary-container: '#ffd87c'
  on-secondary-container: '#795d08'
  tertiary: '#634500'
  on-tertiary: '#ffffff'
  tertiary-container: '#825b00'
  on-tertiary-container: '#ffd99b'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#9ff0fb'
  primary-fixed-dim: '#82d3de'
  on-primary-fixed: '#001f23'
  on-primary-fixed-variant: '#004f56'
  secondary-fixed: '#ffdf96'
  secondary-fixed-dim: '#e7c268'
  on-secondary-fixed: '#251a00'
  on-secondary-fixed-variant: '#5a4400'
  tertiary-fixed: '#ffdea9'
  tertiary-fixed-dim: '#ffba27'
  on-tertiary-fixed: '#271900'
  on-tertiary-fixed-variant: '#5e4100'
  background: '#faf9f5'
  on-background: '#1b1c1a'
  surface-variant: '#e3e2df'
typography:
  display-lg:
    fontFamily: Noto Serif
    fontSize: 64px
    fontWeight: '300'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Noto Serif
    fontSize: 48px
    fontWeight: '400'
    lineHeight: '1.2'
  headline-md:
    fontFamily: Noto Serif
    fontSize: 32px
    fontWeight: '400'
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
    lineHeight: '1.5'
  label-caps:
    fontFamily: Manrope
    fontSize: 12px
    fontWeight: '600'
    lineHeight: '1'
    letterSpacing: 0.1em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  unit: 8px
  container-max: 1280px
  gutter: 24px
  margin-mobile: 20px
  margin-desktop: 64px
  section-padding: 120px
---

## Brand & Style

The design system is rooted in an **Editorial Minimalism** aesthetic, tailored for a high-end business consultancy. It balances the authority of a traditional firm with the vibrant energy of modern strategic thinking. The visual narrative is built on expansive whitespace, refined typography, and a "less is more" philosophy that allows premium content to breathe.

The UI should feel sophisticated, confident, and intentionally curated. It leverages a mix of high-contrast color accents and subtle transitions to guide the user's eye. Every element serves a purpose, avoiding unnecessary decoration in favor of clarity and prestige. For the RTL (Hebrew) implementation, the layout mirrors the horizontal axis while maintaining the same strict adherence to vertical rhythm and typographic hierarchy.

## Colors

The palette is anchored by a deep, intellectual **Professional Teal (#006D77)**, which serves as the primary driver for brand recognition and structural elements. This is complemented by a warm, ivory-leaning **Off-White (#FDFCF8)** background that prevents the sterile feel of pure white, providing a gallery-like backdrop.

Vibrancy is introduced through **Warm Gold (#E9C46A)** and **Amber (#FFB703)**. These are used sparingly as high-visibility accents for calls to action, highlights, and interactive states. Text should primarily use a darkened shade of the teal (#002327) to maintain a soft but high-contrast readability.

## Typography

Typography is the cornerstone of this design system’s editorial feel. We pair the timeless elegance of **Noto Serif** for headlines with the clean, modern precision of **Manrope** for body text. 

Headlines should be light or regular in weight to maintain a sophisticated air, using negative letter spacing on larger displays to create a tight, professional lockup. For Hebrew (RTL), ensure line heights are slightly increased to accommodate the distinct verticality of the script, maintaining the same optical weight across both languages.

## Layout & Spacing

This design system utilizes a **Fixed Grid** model within a flexible container. A 12-column grid provides the framework for desktop, while a 4-column grid handles mobile devices. Spacing is generous, emphasizing vertical "breathing room" between sections (typically 120px or more) to signify premium quality.

For RTL support, the grid logic remains identical but the column flow and margin directions are reversed. Alignment should be strictly right-aligned for Hebrew text, ensuring that the visual "weight" of the editorial layout remains balanced.

## Elevation & Depth

To maintain the clean, editorial aesthetic, elevation is handled through **Tonal Layers** and **Low-Contrast Outlines** rather than heavy shadows. 

Physical depth is implied through the stacking of off-white containers on slightly tinted backgrounds. When a shadow is necessary (e.g., a floating navigation bar or a primary modal), it should be an **Ambient Shadow**: extremely diffused, with a very low opacity (3-5%) and a slight teal tint to ensure it feels integrated into the professional palette.

## Shapes

The shape language is **Soft** and restrained. We use subtle 0.25rem (4px) corner radii for standard UI components like buttons and inputs. Larger cards or featured images may use up to 0.75rem (12px) to provide a gentle, approachable feel without losing the structural "edge" required for a business context. 

Strict geometric shapes are preferred for containers to reinforce the grid-based editorial style. Interactive elements should feel crisp and architectural.

## Components

### Buttons
Primary buttons utilize the Deep Teal (#006D77) with white text. Secondary buttons use a ghost style with a 1px teal border. Accent buttons for high-conversion moments use the Gold (#E9C46A) with dark teal text. All buttons feature a subtle transition on hover, shifting background opacity.

### Input Fields
Inputs are minimalist, defined by a bottom-border only or a very light gray (#E0E0E0) full border. When focused, the border transitions to Deep Teal. Labels are always positioned above the input in the `label-caps` style.

### Cards
Cards are used for services or case studies. They feature large imagery with a "bleed" effect to the top of the card and use significant internal padding (32px+). Borders should be thin and low-contrast.

### Navigation
The navigation should be airy, using the `label-caps` typography for menu items. In RTL mode, the logo shifts to the right and the menu items to the left, ensuring a natural reading flow for Hebrew users.

### Editorial Accents
Use vertical or horizontal dividers (1px width) in Deep Teal or light gray to separate content sections, mimicking the layout of a premium broadsheet or high-end magazine.