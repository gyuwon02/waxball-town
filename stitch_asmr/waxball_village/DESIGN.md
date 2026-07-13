---
name: WaxBall Village
colors:
  surface: '#fbf9f5'
  surface-dim: '#dbdad6'
  surface-bright: '#fbf9f5'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f5f3ef'
  surface-container: '#efeeea'
  surface-container-high: '#eae8e4'
  surface-container-highest: '#e4e2de'
  on-surface: '#1b1c1a'
  on-surface-variant: '#514345'
  inverse-surface: '#30312e'
  inverse-on-surface: '#f2f0ed'
  outline: '#837375'
  outline-variant: '#d5c2c4'
  surface-tint: '#81515b'
  primary: '#81515b'
  on-primary: '#ffffff'
  primary-container: '#ffc1cc'
  on-primary-container: '#7b4c56'
  inverse-primary: '#f3b7c1'
  secondary: '#3a675a'
  on-secondary: '#ffffff'
  secondary-container: '#bceddc'
  on-secondary-container: '#406d60'
  tertiary: '#5c5d6e'
  on-tertiary: '#ffffff'
  tertiary-container: '#d0d0e3'
  on-tertiary-container: '#575869'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffd9df'
  primary-fixed-dim: '#f3b7c1'
  on-primary-fixed: '#331019'
  on-primary-fixed-variant: '#663a43'
  secondary-fixed: '#bceddc'
  secondary-fixed-dim: '#a1d0c1'
  on-secondary-fixed: '#002019'
  on-secondary-fixed-variant: '#214e43'
  tertiary-fixed: '#e1e1f5'
  tertiary-fixed-dim: '#c5c5d8'
  on-tertiary-fixed: '#191b29'
  on-tertiary-fixed-variant: '#444655'
  background: '#fbf9f5'
  on-background: '#1b1c1a'
  surface-variant: '#e4e2de'
typography:
  display-lg:
    fontFamily: Quicksand
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Quicksand
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
  headline-lg-mobile:
    fontFamily: Quicksand
    fontSize: 28px
    fontWeight: '700'
    lineHeight: 36px
  headline-md:
    fontFamily: Quicksand
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  body-lg:
    fontFamily: Nunito Sans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Nunito Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-md:
    fontFamily: Nunito Sans
    fontSize: 14px
    fontWeight: '700'
    lineHeight: 20px
    letterSpacing: 0.05em
  label-sm:
    fontFamily: Nunito Sans
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
rounded:
  sm: 0.5rem
  DEFAULT: 1rem
  md: 1.5rem
  lg: 2rem
  xl: 3rem
  full: 9999px
spacing:
  unit: 8px
  container-margin: 24px
  gutter: 16px
  element-gap-sm: 8px
  element-gap-md: 16px
  element-gap-lg: 32px
---

## Brand & Style
The design system is built to evoke a sense of digital "slow living." It transforms the screen into a tactile playground inspired by high-end stationery, boutique wax melting studios, and artisanal toy workshops. The target audience seeks a sanctuary for stress relief, sensory stimulation, and creative play.

The visual style is a hybrid of **Neomorphism** and **Glassmorphism**, characterized by soft, "squishy" surfaces that look physically depressible. Surfaces should appear as if they are made of molded silicone, semi-translucent wax, or polished wood. The emotional response is one of safety, comfort, and tactile satisfaction—every interaction should feel like pressing into a soft, responsive material.

## Colors
The palette is anchored by "Strawberry Milk" (#FFC1CC), a primary accent that feels sweet and approachable. This is supported by "Creamy White" (#FDFBF7) for base surfaces, "Mint Green" (#B2E2D2) for success or growth-related elements, and "Lavender" (#E6E6FA) for secondary interactive highlights.

To ground the pastel airiness, warm wood tones are used sparingly for structural elements like shelves, toolbars, or "workshop" tables, providing a sense of stability and craftsmanship. Avoid pure blacks; use deep, warm grays or muted browns for text to maintain the soft aesthetic.

## Typography
The typography in this design system prioritizes friendliness and legibility. **Quicksand** is utilized for all display and headline roles, taking advantage of its rounded terminals to reinforce the "soft" brand character. **Nunito Sans** provides a slightly more structured but still warm experience for body text and functional labels.

For large display text, slight negative letter spacing is applied to create a tighter, more "molded" look. All body text should maintain generous line heights to ensure a relaxed, airy reading experience that doesn't overwhelm the user.

## Layout & Spacing
This design system utilizes a fluid grid with generous padding to create a sense of openness. Content is typically centered in "pods" or "bubbles" rather than edge-to-edge containers. 

For mobile, a 4-column layout with 24px side margins is standard. Desktop layouts expand to a 12-column grid but cap the content width at 1200px to maintain the "cozy workshop" feel. Spacing between elements should be loose; breathing room is essential to the healing nature of the app. Use a 8px-based rhythm for all padding and margins.

## Elevation & Depth
Depth is the core of this design system. It is achieved through **Dual-Shadow Neomorphism**:
- **Raised Elements:** Use a light highlight (white, 80% opacity) on the top-left and a soft shadow (primary color or warm gray, 15% opacity) on the bottom-right.
- **Sunken Elements:** For active states or input fields, reverse the shadows to make the element appear pressed into the background.

**Frosted Glass (Backdrop Blur)** is applied to overlays, modals, and navigation bars to mimic the appearance of translucent wax or milky plastic. This maintains the color context of the background while providing a clear surface for interaction.

## Shapes
Shapes are extremely organic and rounded. The design system avoids sharp corners entirely. Buttons and primary containers use a "Pill-shaped" or `3XL` rounding logic. Even standard cards should feel like smooth, tumbled stones or molded clay. 

Interactive elements should have a slight "bounce" in their physical shape—consider using slightly irregular, "squircle" shapes for icons and decorative containers to enhance the whimsical, handmade feel of the village.

## Components
- **Buttons:** Large, pill-shaped, and high-contrast. Use the "raised" neomorphic effect. On hover, the highlight should brighten; on click, the button should transition to a "sunken" state with a haptic-like visual shift.
- **Chips & Tags:** Small, semi-transparent frosted glass pills. Used for categories like "Sparkly," "Matte," or "Scented."
- **Input Fields:** Sunken wells with soft inner shadows. The cursor should be the Primary Strawberry Pink.
- **Cards:** Large containers with `rounded-xl` corners. Use a very subtle border (1px, low opacity white) to define edges on top of the soft background shadows.
- **The "Wax Melter" Toggle:** A custom radio/switch component that looks like a physical slider on a wooden base.
- **Progress Bars:** Designed to look like a glass tube filling with colored liquid wax, including a subtle "glitter" overlay for the filled portion.
- **Modals:** Centered overlays with heavy backdrop blur (20px+) and a soft entrance animation that feels like a bubble expanding.