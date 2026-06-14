---
name: Sacred Devotional Aesthetic
colors:
  surface: '#fff8f5'
  surface-dim: '#e1d8d4'
  surface-bright: '#fff8f5'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#fbf2ed'
  surface-container: '#f5ece7'
  surface-container-high: '#efe6e2'
  surface-container-highest: '#e9e1dc'
  on-surface: '#1e1b18'
  on-surface-variant: '#554336'
  inverse-surface: '#34302c'
  inverse-on-surface: '#f8efea'
  outline: '#887364'
  outline-variant: '#dbc2b0'
  surface-tint: '#8f4e00'
  primary: '#8f4e00'
  on-primary: '#ffffff'
  primary-container: '#ff9933'
  on-primary-container: '#693800'
  inverse-primary: '#ffb77a'
  secondary: '#735c00'
  on-secondary: '#ffffff'
  secondary-container: '#fed65b'
  on-secondary-container: '#745c00'
  tertiary: '#5d5f5f'
  on-tertiary: '#ffffff'
  tertiary-container: '#b1b2b2'
  on-tertiary-container: '#434545'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffdcc2'
  primary-fixed-dim: '#ffb77a'
  on-primary-fixed: '#2e1500'
  on-primary-fixed-variant: '#6d3a00'
  secondary-fixed: '#ffe088'
  secondary-fixed-dim: '#e9c349'
  on-secondary-fixed: '#241a00'
  on-secondary-fixed-variant: '#574500'
  tertiary-fixed: '#e2e2e2'
  tertiary-fixed-dim: '#c6c6c7'
  on-tertiary-fixed: '#1a1c1c'
  on-tertiary-fixed-variant: '#454747'
  background: '#fff8f5'
  on-background: '#1e1b18'
  surface-variant: '#e9e1dc'
typography:
  display-lg:
    fontFamily: EB Garamond
    fontSize: 48px
    fontWeight: '600'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: EB Garamond
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.2'
  headline-lg-mobile:
    fontFamily: EB Garamond
    fontSize: 28px
    fontWeight: '600'
    lineHeight: '1.2'
  headline-md:
    fontFamily: EB Garamond
    fontSize: 24px
    fontWeight: '500'
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
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '600'
    lineHeight: '1.2'
    letterSpacing: 0.05em
  caption:
    fontFamily: Plus Jakarta Sans
    fontSize: 12px
    fontWeight: '400'
    lineHeight: '1.4'
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  base: 8px
  container-max: 1200px
  gutter: 24px
  margin-mobile: 16px
  stack-sm: 8px
  stack-md: 16px
  stack-lg: 32px
  section-gap: 80px
---

## Brand & Style
The visual identity of the design system is rooted in reverence, tradition, and the artisanal beauty of Indian devotional items. It balances the warmth of spiritual practice with the precision of a high-end boutique. 

The design style is **Elegant Traditionalism**. It moves away from flat, sterile digital trends in favor of a tactile, layered experience that reflects the textures of silk, brass, and gold. While the layout remains clean and functional to ensure trust and ease of purchase, the atmosphere is enriched with subtle ornamental motifs and a warm, inviting color palette. The goal is to evoke a sense of "Shubh" (auspiciousness) and beauty, making the act of shopping feel like a part of the ritual itself.

## Colors
The palette is centered on sacred hues that represent purity and divinity:
- **Primary (Saffron):** Used for primary actions, highlights, and status indicators. It represents the flame of the diya and spiritual energy.
- **Secondary (Gold):** Used for ornamentation, borders, and premium iconography. This should be applied with restraint to maintain elegance, often as a metallic gradient or a fine stroke.
- **Neutral (Charcoal/Umber):** Deep, warm neutrals are used for typography to ensure readability without the harshness of pure black.
- **Surface (White & Cream):** Generous use of white space is complemented by very light cream or saffron-tinted backgrounds for secondary containers to provide a soft, "parchment" feel.

## Typography
The typography system pairs the historical authority of a classic serif with the clarity of a contemporary sans-serif.

- **Headlines:** Uses **EB Garamond**. This typeface brings a literary, timeless quality to product titles and section headers. High-level displays should use Medium or SemiBold weights to anchor the page.
- **Body & UI:** Uses **Plus Jakarta Sans**. Its soft, rounded terminals echo the friendly and approachable nature of the brand while remaining highly legible for product descriptions and checkout flows.
- **Labels:** Small labels and price tags use uppercase Sans with increased letter spacing to provide a modern "editorial" look that contrasts with the fluid serif headers.

## Layout & Spacing
The layout follows a **Fixed Grid** model on desktop to preserve the aspect ratio of intricate product photography, centering the content at a maximum width of 1200px. 

- **Vertical Rhythm:** A strict 8px baseline grid ensures harmony between elements. Large section gaps (80px+) are encouraged to allow the traditional motifs and high-quality imagery to "breathe."
- **Grid:** A 12-column system is used for desktop, collapsing to 4 columns on mobile. 
- **Product Tiles:** Use a generous 24px gutter to prevent visual clutter, as devotional items often have high detail.
- **Responsive Behavior:** On mobile, margins reduce to 16px, and stack spacing is tightened, but the serif headlines maintain their prominence to keep the brand voice consistent.

## Elevation & Depth
Depth is communicated through **Tonal Layering** and soft, ambient shadows that mimic natural light falling on fabric or metal.

- **Surfaces:** Main backgrounds use #FFFFFF. Secondary areas like filters or footers use a subtle Saffron-tinted cream (#FFF9F2).
- **Shadows:** Avoid harsh, black shadows. Use low-opacity Umber tints (#2D2926 at 8% opacity) with a large blur radius to create a "floating" effect for cards.
- **Depth Motifs:** Incorporate semi-transparent Mandala or floral patterns (5% opacity) on background layers. These should feel like watermarks or fabric textures rather than active UI elements.
- **Glassmorphism:** Use subtle background blurs on sticky navigation bars to maintain context while keeping the spiritual aesthetic modern.

## Shapes
The shape language is **Soft** and architectural.
- **Corners:** A standard 4px (0.25rem) radius is used for most UI components (cards, inputs). This is enough to remove the "sharpness" of digital boxes without becoming overly bubbly or informal.
- **Circular Accents:** Profile images, price badges, and specific action icons (like "Add to Wishlist") should use full pill/circle shapes to create a visual counterpoint to the rectangular grid.
- **Ornamental Borders:** Special containers or product detail highlights may feature a "Double Border" (a thin 1px Saffron line inside a thicker Gold line) to signify premium quality.

## Components
- **Buttons:** Primary buttons are solid Saffron with White text, using a Medium weight. Secondary buttons use a Gold 1px border with a subtle inner glow. 
- **Cards:** Product cards use a white background with a very fine Gold border (0.5px) and no shadow by default, gaining a soft shadow on hover.
- **Inputs:** Text fields use a light cream background with a Saffron bottom-border focus state. Labels are always positioned above the field in uppercase Jakarta Sans.
- **Chips:** Used for sizing (e.g., for Laddu Gopal dresses) or categories. They feature a light saffron fill with a darker saffron text, using the "Soft" corner radius.
- **Icons:** Use thin-stroke, monolinear icons. Where possible, incorporate custom devotional icons (bells, lotus, incense) styled with a Gold tint.
- **Dividers:** Instead of plain lines, use a thin horizontal line that terminates in a small Gold dot or a tiny floral motif in the center.