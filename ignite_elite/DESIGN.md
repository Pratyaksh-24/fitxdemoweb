---
name: Ignite Elite
colors:
  surface: '#131313'
  surface-dim: '#131313'
  surface-bright: '#3a3939'
  surface-container-lowest: '#0e0e0e'
  surface-container-low: '#1c1b1b'
  surface-container: '#201f1f'
  surface-container-high: '#2a2a2a'
  surface-container-highest: '#353534'
  on-surface: '#e5e2e1'
  on-surface-variant: '#e4beb4'
  inverse-surface: '#e5e2e1'
  inverse-on-surface: '#313030'
  outline: '#ab8980'
  outline-variant: '#5b4039'
  surface-tint: '#ffb5a0'
  primary: '#ffb5a0'
  on-primary: '#5f1500'
  primary-container: '#ff5722'
  on-primary-container: '#541200'
  inverse-primary: '#b02f00'
  secondary: '#8dcdff'
  on-secondary: '#00344f'
  secondary-container: '#00affe'
  on-secondary-container: '#003f5f'
  tertiary: '#86cfff'
  on-tertiary: '#00344c'
  tertiary-container: '#019ad8'
  on-tertiary-container: '#002d43'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#ffdbd1'
  primary-fixed-dim: '#ffb5a0'
  on-primary-fixed: '#3b0900'
  on-primary-fixed-variant: '#862200'
  secondary-fixed: '#cae6ff'
  secondary-fixed-dim: '#8dcdff'
  on-secondary-fixed: '#001e30'
  on-secondary-fixed-variant: '#004b70'
  tertiary-fixed: '#c8e6ff'
  tertiary-fixed-dim: '#86cfff'
  on-tertiary-fixed: '#001e2e'
  on-tertiary-fixed-variant: '#004c6d'
  background: '#131313'
  on-background: '#e5e2e1'
  surface-variant: '#353534'
typography:
  display-lg:
    fontFamily: Archivo Narrow
    fontSize: 72px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Archivo Narrow
    fontSize: 48px
    fontWeight: '700'
    lineHeight: '1.2'
  headline-md:
    fontFamily: Archivo Narrow
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.2'
  headline-sm:
    fontFamily: Archivo Narrow
    fontSize: 24px
    fontWeight: '600'
    lineHeight: '1.3'
  body-lg:
    fontFamily: Hanken Grotesk
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Hanken Grotesk
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-lg:
    fontFamily: Hanken Grotesk
    fontSize: 14px
    fontWeight: '600'
    lineHeight: '1.2'
    letterSpacing: 0.05em
  headline-lg-mobile:
    fontFamily: Archivo Narrow
    fontSize: 36px
    fontWeight: '700'
    lineHeight: '1.1'
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  base: 8px
  container-max: 1280px
  gutter: 24px
  margin-mobile: 16px
  margin-desktop: 48px
  stack-sm: 12px
  stack-md: 24px
  stack-lg: 48px
---

## Brand & Style

The design system is engineered for a premium, high-octane fitness experience. It targets the "elite" athlete—individuals who view fitness not just as a hobby, but as a disciplined lifestyle. The aesthetic is a fusion of **Industrial Modernism** and **Glassmorphism**, creating an environment that feels both grounded in grit and elevated by technology.

The UI evokes a sense of "pre-workout adrenaline": dark, focused, and intense. By utilizing deep obsidian surfaces punctuated by "Electric Blue" and "FITX Orange" accents, the system maintains a high-visibility, high-energy atmosphere. Visual depth is achieved through translucent glass layers and subtle 3D transformations, mimicking the high-tech interface of premium gym equipment and performance-tracking wearables.

## Colors

