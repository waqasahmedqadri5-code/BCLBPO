---
name: Secure Enterprise Precision
colors:
  surface: '#011230'
  surface-dim: '#011230'
  surface-bright: '#293958'
  surface-container-lowest: '#000d27'
  surface-container-low: '#091b39'
  surface-container: '#0e1f3d'
  surface-container-high: '#192a48'
  surface-container-highest: '#253453'
  on-surface: '#d8e2ff'
  on-surface-variant: '#c5c6cd'
  inverse-surface: '#d8e2ff'
  inverse-on-surface: '#20304f'
  outline: '#8f9097'
  outline-variant: '#44474d'
  surface-tint: '#b9c7e4'
  primary: '#b9c7e4'
  on-primary: '#233148'
  primary-container: '#0a192f'
  on-primary-container: '#74829d'
  inverse-primary: '#515f78'
  secondary: '#b7c8e1'
  on-secondary: '#213145'
  secondary-container: '#3a4a5f'
  on-secondary-container: '#a9bad3'
  tertiary: '#e7bf99'
  on-tertiary: '#432b10'
  tertiary-container: '#281400'
  on-tertiary-container: '#9d7b5a'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#d6e3ff'
  primary-fixed-dim: '#b9c7e4'
  on-primary-fixed: '#0d1c32'
  on-primary-fixed-variant: '#39475f'
  secondary-fixed: '#d3e4fe'
  secondary-fixed-dim: '#b7c8e1'
  on-secondary-fixed: '#0b1c30'
  on-secondary-fixed-variant: '#38485d'
  tertiary-fixed: '#ffdcbd'
  tertiary-fixed-dim: '#e7bf99'
  on-tertiary-fixed: '#2b1701'
  on-tertiary-fixed-variant: '#5d4124'
  background: '#011230'
  on-background: '#d8e2ff'
  surface-variant: '#253453'
typography:
  display-lg:
    fontFamily: Inter
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Inter
    fontSize: 36px
    fontWeight: '700'
    lineHeight: 44px
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Inter
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
    letterSpacing: -0.01em
  headline-sm:
    fontFamily: Inter
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
  label-md:
    fontFamily: JetBrains Mono
    fontSize: 14px
    fontWeight: '500'
    lineHeight: 20px
    letterSpacing: 0.05em
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
  unit: 8px
  container-max: 1280px
  gutter: 24px
  margin-mobile: 16px
  margin-desktop: 64px
  stack-sm: 8px
  stack-md: 16px
  stack-lg: 32px
  section-padding: 80px
---

# BCL BPO - Design Specifications

## Brand & Style

This design system is engineered for a high-stakes BPO and IT services environment, where trust, technical dominance, and operational clarity are paramount. The aesthetic follows a **Corporate / Modern** approach with a refined technological edge, utilizing a deep-space foundation to evoke a sense of security and "always-on" reliability.

The visual language balances the weight of enterprise infrastructure with the agility of modern SaaS. It avoids unnecessary ornamentation, favoring high-precision alignment, ample whitespace, and thin, technical borders. The intended emotional response is one of calm authority—positioning the company as a sophisticated partner capable of handling complex global workflows.

## Colors

The palette is anchored by a deep navy primary, providing a stable, low-strain background for data-heavy environments. 

- **Primary (#011230):** Used for global backgrounds and foundational structural elements.
- **Neutral (#112240):** A slightly lighter navy used for surface containers, cards, and section differentiation.
- **Secondary (#64748B):** A muted slate gray reserved for non-critical metadata, helper text, and secondary icon states.
- **Accent (#00F2FE):** The "Electric Cyan" is used sparingly for high-impact Call to Actions (CTAs), progress indicators, and active selection states, providing a high-contrast focal point against the dark base.
- **Border Subtle (#233554):** Used for the thin 1px lines that define the grid without cluttering the visual hierarchy.

## Typography

The system utilizes **Inter** for all primary communication. Its geometric neutrality provides the professional clarity required for IT services. 

- **Headlines:** Use a tighter letter-spacing and heavier weights to project confidence and "Big Tech" authority.
- **Body:** Standardized at 16px for optimal readability against the dark background, utilizing a generous line height (1.5x) to prevent cognitive fatigue.
- **Labels:** We introduce **JetBrains Mono** for specialized metadata, status tags, and technical labels. This monospaced touch reinforces the IT and developer-centric nature of the brand.

## Layout & Spacing

The design system employs a **Fixed Grid** model for desktop to ensure complex dashboards and technical layouts maintain high-density precision. 

- **Grid:** A 12-column system with 24px gutters.
- **Rhythm:** All spacing is derived from a strict 8px base unit. 
- **Density:** While the system feels "premium" through generous outer margins (64px), internal component spacing is kept tight (8px-16px) to maximize information density for IT operators and BPO managers.
- **Mobile:** Reflows to a single column with 16px side margins, maintaining the 8px vertical rhythm.

## Elevation & Depth

Depth is conveyed through **Tonal Layering** rather than traditional heavy shadows. In a dark-mode corporate environment, light is used as a tool for focus.

- **Level 0 (Background):** Primary #011230.
- **Level 1 (Surface):** Neutral #112240 with a 1px border of #233554. This is used for cards and main content areas.
- **Level 2 (Interactive):** Elements that are hovered or active gain a subtle "Cyan Glow"—an outer drop shadow with a large blur radius (20px) and very low opacity (0.15) using the Accent color.
- **Borders:** Every container should have a thin 1px border. This "Glass-lite" effect creates a structured, high-tech grid feel without requiring heavy blurs.

## Shapes

The shape language is disciplined and consistent. A **8px (0.5rem) radius** is applied to almost all UI containers including buttons, cards, and input fields.

- **Standard Radius:** 8px for cards and primary buttons.
- **Subtle Radius:** 4px for smaller elements like chips or checkboxes.
- **Full Radius:** Reserved exclusively for status indicators or specific "pill" tags to contrast against the structural grid.

This specific roundedness avoids the "too-playful" look of fully rounded corners while moving away from the "dated" feel of sharp 90-degree angles.

## Components

### Buttons
- **Primary:** Background #00F2FE, Text #011230 (High contrast). Bold weight.
- **Secondary:** Transparent background, 1px Border #64748B, Text #FFFFFF.
- **Active State:** Add the "Cyan Glow" elevation effect.

### Input Fields
- **Default:** Background #112240, 1px Border #233554, Placeholder #64748B.
- **Focus:** 1px Border #00F2FE with a subtle cyan outer glow.

### Cards
- **Construction:** Background #112240, 1px Border #233554, 8px corner radius.
- **Padding:** 24px for standard content; 32px for premium marketing sections.

### Chips & Tags
- **Technical Tags:** Monospaced (JetBrains Mono), 12px size, subtle navy background with gray text.
- **Status Tags:** Use the Accent color only for "Active" or "Online" states.

### Checkboxes & Radios
- Square 8px-radius checkbox with a cyan checkmark for active states. This maintains the "technical" look more than rounded variants.

### Lists
- Use thin #233554 horizontal separators. Ensure 16px of vertical padding per list item to maintain executive-level readability.
