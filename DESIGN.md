---
name: Coastal Athletic Premium
colors:
  surface: '#f7f9fb'
  surface-dim: '#d8dadc'
  surface-bright: '#f7f9fb'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f2f4f6'
  surface-container: '#eceef0'
  surface-container-high: '#e6e8ea'
  surface-container-highest: '#e0e3e5'
  on-surface: '#191c1e'
  on-surface-variant: '#454652'
  inverse-surface: '#2d3133'
  inverse-on-surface: '#eff1f3'
  outline: '#767683'
  outline-variant: '#c6c5d4'
  surface-tint: '#4c56af'
  primary: '#000666'
  on-primary: '#ffffff'
  primary-container: '#1a237e'
  on-primary-container: '#8690ee'
  inverse-primary: '#bdc2ff'
  secondary: '#006876'
  on-secondary: '#ffffff'
  secondary-container: '#69e8fe'
  on-secondary-container: '#006774'
  tertiary: '#390a00'
  on-tertiary: '#ffffff'
  tertiary-container: '#5d1600'
  on-tertiary-container: '#f96b3f'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#e0e0ff'
  primary-fixed-dim: '#bdc2ff'
  on-primary-fixed: '#000767'
  on-primary-fixed-variant: '#343d96'
  secondary-fixed: '#9eefff'
  secondary-fixed-dim: '#55d7ed'
  on-secondary-fixed: '#001f24'
  on-secondary-fixed-variant: '#004e59'
  tertiary-fixed: '#ffdbd0'
  tertiary-fixed-dim: '#ffb59f'
  on-tertiary-fixed: '#3a0a00'
  on-tertiary-fixed-variant: '#852300'
  background: '#f7f9fb'
  on-background: '#191c1e'
  surface-variant: '#e0e3e5'
  ocean-depth: '#1A237E'
  vibrant-bay: '#00ACC1'
  protein-coral: '#FF7043'
  shore-white: '#FFFFFF'
  glass-fill: rgba(255, 255, 255, 0.7)
typography:
  headline-xl:
    fontFamily: Montserrat
    fontSize: 48px
    fontWeight: '800'
    lineHeight: 56px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Montserrat
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
  headline-lg-mobile:
    fontFamily: Montserrat
    fontSize: 28px
    fontWeight: '700'
    lineHeight: 36px
  headline-md:
    fontFamily: Montserrat
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  body-lg:
    fontFamily: Hanken Grotesk
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Hanken Grotesk
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-caps:
    fontFamily: JetBrains Mono
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.1em
  protein-stat:
    fontFamily: Montserrat
    fontSize: 20px
    fontWeight: '800'
    lineHeight: 24px
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  base: 8px
  gutter: 24px
  margin-mobile: 16px
  margin-desktop: 64px
  section-gap: 80px
  stack-sm: 12px
  stack-md: 24px
---

## Brand & Style

The design system embodies a "Coastal Modern" aesthetic—a high-energy fusion of Kakinada’s seaside soul and elite athletic performance. It is designed to feel fresh, local, and undeniably premium, positioning high-protein nutrition as an aspirational lifestyle choice rather than a chore.

The visual style is **Modern Corporate with Glassmorphism influences**. It prioritizes high-quality food photography and expansive whitespace to emphasize the "farm-fresh" aspect of the product. UI elements utilize deep, oceanic depths contrasted against vibrant, sun-drenched accents to create a sense of movement and vitality. 

Key visual principles include:
- **Breathable Layouts:** Significant negative space to reflect the openness of the bay.
- **Glassmorphic Layers:** Translucent surfaces that mimic the condensation on a cold smoothie jar.
- **Athletic Energy:** High-contrast color pairings and bold, rhythmic typography that mirrors the intensity of a workout.

## Colors

