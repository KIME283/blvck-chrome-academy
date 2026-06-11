---
name: Obsidian & Acid
colors:
  surface: '#121414'
  surface-dim: '#121414'
  surface-bright: '#37393a'
  surface-container-lowest: '#0c0f0f'
  surface-container-low: '#1a1c1c'
  surface-container: '#1e2020'
  surface-container-high: '#282a2b'
  surface-container-highest: '#333535'
  on-surface: '#e2e2e2'
  on-surface-variant: '#c4c7c7'
  inverse-surface: '#e2e2e2'
  inverse-on-surface: '#2f3131'
  outline: '#8e9192'
  outline-variant: '#444748'
  surface-tint: '#c9c6c5'
  primary: '#c9c6c5'
  on-primary: '#313030'
  primary-container: '#050505'
  on-primary-container: '#797777'
  inverse-primary: '#5f5e5e'
  secondary: '#fcffdd'
  on-secondary: '#2c3400'
  secondary-container: '#cfed00'
  on-secondary-container: '#5b6900'
  tertiary: '#ffaed8'
  on-tertiary: '#610045'
  tertiary-container: '#12000a'
  on-tertiary-container: '#e000a4'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#e5e2e1'
  primary-fixed-dim: '#c9c6c5'
  on-primary-fixed: '#1c1b1b'
  on-primary-fixed-variant: '#474646'
  secondary-fixed: '#d2f006'
  secondary-fixed-dim: '#b8d300'
  on-secondary-fixed: '#191e00'
  on-secondary-fixed-variant: '#414c00'
  tertiary-fixed: '#ffd8e9'
  tertiary-fixed-dim: '#ffaed8'
  on-tertiary-fixed: '#3c0029'
  on-tertiary-fixed-variant: '#890063'
  background: '#121414'
  on-background: '#e2e2e2'
  surface-variant: '#333535'
typography:
  display-xl:
    fontFamily: Syne
    fontSize: 120px
    fontWeight: '800'
    lineHeight: 100px
    letterSpacing: -0.04em
  display-xl-mobile:
    fontFamily: Syne
    fontSize: 64px
    fontWeight: '800'
    lineHeight: 60px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Syne
    fontSize: 64px
    fontWeight: '700'
    lineHeight: 72px
    letterSpacing: -0.02em
  headline-lg-mobile:
    fontFamily: Syne
    fontSize: 40px
    fontWeight: '700'
    lineHeight: 44px
  headline-md:
    fontFamily: Syne
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
  body-lg:
    fontFamily: Hanken Grotesk
    fontSize: 20px
    fontWeight: '400'
    lineHeight: 32px
    letterSpacing: 0.01em
  body-md:
    fontFamily: Hanken Grotesk
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-caps:
    fontFamily: JetBrains Mono
    fontSize: 14px
    fontWeight: '500'
    lineHeight: 20px
    letterSpacing: 0.1em
spacing:
  unit: 8px
  gutter: 24px
  margin-desktop: 64px
  margin-mobile: 20px
  section-gap: 160px
---

## Brand & Style

This design system embodies a "Luxury Brutalist" aesthetic—a high-tension intersection between elite hair artistry and underground creative energy. It is designed for a dual audience: high-end clientele seeking a transformative experience and professional stylists looking for vanguard education.

The visual language is characterized by **maximalist scale** and **rebellious precision**. It rejects the typical "zen" spa aesthetic in favor of a high-energy, editorial atmosphere. Key styling pillars include:
- **Kinetic Overlays:** Layouts that use absolute positioning to overlap typography onto high-resolution photography.
- **Chrome & Depth:** Utilization of metallic textures and liquid-metal accents to contrast against flat, matte surfaces.
- **Aggressive Whitespace:** Large "dead zones" of deep obsidian to make the vibrant accents feel more explosive.
- **Intentional Friction:** Using heavy borders and raw, unpolished layout structures to signal an "underground" but premium status.

## Colors

