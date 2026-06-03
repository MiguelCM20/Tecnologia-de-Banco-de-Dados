---
name: Technical Infrastructure System
colors:
  surface: '#081425'
  surface-dim: '#081425'
  surface-bright: '#2f3a4c'
  surface-container-lowest: '#040e1f'
  surface-container-low: '#111c2d'
  surface-container: '#152031'
  surface-container-high: '#1f2a3c'
  surface-container-highest: '#2a3548'
  on-surface: '#d8e3fb'
  on-surface-variant: '#c6c6cd'
  inverse-surface: '#d8e3fb'
  inverse-on-surface: '#263143'
  outline: '#909097'
  outline-variant: '#45464d'
  surface-tint: '#bec6e0'
  primary: '#bec6e0'
  on-primary: '#283044'
  primary-container: '#0f172a'
  on-primary-container: '#798098'
  inverse-primary: '#565e74'
  secondary: '#5de6ff'
  on-secondary: '#00363e'
  secondary-container: '#00cbe6'
  on-secondary-container: '#00515d'
  tertiary: '#b9c8de'
  on-tertiary: '#233143'
  tertiary-container: '#081828'
  on-tertiary-container: '#738296'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#dae2fd'
  primary-fixed-dim: '#bec6e0'
  on-primary-fixed: '#131b2e'
  on-primary-fixed-variant: '#3f465c'
  secondary-fixed: '#a2eeff'
  secondary-fixed-dim: '#2fd9f4'
  on-secondary-fixed: '#001f25'
  on-secondary-fixed-variant: '#004e5a'
  tertiary-fixed: '#d4e4fa'
  tertiary-fixed-dim: '#b9c8de'
  on-tertiary-fixed: '#0d1c2d'
  on-tertiary-fixed-variant: '#39485a'
  background: '#081425'
  on-background: '#d8e3fb'
  surface-variant: '#2a3548'
typography:
  display:
    fontFamily: Geist
    fontSize: 48px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Geist
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.2'
  headline-lg-mobile:
    fontFamily: Geist
    fontSize: 24px
    fontWeight: '600'
    lineHeight: '1.2'
  headline-md:
    fontFamily: Geist
    fontSize: 24px
    fontWeight: '600'
    lineHeight: '1.3'
  body-lg:
    fontFamily: Geist
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Geist
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-md:
    fontFamily: JetBrains Mono
    fontSize: 14px
    fontWeight: '500'
    lineHeight: '1.4'
    letterSpacing: 0.05em
  code-sm:
    fontFamily: JetBrains Mono
    fontSize: 12px
    fontWeight: '400'
    lineHeight: '1.5'
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
  gutter: 24px
  margin-mobile: 16px
  margin-desktop: 64px
---

## Brand & Style
The design system is engineered for a high-performance database environment where stability and technical precision are paramount. The brand personality is authoritative yet innovative, catering to developers, data engineers, and CTOs who prioritize uptime and data integrity.

The visual style blends **Corporate Modern** efficiency with **Technical Minimalist** details. It utilizes a structured grid-based aesthetic, subtle monospaced accents for data-heavy contexts, and a sophisticated use of depth to organize complex information architectures. The emotional response should be one of absolute reliability, high-speed performance, and modern sophistication.

## Colors
This design system employs a "Tech Blue" palette designed for long-session readability and professional gravity.

- **Primary (Deep Blue):** Used for primary backgrounds and structural elements to establish a solid foundation.
- **Secondary (Cyan/Electric Blue):** Reserved for data highlights, active states, and calls to action. It represents the "flow" of data.
- **Tertiary (Slate Gray):** Used for auxiliary information, supporting text, and low-priority icons.
- **Neutral:** A range of slates used for borders, dividers, and surface differentiation.

The default mode is **Dark**, mirroring the environments where developers and database administrators spend the majority of their time.

## Typography
The typography is centered around **Geist** for its exceptional clarity and technical "developer-first" aesthetic. Its geometric construction ensures legibility in dense data views. 

**JetBrains Mono** is utilized for labels, technical metadata, and code snippets. This creates a clear visual distinction between editorial content and technical data. 

- **Headlines:** Should be tight and impactful with slight negative letter-spacing.
- **Body:** Uses generous line-height to maintain readability during technical documentation review.
- **Labels:** Always in monospace to signify data attributes or system status.

## Layout & Spacing
The system uses a **12-column fluid grid** for desktop and a **4-column grid** for mobile. The layout philosophy is rooted in a strict 4px baseline grid to ensure mathematical alignment across all components.

- **Grid Patterns:** Subtle 24px background grids should be used in hero sections or container backgrounds to evoke a sense of infrastructure and organized data.
- **Margins:** Large horizontal margins on desktop (64px) help focus the user's eye on the central data flow.
- **Gutters:** Fixed 24px gutters maintain a consistent "breathing room" between complex data widgets and charts.

## Elevation & Depth
Depth is conveyed through **Tonal Layering** rather than traditional shadows. In a dark technical interface, physical shadows are replaced by "inner glows" and "border lighting."

- **Level 0 (Background):** Deepest slate (#020617).
- **Level 1 (Card/Container):** Raised surface (#0F172A) with a 1px solid border (#1E293B).
- **Level 2 (Popovers/Modals):** High-contrast surface (#1E293B) with a subtle Cyan-tinted outer glow (0px 4px 20px rgba(34, 211, 238, 0.1)).

Use thin, low-opacity lines to connect related data nodes, reinforcing the "infrastructure" metaphor.

## Shapes
The shape language is **Soft (0.25rem)**. This preserves the professional, "engineered" feel of the system while preventing it from feeling overly aggressive or dated.

- **Components:** Buttons and input fields use a 4px radius.
- **Containers:** Larger cards or code blocks use an 8px (rounded-lg) radius.
- **Data Nodes:** Connection points or status pips use full rounding (pill-shaped) to distinguish them from structural UI elements.

## Components
- **Buttons:** Primary buttons use a solid Cyan fill with dark navy text. Secondary buttons are outlined with a 1px slate border and subtle hover transitions to a dimmed cyan.
- **Input Fields:** Dark background (#020617) with a 1px slate border. On focus, the border transitions to Cyan with a faint outer glow.
- **Data Cards:** Features a subtle grid pattern background and a 1px top-border highlight in the secondary color to denote "active" or "monitored" status.
- **Status Chips:** Small, monospaced text within high-contrast containers (e.g., "SYNCING" in Cyan, "ERROR" in Red).
- **Code Blocks:** Styled with a distinct background color and line numbering, using JetBrains Mono for all content.
- **Connection Lines:** SVG-based paths with 1px width, using a gradient from Primary to Secondary to represent data flow between components.