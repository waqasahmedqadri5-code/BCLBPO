# BCL BPO - Brand & Style Guidelines

This document outlines the core brand identity, visual guidelines, voice, tone, and system architecture for BCL BPO's digital touchpoints. It ensures that all frontend modifications and new pages remain completely consistent with the high-stakes BPO corporate identity.

---

## 1. Brand Essence

**BCL BPO** is a leading global provider of high-stakes Business Process Outsourcing and managed IT solutions. Our brand is built on three core pillars:
1. **Precision Operational Support:** Error-free execution of critical administrative, financial, and customer operations.
2. **Technical Dominance:** Robust, cutting-edge technical infrastructure, state-of-the-art data centers, and advanced automation workflows.
3. **Uncompromising Security:** Bank-grade data encryption, comprehensive compliance certifications (ISO 27001, SOC2 Type II, HIPAA), and 99.9% uptime reliability.

### The Brand Voice
- **Authoritative:** Grounded in facts, stability, and deep technological expertise. We speak as trusted enterprise partners, not raw startups.
- **Precise:** Clear, direct language. Avoid fluff and overly emotional marketing buzzwords. Detail-oriented and outcome-focused.
- **Always-On:** Evoking a sense of 24/7 responsiveness, vigilance, and global reach.

---

## 2. Visual Palette (Secure Enterprise Precision Theme)

The brand utilizes a **Corporate Dark Space** visual style, designed for operational dashboards, high-density portals, and premium executive sites. 

| Token | CSS Variable | Hex Color | Usage & Description |
| :--- | :--- | :--- | :--- |
| **Primary Background** | `--bg-primary` | `#011230` | Core backdrop of the entire application. Deep space navy. |
| **Surface Containers** | `--bg-surface` | `#0E1F3D` | Lighter navy for cards, form fields, and content containers. |
| **Secondary Neutral** | `--text-muted` | `#64748B` | Used for subheaders, non-active menu items, and non-critical helper text. |
| **High Contrast Text** | `--text-light` | `#D8E2FF` | General body copy, headlines, and high-visibility text labels. |
| **Accent / CTA** | `--color-accent` | `#00F2FE` | **Electric Cyan**. Used exclusively for active items, hover effects, primary buttons, and key metrics. |
| **Borders & Separators**| `--border-subtle`| `#233554` | 1px technical lines defining the structural grid and card outlines. |

### Color Usage Restrictions
- **Do not** introduce brand colors like standard saturated red, solid green, or standard primary blue.
- Use the **Electric Cyan (#00F2FE)** sparingly. It is a high-energy highlight color. If used on more than 10% of a screen surface, its impact is diluted and it degrades the premium aesthetic.
- Background blocks must transition smoothly through tonal levels: `Level 0 (#011230)` -> `Level 1 (#0E1F3D)` -> `Level 2 (#253453)`.

---

## 3. Typography Hierarchy

Consistent typography is critical to projecting professional technical capability.

1. **Brand Headers (Inter, Bold / Semi-Bold):**
   - Headings use tighter spacing (`-0.02em` for Display, `-0.01em` for Headline-MD).
   - High weights (Bold, font-weight 700) are reserved for major value propositions and core headers.
2. **Body Copy (Inter, Regular, font-weight 400):**
   - Inter is highly readable. Use 16px (1rem) for general text, with a generous `1.5` line height to prevent fatigue.
   - Text color should be `--text-light` (`#D8E2FF`) or `--text-muted` (`#64748B`) to keep a comfortable reading contrast ratio.
3. **Monospaced Technical Accents (JetBrains Mono, Medium, font-weight 500):**
   - Used for metadata tags, status indicators, system labels, uptime counters, and statistical metrics.
   - This provides the "always-on" tech terminal aesthetic that enterprise partners expect from a managed IT services BPO.

---

## 4. UI Layout & Geometry Rules

- **Grid Alignment:** All page layouts must align to a strict 12-column desktop grid with 24px gutters. Use margin-desktop of 64px for primary layout bounds.
- **Section Spacing:** Generous 80px (`section-padding`) vertical padding between sections to allow the dark layout to breathe.
- **Rounded Corners:**
  - Standard cards, interactive buttons, and text input boxes use a **8px (0.5rem) border radius**.
  - Small chips, checkboxes, and status items use a **4px border radius**.
  - **No fully circular rounded buttons** (except status indicators or utility circular buttons). The geometric squareness reinforces stability.
- **Interactive Visual Feedback:**
  - Hover states on primary elements must apply a transition duration of at least 200ms.
  - Hovering over cards or call-to-action buttons should trigger a subtle Cyan Glow (`.cyan-glow:hover { box-shadow: 0 0 20px 0 rgba(0, 242, 254, 0.15); }`).
  - Active buttons must scale down slightly (`active:scale-[0.98]`) to feel interactive and responsive.

---

## 5. Security & Trust Indicators

Every digital touchpoint must reassure our clients of enterprise-grade reliability:
- **SOC2 Type II & ISO 27001:** Always display certified badges or reference these compliance standards in headers, footers, or client login areas.
- **Uptime Assurance:** Highlight the "99.9% Uptime Support" metrics.
- **Secured Form Submissions:** Any login or form submission button must utilize micro-animations simulating cryptographic verification (e.g. transitioning from a loading wheel to a secure check icon).