The palette is built on a foundation of **Obsidian (#050505)**, providing a void-like depth that allows the neon accents to vibrate.

- **Primary (Obsidian):** Used for 90% of surfaces to maintain a luxury, high-end feel.
- **Secondary (Acid Green - #E0FF25):** The "action" color. Used for high-priority CTAs, training-specific alerts, and navigational highlights.
- **Tertiary (Electric Pink - #FF2EBD):** The "artistry" color. Used for artistic showcases, salon services, and secondary interactive elements.
- **Neutral (Stark White):** Reserved strictly for body copy and critical technical information to ensure legibility against the dark background.
- **Chrome/Metallic:** Implemented as a CSS gradient or texture overlay for borders and specialized UI cards to simulate high-end salon hardware.

## Typography

The typography strategy relies on extreme contrast in width and personality.

- **Headlines (Syne):** Chosen for its eccentric, ultra-wide architecture. For `display-xl`, the font should be set with tight kerning to create a "block" of text effect. Use `700` or `800` weights for maximum impact.
- **Body (Hanken Grotesk):** Provides a clean, contemporary, and wide-set sans-serif balance. It ensures the "luxury" aspect isn't lost in the "brutalist" headlines.
- **Technical Accents (JetBrains Mono):** Used for hair-level specifications, prices, and training dates to evoke a "scientific" or "manual" aesthetic.
- **Treatment:** Headlines should frequently use `text-stroke` or `outline` styles when overlapping imagery to maintain the maximalist feel.

## Layout & Spacing

The layout follows a **Strict Fluid Grid** but intentionally breaks it with "floating" elements.

- **Grid System:** A 12-column grid on desktop with a heavy 64px outer margin.
- **Section Gaps:** Significant vertical breathing room (160px+) between major sections to prevent the maximalist elements from feeling cluttered.
- **Asymmetry:** Content blocks should be offset. If text is in columns 1-6, the accompanying image should occupy columns 7-12 but be vertically shifted by 40-80px.
- **Mobile:** Transition to a 4-column grid. Remove horizontal overlaps to maintain vertical legibility, but retain the large-scale typography.

## Elevation & Depth

This design system avoids traditional soft shadows. Instead, depth is achieved through **Hard Layering** and **Material Contrast**:

- **Tonal Layers:** Use `Primary-Lighter` (a very dark charcoal) to distinguish cards from the obsidian background.
- **Heavy Borders:** Instead of shadows, use 2px or 3px solid borders. For "elevated" elements like hover states, use the **Acid Green** or **Chrome** as the border color.
- **Backdrop Blurs:** Use high-intensity blurs (30px+) behind navigation bars and overlays to create a "glass-on-void" effect.
- **Z-Index Play:** Text should frequently "stack" behind or in front of cropped photography of hair textures to create a 3D collage effect.

## Shapes

The shape language is **Strictly Geometric and Sharp**.

- **Corners:** 0px radius across all buttons, inputs, and image containers. This reinforces the "Brutalist" and "cutting-edge" (pun intended) nature of the salon.
- **Dividers:** Use thick (4px+) horizontal lines to separate sections, occasionally using the **Electric Pink** color for these strokes.
- **Masking:** Use sharp, diagonal masks for images (e.g., 45-degree cuts) to suggest movement and precision.

## Components

### Buttons
- **Primary:** Stark White background, Obsidian text, 0px radius. On hover, shifts to **Acid Green** background with a "glitch" or "slide" transition.
- **Secondary:** Transparent with a 2px **Electric Pink** border. Text in White.

### Input Fields
- Underline style only. A 2px White bottom border that turns **Acid Green** on focus. Labels use the `label-caps` typography style.

### Cards (Course/Service)
- No shadows. Solid 1px Obsidian-Light border. Images within cards should have a subtle "grain" or "noise" filter. On hover, the image scales slightly and a color-burn overlay of **Electric Pink** appears.

### Chips/Tags
- Small, rectangular blocks using `JetBrains Mono`. Background is Obsidian-Lighter with the text in the secondary or tertiary accent color.

### Image Carousels
- Navigation arrows should be oversized and placed at the edges of the screen, utilizing the **Chrome** metallic effect for the icons.