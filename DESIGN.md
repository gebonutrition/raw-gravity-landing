---
name: Nordic Equilibrium
colors:
  surface: '#fcf9f8'
  surface-dim: '#dcd9d9'
  surface-bright: '#fcf9f8'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f6f3f2'
  surface-container: '#f0eded'
  surface-container-high: '#eae7e7'
  surface-container-highest: '#e5e2e1'
  on-surface: '#1c1b1b'
  on-surface-variant: '#424844'
  inverse-surface: '#313030'
  inverse-on-surface: '#f3f0ef'
  outline: '#727973'
  outline-variant: '#c2c8c2'
  surface-tint: '#496455'
  primary: '#173124'
  on-primary: '#ffffff'
  primary-container: '#2d4739'
  on-primary-container: '#98b5a3'
  inverse-primary: '#b0cdbb'
  secondary: '#5d5f5f'
  on-secondary: '#ffffff'
  secondary-container: '#dcdddd'
  on-secondary-container: '#5f6161'
  tertiary: '#2c2c28'
  on-tertiary: '#ffffff'
  tertiary-container: '#42423e'
  on-tertiary-container: '#b0aea9'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ccead6'
  primary-fixed-dim: '#b0cdbb'
  on-primary-fixed: '#062014'
  on-primary-fixed-variant: '#324c3e'
  secondary-fixed: '#e2e2e2'
  secondary-fixed-dim: '#c6c6c7'
  on-secondary-fixed: '#1a1c1c'
  on-secondary-fixed-variant: '#454747'
  tertiary-fixed: '#e5e2dc'
  tertiary-fixed-dim: '#c9c6c1'
  on-tertiary-fixed: '#1c1c18'
  on-tertiary-fixed-variant: '#474743'
  background: '#fcf9f8'
  on-background: '#1c1b1b'
  surface-variant: '#e5e2e1'
typography:
  display-lg:
    fontFamily: Manrope
    fontSize: 64px
    fontWeight: '600'
    lineHeight: 72px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Manrope
    fontSize: 40px
    fontWeight: '600'
    lineHeight: 48px
    letterSpacing: -0.01em
  headline-lg-mobile:
    fontFamily: Manrope
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Manrope
    fontSize: 24px
    fontWeight: '500'
    lineHeight: 32px
    letterSpacing: 0em
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
    letterSpacing: 0em
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
    letterSpacing: 0em
  label-caps:
    fontFamily: JetBrains Mono
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: 0.05em
  button:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.01em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  unit: 8px
  container-max: 1280px
  gutter: 24px
  margin-desktop: 64px
  margin-mobile: 20px
  stack-sm: 8px
  stack-md: 16px
  stack-lg: 32px
  section-gap: 120px
---

## Brand & Style
The design system is rooted in the principles of Scandinavian minimalism—functionalism, simplicity, and a deep connection to the natural world. It targets a discerning audience that values scientific rigor as much as aesthetic tranquility. The UI must feel "breathable," utilizing expansive whitespace to reduce cognitive load and evoke a sense of calm authority.

The visual style is **Minimalist-Premium**, characterized by high-fidelity typography, a restricted organic palette, and a subtle tactile quality. It avoids unnecessary ornamentation, ensuring every element serves a functional purpose or reinforces the brand's credibility. The emotional response is one of effortless sophistication: the user should feel they are in a high-end clinic that happens to be located in a serene forest.

## Colors
The palette is a disciplined arrangement of neutrals and a single "Biophilic" accent.
- **Surface Layering:** Use `#FFFFFF` for the primary content canvas. Use `#F7F7F7` (Warm Light Gray) for secondary sections or background groupings to create soft structural separation.
- **Accentuation:** `#F2EFE9` (Soft Beige) is reserved for highlighting specific functional areas, such as call-out cards or unique tooltips, providing a subtle warmth against the cooler grays.
- **Action & Brand:** `#2D4739` (Natural Dark Green) is the sole primary action color. It represents vitality and scientific precision. Use it for primary buttons, active states, and critical data visualizations.
- **Typography:** Maintain a strict contrast ratio. Primary text uses `#1A1A1A` for maximum legibility, while secondary metadata and captions use `#666666`.

