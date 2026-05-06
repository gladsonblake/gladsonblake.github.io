---
name: Industrial Tech Portfolio
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
  on-surface-variant: '#45464d'
  inverse-surface: '#2d3133'
  inverse-on-surface: '#eff1f3'
  outline: '#76777e'
  outline-variant: '#c6c6ce'
  surface-tint: '#545e78'
  primary: '#000000'
  on-primary: '#ffffff'
  primary-container: '#101b31'
  on-primary-container: '#79849f'
  inverse-primary: '#bcc6e4'
  secondary: '#545f72'
  on-secondary: '#ffffff'
  secondary-container: '#d5e0f7'
  on-secondary-container: '#586377'
  tertiary: '#000000'
  on-tertiary: '#ffffff'
  tertiary-container: '#001f28'
  on-tertiary-container: '#0090b0'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d9e2ff'
  primary-fixed-dim: '#bcc6e4'
  on-primary-fixed: '#101b31'
  on-primary-fixed-variant: '#3c465f'
  secondary-fixed: '#d8e3fa'
  secondary-fixed-dim: '#bcc7dd'
  on-secondary-fixed: '#111c2c'
  on-secondary-fixed-variant: '#3c475a'
  tertiary-fixed: '#b7eaff'
  tertiary-fixed-dim: '#4cd6ff'
  on-tertiary-fixed: '#001f28'
  on-tertiary-fixed-variant: '#004e60'
  background: '#f7f9fb'
  on-background: '#191c1e'
  surface-variant: '#e0e3e5'
typography:
  h1:
    fontFamily: Space Grotesk
    fontSize: 48px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  h2:
    fontFamily: Space Grotesk
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.2'
    letterSpacing: -0.01em
  h3:
    fontFamily: Space Grotesk
    fontSize: 24px
    fontWeight: '600'
    lineHeight: '1.3'
    letterSpacing: 0em
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
    letterSpacing: 0em
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.5'
    letterSpacing: 0em
  label-caps:
    fontFamily: Space Grotesk
    fontSize: 12px
    fontWeight: '700'
    lineHeight: '1'
    letterSpacing: 0.1em
  mono:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '500'
    lineHeight: '1.5'
    letterSpacing: 0em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  unit: 4px
  xs: 4px
  sm: 8px
  md: 16px
  lg: 24px
  xl: 48px
  container-max: 1280px
  gutter: 24px
---

## Brand & Style

This design system is engineered for the high-stakes environment of Industrial Tech and the Oil & Gas sector. The brand personality is grounded in **Precision, Reliability, and Technical Sophistication**. It communicates the expertise of a full-stack developer who understands both the rigid requirements of physical infrastructure and the fluid possibilities of AI.

The visual style follows a **Corporate-Industrial Minimalism** approach. It utilizes structured grid systems reminiscent of engineering blueprints and technical schematics. The UI avoids decorative fluff, opting instead for functional aesthetics where every line and margin serves a purpose. The emotional response should be one of "Expertise in Control"—reassuring stakeholders that complex data and systems are being handled with surgical accuracy.

## Colors

The palette is anchored by **Deep Midnight Navy**, providing a heavy, authoritative base that evokes stability and tradition within the energy sector. **Slate Grey** serves as the primary bridge for secondary information and borders, maintaining a neutral, technical tone.

The **Electric Teal** accent is used sparingly but strategically. It functions as the "active state" or "data signal," highlighting key calls to action, AI-driven insights, and interactive elements. Backgrounds remain predominantly white to ensure maximum readability of technical documentation and code snippets. Status colors (Error/Success) are muted to fit the industrial aesthetic, ensuring they inform without alarming.

## Typography

This design system utilizes **Space Grotesk** for headings to inject a technical, futuristic, yet geometric rigor. Its distinct letterforms suggest innovation and engineering precision. **Inter** is used for body text due to its exceptional legibility and systematic appearance, ensuring that even dense technical descriptions remain accessible.

- **Headings:** High contrast in scale but low in decoration. Use "Label-caps" for section overlines to mimic industrial labeling systems.
- **Body:** Standardized at 16px for optimal scanning.
- **Technical Data:** Use the medium weight of Inter with slightly tighter tracking for tabular data or code-adjacent labels to maintain a "monospaced feel" without sacrificing the readability of a sans-serif.

## Layout & Spacing

The layout is governed by a **Strict 12-Column Grid**. This design system relies on clear vertical and horizontal alignment to suggest order and reliability.

- **Rhythm:** A 4px baseline shift ensures all elements, from icons to text, align to a consistent mathematical scale.
- **Project Showcases:** Use a card-based layout where cards span 4 columns (3-up) or 6 columns (2-up), depending on content density.
- **Negative Space:** Use generous "XL" spacing between major sections to prevent the technical content from feeling claustrophobic.
- **Dividers:** Use 1px Slate Grey (#4A5568) lines at 20% opacity to separate sections, mimicking the look of a technical ledger or blueprint.

## Elevation & Depth

To maintain a professional and "flat" industrial feel, this design system avoids heavy shadows. Depth is communicated through **Tonal Layering** and **Low-Contrast Outlines**.

- **Surfaces:** Most content sits on the base white background. Secondary sections or "well" containers use the Neutral color (#F8FAFC) to create subtle recession.
- **Borders:** Instead of shadows, use 1px solid borders in Slate Grey at low opacity for cards and input fields.
- **Active Elevation:** Only upon interaction (hover/focus) should an element exhibit a subtle, "hard" shadow (4px offset, no blur, Deep Midnight Navy at 10% opacity) to signify a mechanical click or engagement.
- **AI Layers:** For AI-specific components, a very subtle 20px blur of Electric Teal can be used behind a container to suggest "processing" or "intelligence" without breaking the rigid grid.

## Shapes

The shape language is **Precise and Minimal**.

- **Corners:** A "Soft" (0.25rem) radius is applied to all buttons, cards, and input fields. This provides just enough approachability to feel modern without losing the "hard" edge required for a professional industrial tool.
- **Icons:** Use stroke-based icons with a 2px weight. Avoid filled icons unless they represent a critical status alert.
- **Data Motifs:** Graphs and charts should use sharp 90-degree angles or very slight curves to maintain the technical aesthetic.

## Components

- **Buttons:** Primary buttons use Deep Midnight Navy with White text. Secondary buttons use a Slate Grey outline. The "Electric Teal" is reserved for specific "Run AI" or "Analyze" actions to differentiate standard navigation from specialized computations.
- **Cards:** White background with a 1px Slate Grey border. Header areas within cards should have a subtle #F8FAFC background to separate metadata from the main content.
- **Chips/Tags:** Used for tech stacks (e.g., "Python", "TensorFlow", "React"). Use a light Slate Grey background with Midnight Navy text; no borders.
- **Inputs:** Square-ish, 1px bordered boxes. Use a 2px Electric Teal left-border highlight when the field is focused to simulate a terminal-style cursor.
- **Data Visualization:** Line charts should use Electric Teal for the primary data path. Use Slate Grey for grid lines.
- **Technical Diagrams:** Use simple vector lines and labels in Space Grotesk. Incorporate "blueprint" dots at grid intersections for background sections to reinforce the Industrial Tech theme.