The palette is anchored by **Deep Indigo (#1A237E)**, representing the depth of the ocean and the reliability of the brand. **Vibrant Cyan (#00ACC1)** serves as the secondary energy source, used for progress indicators, health-related icons, and secondary actions.

**Coral (#FF7043)** is the "Punchy" accent reserved exclusively for Primary CTAs and high-priority conversion points, ensuring it stands out against the cool-toned background. 

The background should primarily be **Shore White (#FFFFFF)** to maintain a clean, clinical (yet appetizing) feel. For depth, use the Neutral shade for sectioning and "Glass Fill" for translucent card backgrounds over photography.

## Typography

The typography strategy focuses on "Athletic Authority." **Montserrat** is used for all headlines in bold and extra-bold weights to convey strength and confidence. **Hanken Grotesk** provides a clean, modern, and highly legible experience for body copy and nutritional details.

A specialized label style using **JetBrains Mono** is introduced for technical data, such as protein counts and ingredient lists, giving the brand a "precise formula" feel. 

Headlines should use tight letter-spacing to feel impactful, while body text maintains generous line-height for readability during mobile browsing. All pricing and "grams of protein" metrics should be emphasized using the `protein-stat` or headline styles.

## Layout & Spacing

This design system utilizes a **Fluid Grid** model to ensure the "Shore" aesthetic feels expansive on any device. 

- **Desktop:** 12-column grid with 64px margins and 24px gutters. Content is often centered with significant horizontal whitespace to drive focus toward product photography.
- **Mobile:** 4-column grid with 16px margins. 
- **Rhythm:** An 8px base unit governs all internal spacing. Vertical "Stack" tokens (12px/24px) are used for grouping related content like product names and their protein stats.

Section gaps are intentionally large (80px+) to prevent the interface from feeling cluttered, maintaining the "Coastal Modern" airy vibe.

## Elevation & Depth

Hierarchy is established through **Glassmorphism** and **Tonal Layering** rather than traditional heavy shadows.

- **Surface Levels:** The base is Shore White. Floating elements (cards, menu items) use a "Glass" effect: a semi-transparent white fill (70% opacity) with a 16px backdrop blur and a subtle 1px border in a lighter tint of the Primary color.
- **Shadows:** When shadows are necessary for high-intensity interactions (like the primary "Order Now" button), use long, soft, ambient shadows tinted with the Primary Indigo (`rgba(26, 35, 126, 0.08)`).
- **Depth of Field:** Backgrounds behind glass layers should utilize high-quality, slightly blurred food photography to create a sense of environmental immersion.

## Shapes

The shape language is "Soft-Modern." All UI containers, buttons, and input fields utilize a **0.5rem (8px)** base radius, but primary cards and featured product images scale up to **rounded-xl (24px)** to mimic the smooth, organic curves of coastal pebbles or blended smoothies.

Buttons are never sharp; they should feel tactile and approachable. Icons should follow a "Line" style with rounded caps to match the roundedness of the containers.

## Components

### Buttons
- **Primary:** Coral background, white Montserrat Bold text. High elevation on hover. Used for "Add to Cart" and "Checkout."
- **Secondary:** Transparent with a 2px Indigo border. Used for "Learn More" or "View Ingredients."
- **Protein Badge:** A pill-shaped component with a Cyan background and white JetBrains Mono text, used to highlight "35g Protein" on product cards.

### Cards (Smoothie/Bowl Items)
Cards must use the Glassmorphism style. The top half is reserved for high-resolution photography with the product "bleeding" over the edge. The bottom half contains the title, a short description, and the protein stat prominently displayed.

### Input Fields
Clean, minimal outlines in a light gray-blue. On focus, the border transitions to Vibrant Cyan with a soft outer glow.

### Chips & Filters
Small, rounded-pill components used for menu categories (e.g., "High Protein," "Vegan," "Local Favorites"). Active states use a solid Indigo fill; inactive states use a subtle gray-blue ghost border.

### Lists (Menu View)
For the mobile "Formula" view, use a clean list with 16px internal padding, separated by thin 1px lines. Every list item must feature a circular thumbnail of the base flavor color (Yellow, Red, Green, Orange) to match the physical cart's color-coded system.