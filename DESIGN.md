---
name: ProClean Solutions Design System
colors:
  surface: '#f6faf9'
  surface-dim: '#d7dbda'
  surface-bright: '#f6faf9'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f1f4f3'
  surface-container: '#ebefee'
  surface-container-high: '#e5e9e8'
  surface-container-highest: '#dfe3e2'
  on-surface: '#181c1c'
  on-surface-variant: '#3e4948'
  inverse-surface: '#2d3131'
  inverse-on-surface: '#eef1f0'
  outline: '#6e7979'
  outline-variant: '#bdc9c8'
  surface-tint: '#006a69'
  primary: '#006161'
  on-primary: '#ffffff'
  primary-container: '#0e7c7b'
  on-primary-container: '#c3fffd'
  inverse-primary: '#7cd5d3'
  secondary: '#825500'
  on-secondary: '#ffffff'
  secondary-container: '#fdb64a'
  on-secondary-container: '#704800'
  tertiary: '#00643f'
  on-tertiary: '#ffffff'
  tertiary-container: '#097f52'
  on-tertiary-container: '#cdffde'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#98f2f0'
  primary-fixed-dim: '#7cd5d3'
  on-primary-fixed: '#002020'
  on-primary-fixed-variant: '#00504f'
  secondary-fixed: '#ffddb3'
  secondary-fixed-dim: '#ffb950'
  on-secondary-fixed: '#291800'
  on-secondary-fixed-variant: '#633f00'
  tertiary-fixed: '#93f7bf'
  tertiary-fixed-dim: '#77daa4'
  on-tertiary-fixed: '#002112'
  on-tertiary-fixed-variant: '#005232'
  background: '#f6faf9'
  on-background: '#181c1c'
  surface-variant: '#dfe3e2'
typography:
  headline-xl:
    fontFamily: Playfair Display
    fontSize: 48px
    fontWeight: '700'
    lineHeight: '1.2'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Playfair Display
    fontSize: 36px
    fontWeight: '700'
    lineHeight: '1.2'
  headline-lg-mobile:
    fontFamily: Playfair Display
    fontSize: 30px
    fontWeight: '700'
    lineHeight: '1.2'
  headline-md:
    fontFamily: Playfair Display
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
    fontWeight: '600'
    lineHeight: '1'
    letterSpacing: 0.05em
  caption:
    fontFamily: Inter
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
  base: 8px
  xs: 4px
  sm: 12px
  md: 24px
  lg: 48px
  xl: 80px
  container-max: 1200px
  gutter: 24px
  margin-mobile: 20px
---

## Brand & Style
The design system for this brand is built upon the pillars of **Pristine Luxury** and **Exceptional Trust**. It targets a high-end demographic in the twin cities, evoking an emotional response of immediate relief and sophisticated order. 

The aesthetic is a hybrid of **Modern Minimalism** and **Soft Glassmorphism**. It utilizes expansive white space to mirror the literal cleanliness of the service, while employing translucent layers and refined typography to communicate a premium, bespoke experience. The interface should feel breathable, calm, and meticulously organized.

## Colors
The palette is rooted in a "Clean-Tech" luxury aesthetic. 

- **Primary (Deep Teal):** Used for primary actions, navigation headers, and authoritative elements. It represents stability and professional depth.
- **Secondary (Warm Gold):** Reserved for high-value conversions, trust badges, and premium service highlights. It adds a glow of warmth and energy.
- **Background (Mint-White):** A soft, airy base that prevents the clinical feel of pure white, providing a gentle canvas for glass effects.
- **Text (Charcoal Teal):** High-contrast readability that maintains the cool undertone of the brand.
- **Success (Emerald):** Used for confirmation states and completed service indicators.

## Typography
This design system employs a classic typographic pairing to balance heritage with modern efficiency. 

**Playfair Display** is used for all headlines to establish a literary, high-end editorial feel. It should be typeset with slightly tighter letter-spacing in larger sizes. 

**Inter** provides a highly legible, neutral counterpoint for all functional text. It ensures that service details and pricing are communicated with absolute clarity. For labels and small buttons, use uppercase with increased tracking to maintain the luxury "spaced" aesthetic.

## Layout & Spacing
The layout follows a **Fixed Grid** model on desktop (12 columns, 1200px max-width) and a **Fluid Content** model on mobile. 

The spacing philosophy is "Generous and Intentional." Use large `xl` padding for section vertical spacing to ensure elements never feel crowded. 
- **Mobile:** 4-column layout, 20px side margins.
- **Tablet:** 8-column layout, 32px side margins.
- **Desktop:** 12-column layout, centered with 24px gutters.

Avoid tight clusters; every component should have "room to breathe," reflecting the spaciousness of a freshly cleaned luxury home.

## Elevation & Depth
Depth is created through **Soft Multi-layered Shadows** and **Glassmorphism**. 

1.  **Surfaces:** Use high-transparency white (e.g., `rgba(255, 255, 255, 0.7)`) with a `20px` backdrop-blur for cards that sit atop imagery or colored backgrounds.
2.  **Shadows:** Avoid harsh blacks. Use the Primary color (Deep Teal) at very low opacity (3-5%) for shadows to create a "tinted" depth that feels more integrated.
3.  **Layers:** 
    - *Level 0 (Base):* Background color.
    - *Level 1 (Cards):* White surface, 1px subtle border (#E0E7E6), and a soft diffused shadow.
    - *Level 2 (Modals/Popovers):* Glassmorphic surface with a more pronounced shadow (blur: 40px, spread: -10px).

## Shapes
The design system uses **Rounded** geometry to evoke friendliness and safety. 

- **Standard Elements:** Buttons and small cards use a `0.5rem` radius.
- **Large Containers:** Service cards and main content areas use `rounded-lg` (1rem).
- **Hero/Featured Elements:** Use `rounded-xl` (1.5rem) to create a soft, modern frame for high-quality photography.
- **Input Fields:** Should maintain a `0.5rem` radius for consistency with buttons.

## Components
- **Buttons:** Primary buttons use the Deep Teal background with white text. Secondary buttons use a Deep Teal outline or the Gold Accent for CTA. All buttons must have a minimum height of 48px.
- **Cards:** Utilize the glassmorphism effect for cards placed over high-resolution images. Cards should feature a 1px border in a slightly darker mint-white to define edges.
- **Input Fields:** Minimalist style with a subtle background tint (#F0F4F3) and a 2px Primary color bottom border or full focus ring.
- **Chips/Status Tags:** Use rounded-pill shapes with low-opacity background fills (e.g., Success Green at 10% opacity with 100% opacity text).
- **Service Lists:** Use high-quality icons with a circular background of the secondary Gold color at 15% opacity to draw attention without overpowering the text.
- **Interactive States:** On hover, cards should lift slightly using a more pronounced tinted shadow, and buttons should have a subtle luminance increase.