The palette is anchored in a triple-black architecture. The base layer is **Deep Black (#0a0a0a)**, providing an infinite canvas that emphasizes focus. Secondary surfaces use a slightly lighter charcoal to define containers without breaking the dark immersion.

**Accents:**
- **FITX Orange (#ff5722):** Used for primary calls to action, progress indicators, and "active" states. It represents heat, energy, and effort.
- **Electric Blue (#00b0ff):** Used for technical data, performance metrics, and secondary interactive elements. It represents recovery, technology, and precision.

**Functional Colors:**
- **Grays:** A scale of cool, sophisticated grays is used for borders and secondary text to maintain a premium industrial feel.
- **Gradients:** Use linear gradients (e.g., `#ff5722` to `#ff8a65`) sparingly on large buttons or background glows to add a "molten" or "neon" depth.

## Typography

This design system utilizes a high-contrast typographic hierarchy to ensure information is digestible during intense activity.

- **Headlines:** `Archivo Narrow` is the core identity font. Its condensed nature allows for massive, impactful headlines that mirror the strength and efficiency of an industrial gym space. All major headers should be set in **Uppercase** to convey authority and energy.
- **Body:** `Hanken Grotesk` provides a modern, clean, and highly legible counterpoint. Its open apertures and contemporary proportions maintain the "premium tech" feel while ensuring workout descriptions and stats are easy to read at a glance.
- **Labels:** Small labels and tags should utilize increased letter-spacing and semi-bold weights for maximum clarity on dark backgrounds.

## Layout & Spacing

The layout philosophy follows a **Fixed-Fluid Hybrid** model. While the central content container is capped for readability on wide displays, internal components utilize a fluid grid to maximize visual impact.

**Grid System:**
- **Desktop:** 12-column grid with a 24px gutter. Large sections should utilize wide margins to create "breathing room" for the bold typography.
- **Mobile:** 4-column grid with 16px margins. Content is primarily stacked to facilitate one-handed navigation during workouts.

**Spacing Rhythm:**
A strict 8px base unit ensures mathematical harmony. Use larger vertical stacks (`stack-lg`) between distinct training programs or sections to allow the dark aesthetic to feel luxurious rather than cramped.

## Elevation & Depth

Depth in this design system is created through light, not shadows.

- **Glassmorphism:** Secondary panels and navigation bars use a background blur (20px) with a semi-transparent fill (`rgba(255, 255, 255, 0.05)`). This creates a "frosted tech" appearance.
- **Outer Glows:** Instead of traditional black shadows, elevated elements (like active cards) use subtle colored outer glows (10-15% opacity of the primary or secondary accent color).
- **Thin Borders:** Layers are separated by 1px "ghost borders" in a light gray or semi-transparent white. This reinforces the industrial, precision-milled aesthetic.
- **3D Interaction:** Cards and buttons should utilize a slight `scale(1.02)` and `rotateX/rotateY` tilt on hover to simulate physical depth and responsiveness.

## Shapes

The shape language is "Soft-Industrial." While the aesthetic is rugged, the corners are slightly rounded to feel modern and high-end.

- **Primary Elements:** Buttons and standard cards use a `0.25rem` (4px) radius. This sharp-but-not-piercing corner style reflects precision equipment.
- **Data Points:** Small chips and status tags may use a `rounded-xl` (pill shape) to differentiate meta-data from structural content.
- **Visual Accents:** Use 45-degree diagonal cuts or "clipped corners" on decorative containers to reinforce the energetic, aerodynamic fitness theme.

## Components

### Buttons
- **Primary:** Solid FITX Orange background, black text (Archivo Narrow Bold), 4px radius. 3D transform on hover.
- **Secondary:** Transparent background with a 1px Electric Blue border and Electric Blue text.
- **Ghost:** Text only with an underline or arrow icon that appears on hover.

### Cards
- **Program Cards:** High-quality imagery with a dark gradient overlay at the bottom. Headlines appear in Archivo Narrow. On hover, the image should slightly zoom while the card tilts toward the cursor.
- **Glass Cards:** Used for statistics or technical data. Blurred background, white thin border, and vibrant blue accents for data points.

### Inputs & Form Fields
- Dark gray background (`#1a1a1a`) with a 1px bottom-only border. Border glows FITX Orange upon focus. Labels are uppercase Hanken Grotesk.

### Chips & Badges
- Small, uppercase, letter-spaced text inside a semi-transparent dark container. Used for difficulty levels (e.g., "ADVANCED", "RECOVERY").

### Progress Indicators
- Linear bars using the Electric Blue to FITX Orange gradient to signify intensity or completion.