## Typography
The typography strategy creates a hierarchy of "Scientific Editorial." 
- **Manrope** is used for headlines to provide a modern, balanced, and premium feel. Headlines should use tighter letter spacing to maintain a cohesive visual block.
- **Inter** serves as the workhorse for body text, ensuring peak legibility for health data and long-form wellness content. 
- **JetBrains Mono** is introduced as a tertiary label font for technical data points, timestamps, and "scientific" metadata, reinforcing the brand's credibility.

Type should be set with generous vertical rhythm. Avoid "wall of text" layouts; use `display-lg` sparingly for high-impact hero moments.

## Layout & Spacing
This design system utilizes a **Fixed Grid** philosophy for desktop to maintain an editorial feel, transitioning to a **Fluid Grid** for mobile. 
- **The 8px Rhythm:** All spacing (padding, margins, gaps) must be a multiple of 8px.
- **Sectioning:** Vertical gaps between major content sections should be aggressive (`120px` or more) to enforce the "breathable" Scandinavian aesthetic.
- **Desktop:** 12-column grid, 1280px max-width, 24px gutters.
- **Mobile:** 4-column grid, 20px side margins, 16px gutters.
- **Safe Zones:** Content should never feel crowded against the edges of its container. Use `stack-lg` (32px) for internal card padding to maintain a premium, spacious feel.

## Elevation & Depth
Depth is conveyed through **Tonal Layers** and **Ambient Shadows** rather than traditional heavy dropshadows.
- **The Base:** The background is `#FFFFFF`.
- **Level 1 (Subtle Lift):** Used for cards and interactive containers. A very soft, diffused shadow: `0px 4px 20px rgba(0, 0, 0, 0.04)`.
- **Level 2 (Interactive/Floating):** Used for menus or active modals. A slightly more defined lift: `0px 12px 32px rgba(0, 0, 0, 0.08)`.
- **The "Glass" Effect:** For navigation bars or sticky headers, use a backdrop blur (20px) with a semi-transparent `#FFFFFF` (80% opacity) to maintain a sense of lightness and transparency.
- **Outlines:** Use a 1px border of `#F7F7F7` on all cards to provide definition even when shadows are minimal.

## Shapes
The shape language is "Softly Geometric."
- **Standard Radius:** 8px (`0.5rem`) for standard components like input fields and buttons.
- **Large Radius:** 16px (`1rem`) for primary content cards and images to evoke a friendlier, modern wellness feel.
- **Buttons:** Primary buttons should use the standard 8px radius to maintain a professional, structured appearance. Avoid fully pill-shaped buttons to stay aligned with the "Scientific" aspect of the brand.
- **Media:** Images should always carry the `rounded-lg` (16px) radius to soften the visual impact of photography.

## Components
- **Buttons:** Primary actions use `#2D4739` background with `#FFFFFF` text. Secondary actions use a ghost style with a `#1A1A1A` border or a simple text link with a 1px underline. High-tier buttons use `typography.button` tokens.
- **Input Fields:** Minimalist design with a 1px border of `#E5E5E5`. On focus, the border shifts to `#2D4739`. Use `body-md` for input text and `label-caps` for field titles.
- **Cards:** Utilize a `#FFFFFF` background, a `0.5rem` border radius, and the Level 1 Ambient Shadow. Internal padding is strictly `32px`.
- **Chips/Badges:** Use `#F2EFE9` (Soft Beige) as the background for status or category chips with `#2D4739` text to keep the look natural and low-contrast.
- **Lists:** Clean, border-bottom separation only (`1px solid #F7F7F7`). Icons in lists should be stroke-based (2px weight) and use the primary green color.
- **Data Visualization:** Line charts and progress rings should use `#2D4739` for the primary data line and `#F2EFE9` for the "track" or empty state.