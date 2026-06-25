---
name: Synthetica
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
  on-surface-variant: '#494454'
  inverse-surface: '#2d3133'
  inverse-on-surface: '#eff1f3'
  outline: '#7b7486'
  outline-variant: '#cbc3d7'
  surface-tint: '#6d3bd7'
  primary: '#6b38d4'
  on-primary: '#ffffff'
  primary-container: '#8455ef'
  on-primary-container: '#fffbff'
  inverse-primary: '#d0bcff'
  secondary: '#00687a'
  on-secondary: '#ffffff'
  secondary-container: '#57dffe'
  on-secondary-container: '#006172'
  tertiary: '#545c72'
  on-tertiary: '#ffffff'
  tertiary-container: '#6c748b'
  on-tertiary-container: '#fefcff'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#e9ddff'
  primary-fixed-dim: '#d0bcff'
  on-primary-fixed: '#23005c'
  on-primary-fixed-variant: '#5516be'
  secondary-fixed: '#acedff'
  secondary-fixed-dim: '#4cd7f6'
  on-secondary-fixed: '#001f26'
  on-secondary-fixed-variant: '#004e5c'
  tertiary-fixed: '#dae2fd'
  tertiary-fixed-dim: '#bec6e0'
  on-tertiary-fixed: '#131b2e'
  on-tertiary-fixed-variant: '#3f465c'
  background: '#f7f9fb'
  on-background: '#191c1e'
  surface-variant: '#e0e3e5'
typography:
  display-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 64px
    fontWeight: '800'
    lineHeight: 72px
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 40px
    fontWeight: '800'
    lineHeight: 48px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-sm:
    fontFamily: JetBrains Mono
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: 0.05em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  base: 8px
  container-max: 1280px
  gutter: 24px
  margin-desktop: 64px
  margin-mobile: 20px
---

## Brand & Style

This design system embodies the "Future-Human" narrative, focusing on the symbiotic relationship between human creativity and artificial intelligence. The aesthetic avoids cold, dystopian tropes in favor of a bright, optimistic, and highly interactive educational environment.

The design style is a hybrid of **Minimalism** and **Glassmorphism**. It utilizes expansive white space to ensure clarity and focus, while employing translucent, frosted layers to represent the "transparency" and "depth" of AI processing. Organic, fluid shapes contrast with systematic grid structures to visualize the blend of human intuition and machine logic. The emotional response should be one of curiosity, empowerment, and trust.

## Colors

The palette is anchored by **Deep Space Blue** (#0F172A), used primarily for high-contrast text and structural grounding. The primary driver is **Electric Violet** (#8B5CF6), symbolizing the spark of machine intelligence, while **Cyan** (#06B6D4) provides a cooling, tech-oriented secondary accent.

Backgrounds should default to white or the ultra-light **Neutral** (#F8FAFC) to maintain an approachable, educational feel. Gradients are essential; use a linear 45-degree blend of Electric Violet and Cyan for primary actions and interactive states to signify "energy" and "connection."

## Typography

The typographic hierarchy balances warmth with technical precision. **Plus Jakarta Sans** is used for headings; its soft, rounded terminals provide a friendly and welcoming entrance to complex topics. 

**Inter** serves as the workhorse for body text, ensuring maximum readability for long-form educational content. For technical metadata, code snippets, or AI "status" indicators, **JetBrains Mono** is used to provide a subtle nod to the underlying technology without appearing intimidating. Large display headings should use tighter letter-spacing and heavy weights to command attention.

## Layout & Spacing

The design system utilizes a **12-column fluid grid** for desktop and a **4-column grid** for mobile. A consistent 8px base unit (the "Atomic Unit") governs all padding and margin decisions.

Layouts should favor asymmetrical compositions to feel dynamic and "alive." Use generous vertical padding (80px - 120px) between sections to create a sense of breathability. Content should be centered within a max-width container, but decorative "organic shapes" (blurred orbs) are permitted to bleed off the edges of the viewport to enhance the sense of depth.

## Elevation & Depth

Depth is achieved through **Glassmorphism** rather than traditional heavy shadows. Surfaces use a background blur (12px to 20px) and a semi-transparent white fill (typically 60-80% opacity) to create a "frosted glass" effect.

Each glass element must feature a subtle 1px inner border (stroke) with a white-to-transparent gradient to simulate light catching the edge of the pane. For interactive elevation, use a multi-layered ambient shadow: a soft, violet-tinted glow that expands when an element is hovered, suggesting the piece is "powering up."

## Shapes

The shape language is "Squircle-based"—avoiding harsh 90-degree angles entirely. Standard containers use a 16px (0.5rem) radius to maintain a modern, friendly appearance. 

Buttons and "pill" tags use a fully rounded (32px+) radius to signify interactability and softness. In the background, use large, non-geometric "organic blobs" with CSS blurs to break the rigidity of the grid and reinforce the "Human" side of the design narrative.

## Components

### Buttons
Primary buttons feature a vibrant violet-to-cyan gradient with white text. On hover, the gradient should shift slightly or brighten. Secondary buttons are "ghost" style with a glassmorphic background and a 1px solid violet border.

### Glassmorphic Cards
Cards are the primary content vessel. They must have a `backdrop-filter: blur(16px)`, a light white border at 20% opacity, and a subtle "inner glow" on the top-left edge.

### Interactive Timelines
Use a solid 2px cyan line with "pulsing" violet nodes to represent milestones in AI history. Active nodes should have a larger radius and a soft outer glow.

### Input Fields
Inputs should be clean with a light-gray fill that turns into a glassmorphic state on focus, highlighted by a cyan bottom border.

### Chips & Badges
Small, pill-shaped elements using **JetBrains Mono**. These should use low-saturation versions of the accent colors (e.g., light lavender background with deep violet text) to indicate categories without competing with primary buttons.