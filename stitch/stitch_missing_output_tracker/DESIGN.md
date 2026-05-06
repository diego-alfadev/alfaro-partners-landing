---
name: Digital Obsidian
colors:
  surface: '#131314'
  surface-dim: '#131314'
  surface-bright: '#39393a'
  surface-container-lowest: '#0e0e0f'
  surface-container-low: '#1c1b1c'
  surface-container: '#201f20'
  surface-container-high: '#2a2a2b'
  surface-container-highest: '#353435'
  on-surface: '#e5e2e2'
  on-surface-variant: '#c6c6cc'
  inverse-surface: '#e5e2e2'
  inverse-on-surface: '#313031'
  outline: '#8f9096'
  outline-variant: '#45474b'
  surface-tint: '#c2c6d4'
  primary: '#c2c6d4'
  on-primary: '#2b313b'
  primary-container: '#060b14'
  on-primary-container: '#757a86'
  inverse-primary: '#595e6a'
  secondary: '#e9c349'
  on-secondary: '#3c2f00'
  secondary-container: '#af8d11'
  on-secondary-container: '#342800'
  tertiary: '#dbc2b1'
  on-tertiary: '#3d2d21'
  tertiary-container: '#130802'
  on-tertiary-container: '#8a7667'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#dee2f0'
  primary-fixed-dim: '#c2c6d4'
  on-primary-fixed: '#161c25'
  on-primary-fixed-variant: '#424752'
  secondary-fixed: '#ffe088'
  secondary-fixed-dim: '#e9c349'
  on-secondary-fixed: '#241a00'
  on-secondary-fixed-variant: '#574500'
  tertiary-fixed: '#f8decc'
  tertiary-fixed-dim: '#dbc2b1'
  on-tertiary-fixed: '#26190e'
  on-tertiary-fixed-variant: '#554336'
  background: '#131314'
  on-background: '#e5e2e2'
  surface-variant: '#353435'
typography:
  display-xl:
    fontFamily: Noto Serif
    fontSize: 72px
    fontWeight: '400'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Noto Serif
    fontSize: 48px
    fontWeight: '400'
    lineHeight: '1.2'
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Noto Serif
    fontSize: 32px
    fontWeight: '400'
    lineHeight: '1.3'
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
    letterSpacing: 0.01em
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-caps:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '600'
    lineHeight: '1'
    letterSpacing: 0.15em
spacing:
  unit: 8px
  container-max: 1440px
  gutter: 32px
  margin-edge: 64px
  section-gap: 160px
---

## Brand & Style

This design system is engineered for a boutique real estate firm catering to high-net-worth individuals. The brand personality is rooted in discretion, precision, and absolute authority. It evokes the atmosphere of a private family office or an elite global law firm—places where silence speaks louder than noise.

The visual style is **Minimalist Glassmorphism**. It utilizes deep, dark layers to create a sense of infinite physical depth, mimicking the properties of polished obsidian. Every interface element is treated as a high-precision instrument. The user experience is defined by generous whitespace, creating a "gallery" effect for luxury property listings, and sophisticated micro-interactions that respond with dampened, hydraulic-like smoothness.

## Colors

The palette is anchored in **Abyss Navy**, providing a foundation of stability and infinite depth. **Metallic Gold** is reserved strictly for high-value actions and critical brand moments, acting as a beacon of prestige. 

**Platinum Silver** serves as the functional workhorse for secondary information, ensuring legibility without competing with the primary **Pure White** headlines. To maintain the "Digital Obsidian" aesthetic, background glows should use a desaturated navy radial gradient (#0A121E to #060B14) to subtly illuminate content areas without breaking the dark-mode immersion.

## Typography

The typographic strategy juxtaposes traditional authority with modern efficiency. **Noto Serif** (substituting for Playfair Display) provides a literary, established feel for headlines, conveying heritage and trust. It should be used with generous leading and slight negative tracking in large formats to feel "tight" and editorial.

**Inter** handles all functional data and body copy. It is selected for its neutral, systematic character, ensuring that complex property details remain highly legible. The "Label-Caps" style is essential for navigational elements and small descriptors, providing a rhythmic, architectural feel to the layout.

## Layout & Spacing

The layout follows a **Fixed Grid** philosophy within a 1440px container, prioritizing white space as a luxury asset. Spacing follows a strict 8px linear scale. 

- **Section Gaps:** Use 160px (20 units) between major content sections to allow the design to "breathe."
- **Margins:** Broad 64px side margins ensure content never feels crowded, maintaining a boutique, exclusive feel.
- **Vertical Rhythm:** Content blocks should favor asymmetrical alignments to mimic high-end architectural plans, moving away from standard centered "web" layouts.

## Elevation & Depth

Depth is not achieved through shadows, but through **transparency and blur**. 

1.  **Base Layer:** The Abyss Navy background, occasionally broken by extremely large, soft radial glows (opacity 5-10%).
2.  **Mid Layer (Glass):** Surfaces use a 10px-20px Backdrop Blur with a 3% white fill. This creates a "frosted obsidian" look.
3.  **Borders:** Every glass element is defined by a 1px solid border of Platinum Silver at 10% opacity. This "whisper-thin" line is the hallmark of the system’s precision.
4.  **Active State:** When an element is engaged, its border opacity increases to 30%, and a faint Gold inner-glow may be applied.

## Shapes

The design system utilizes **Sharp (0px)** corners for all primary structural elements, containers, and buttons. This choice reinforces the "private bank" aesthetic—unyielding, precise, and masculine. 

Roundedness is only permitted for small UI indicators (like status pips) or specific iconography to provide a subtle organic contrast to the rigid architectural grid.

## Components

### Buttons & Actions
- **Primary:** Metallic Gold background with black text. Sharp corners. No shadows. On hover, a slight horizontal expansion or a subtle shimmer effect.
- **Secondary:** Transparent background with a 1px Platinum Silver border (20% opacity). White text. 

### Cards & Property Teasers
- Cards are defined by their 1px border and backdrop blur. 
- Imagery within cards should have a subtle desaturation filter that returns to full color on hover.
- Typography within cards must maintain high contrast (Pure White titles).

### Input Fields
- Underline-only or fully enclosed glass containers. 
- Labels use the "Label-Caps" style, floating above the input area.
- Focus state: Border transitions from 10% opacity silver to 100% opacity Gold.

### Navigation
- A persistent top-bar with a heavy backdrop blur. 
- Navigation items use Inter with high letter-spacing.
- Active states are marked by a simple 1px gold line beneath the text.

### Additional Components
- **Property Timeline:** A vertical, minimalist thread for tracking acquisition milestones.
- **Investment Gauges:** High-precision data visualizations using thin Platinum Silver lines and Gold data-points.