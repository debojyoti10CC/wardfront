---
version: alpha
name: "MetaDAO Design System"
description: "MetaDAO is a crypto fundraising platform with a dual-theme design system built on a strict neutral gray palette. The visual identity pairs Geist Sans (utility UI) with EB Garamond (editorial accent) for hero headings, creating a distinctive contrast between functional and expressive type. The coral-red (#ff4949) brand accent appears on the logo, italic hero headline, and CTA button outlines. Surfaces use a stepped neutral scale (--canvas, --surface, --raised, --chrome) with hairline borders rather than shadows for depth. Both light and dark themes are fully supported via CSS custom properties."
colors:
  line-dark: "#525252"
  brand-red: "#ff4949"
  canvas-dark: "#171717"
  emerald: "#10b981"
  raised-dark: "#2e2e2e"
  surface-dark: "#262626"
  faint-dark: "#a3a3a3"
  foreground-dark: "#ffffff"
  muted-dark: "#d4d4d4"
  line: "#d4d4d4"
  canvas: "#f5f5f5"
  raised: "#fafafa"
  surface: "#ffffff"
  faint: "#737373"
  foreground: "#0a0a0a"
  muted: "#404040"
  chrome: "#e5e5e5"
typography:
  hero-display:
    fontFamily: "ebGaramond"
    fontSize: "48px"
    fontWeight: "500"
    lineHeight: "43.2px"
    letterSpacing: "-1.2px"
  section-heading:
    fontFamily: "ebGaramond"
    fontSize: "36px"
    fontWeight: "500"
    lineHeight: "45px"
    letterSpacing: "-0.9px"
  card-heading:
    fontFamily: "GeistSans"
    fontSize: "23px"
    fontWeight: "500"
    lineHeight: "25px"
    letterSpacing: "-0.575px"
  subheading-medium:
    fontFamily: "GeistSans"
    fontSize: "20px"
    fontWeight: "500"
    lineHeight: "28px"
    letterSpacing: "-0.4px"
  body-default:
    fontFamily: "GeistSans"
    fontSize: "16px"
    fontWeight: "400"
    lineHeight: "24px"
  body-tight:
    fontFamily: "GeistSans"
    fontSize: "16px"
    fontWeight: "400"
    lineHeight: "24px"
    letterSpacing: "-0.4px"
  body-medium:
    fontFamily: "GeistSans"
    fontSize: "16px"
    fontWeight: "500"
    lineHeight: "24px"
  small-ui:
    fontFamily: "GeistSans"
    fontSize: "14px"
    fontWeight: "400"
    lineHeight: "20px"
    letterSpacing: "-0.35px"
  caption:
    fontFamily: "GeistSans"
    fontSize: "13px"
    fontWeight: "400"
    lineHeight: "20px"
  mono-label:
    fontFamily: "GeistMono"
    fontSize: "11px"
    fontWeight: "500"
    lineHeight: "16.5px"
    letterSpacing: "1.1px"
  mono-body:
    fontFamily: "GeistMono"
    fontSize: "12px"
    fontWeight: "400"
    lineHeight: "16px"
rounded:
  button: "14px"
  card: "8px"
  small: "6px"
  large: "16px"
  medium: "12px"
  pill: "20px"
spacing:
  xs: "4px"
  sm: "8px"
  md: "12px"
  base: "16px"
  lg: "24px"
  xl: "32px"
  2xl: "48px"
  3xl: "64px"
  micro: "2px"
  component-gap: "4.8px"
  section-pad: "56px"
---

## Overview

MetaDAO is a crypto fundraising platform with a dual-theme design system built on a strict neutral gray palette. The visual identity pairs Geist Sans (utility UI) with EB Garamond (editorial accent) for hero headings, creating a distinctive contrast between functional and expressive type. The coral-red (#ff4949) brand accent appears on the logo, italic hero headline, and CTA button outlines. Surfaces use a stepped neutral scale (--canvas, --surface, --raised, --chrome) with hairline borders rather than shadows for depth. Both light and dark themes are fully supported via CSS custom properties.

**Signature traits:**
- Dual typeface system: Pairs ebGaramond and GeistSans across the type hierarchy.

## Colors

The palette uses 19 validated color tokens across 2 theme profiles. Semantic roles stay attached to observed usage so generation agents can choose accents without inventing new color meaning.

**Semantic naming:**
- **surface-background** maps to `canvas`: Role "background" is grounded by usage context "Page-level background, outermost surface".
- **border-border** maps to `chrome`: Role "border" is grounded by usage context "Subtle dividers and chrome borders".
- **border-primary** maps to `line`: Role "primary" is grounded by usage context "Component borders, hairline separators".
- **content-text** maps to `foreground`: Role "text" is grounded by usage context "Primary body and heading text".

### Dark Theme

### Primary Brand
- **Line Dark** (#525252): Component borders and hairline separators in dark mode. Role: primary. {authored: rgb(82, 82, 82), space: rgb}

### Text Scale
- **Faint Dark** (#a3a3a3): Tertiary text, placeholders in dark mode. Role: text. {authored: rgb(163, 163, 163), space: rgb}
- **Foreground Dark** (#ffffff): Primary text in dark mode. Role: text. {authored: rgb(255, 255, 255), space: rgb}
- **Muted Dark** (#d4d4d4): Secondary text in dark mode. Role: text. {authored: rgb(212, 212, 212), space: rgb}

### Surface & Shadows
- **Brand Red** (#ff4949): Logo, italic hero headline, Sign In button border — same across themes. Role: background. {authored: rgb(255, 73, 73), space: rgb}
- **Canvas Dark** (#171717): Page-level background in dark mode. Role: background. {authored: rgb(23, 23, 23), space: rgb}
- **Emerald** (#10b981): Online/active status dot indicator. Role: background. {authored: rgb(16, 185, 129), space: rgb}
- **Raised Dark** (#2e2e2e): Elevated surfaces, hover states in dark mode. Role: background. {authored: rgb(46, 46, 46), space: rgb}
- **Surface Dark** (#262626): Card and panel surfaces in dark mode. Role: background. {authored: rgb(38, 38, 38), space: rgb}

### Light Theme

### Primary Brand
- **Line** (#d4d4d4): Component borders, hairline separators. Role: primary. {authored: rgb(212, 212, 212), space: rgb}

### Text Scale
- **Faint** (#737373): Tertiary text, placeholders, metadata. Role: text. {authored: rgb(115, 115, 115), space: rgb}
- **Foreground** (#0a0a0a): Primary body and heading text. Role: text. {authored: rgb(10, 10, 10), space: rgb}
- **Muted** (#404040): Secondary text, nav links. Role: text. {authored: rgb(64, 64, 64), space: rgb}

### Interactive
- **Chrome** (#e5e5e5): Subtle dividers and chrome borders. Role: border. {authored: rgb(229, 229, 229), space: rgb}

### Surface & Shadows
- **Brand Red** (#ff4949): Logo, italic hero headline, Sign In button border, CTA links. Role: background. {authored: rgb(255, 73, 73), space: rgb}
- **Canvas** (#f5f5f5): Page-level background, outermost surface. Role: background. {authored: rgb(245, 245, 245), space: rgb}
- **Emerald** (#10b981): Online/active status dot indicator. Role: background. {authored: rgb(16, 185, 129), space: rgb}
- **Raised** (#fafafa): Slightly elevated surfaces, hover states. Role: background. {authored: rgb(250, 250, 250), space: rgb}
- **Surface** (#ffffff): Card and panel surfaces, search bar fill. Role: background. {authored: rgb(255, 255, 255), space: rgb}

## Typography

Typography uses ebGaramond, GeistSans, GeistMono across extracted hierarchy roles. Keep hierarchy mapped to these token rows before adding decorative type styles.

Mixes ebGaramond and GeistSans and GeistMono for visual contrast. Weight range spans medium, regular. Sizes range from 11px to 48px.

### Font Roles
- **Headline Font**: GeistSans
- **Body Font**: GeistSans

### Type Scale Evidence
| Role | Font | Size | Weight | Line Height | Letter Spacing | Stack / Features | Notes |
|------|------|------|--------|-------------|----------------|------------------|-------|
| Hero display headline — italic accent phrase 'ownership coin' | ebGaramond | 48px | 500 | 43.2px | -1.2px | ebGaramond, ebGaramond Fallback, EB Garamond, Georgia, serif | Extracted token |
| Section-level headings with editorial serif treatment | ebGaramond | 36px | 500 | 45px | -0.9px | ebGaramond, ebGaramond Fallback, EB Garamond, Georgia, serif | Extracted token |
| Feature card titles (Raise USDC, Spend it responsibly, Win together) | GeistSans | 23px | 500 | 25px | -0.575px | GeistSans, GeistSans Fallback | Extracted token |
| Sub-section headings and stat labels | GeistSans | 20px | 500 | 28px | -0.4px | GeistSans, GeistSans Fallback | Extracted token |
| Primary body text, navigation links, UI labels | GeistSans | 16px | 400 | 24px | normal | GeistSans, GeistSans Fallback | Extracted token |
| Body text with tighter tracking for denser layouts | GeistSans | 16px | 400 | 24px | -0.4px | GeistSans, GeistSans Fallback | Extracted token |
| Emphasized body text, button labels | GeistSans | 16px | 500 | 24px | normal | GeistSans, GeistSans Fallback | Extracted token |
| Secondary UI labels, dropdown items, metadata | GeistSans | 14px | 400 | 20px | -0.35px | GeistSans, GeistSans Fallback | Extracted token |
| Captions, footer links, fine print | GeistSans | 13px | 400 | 20px | normal | GeistSans, GeistSans Fallback | Extracted token |
| Uppercase metadata labels (CUMULATIVE RAISED, LAUNCHED TO-DATE) | GeistMono | 11px | 500 | 16.5px | 1.1px | GeistMono, ui-monospace, SFMono-Regular, Roboto Mono, Menlo, Monaco, Liberation Mono, DejaVu Sans Mono, Courier New, monospace | Extracted token |
| Code snippets, wallet addresses, on-chain data | GeistMono | 12px | 400 | 16px | normal | GeistMono, ui-monospace, SFMono-Regular, Roboto Mono, Menlo, Monaco, Liberation Mono, DejaVu Sans Mono, Courier New, monospace | Extracted token |

## Layout

Responsive system uses 2 breakpoint tier(s): mobile, desktop.

This system uses a 8px base grid with scale values 2, 4, 8, 12, 16, 24, 32, 48, 64.

### Responsive Strategy
- **mobile (<= 767.98px)**: Constrain layout for small viewports and prioritize vertical stacking.
- **desktop (Unknown)**: Expand layout density and horizontal composition for wide viewports.

### Spacing System
| Token | Value | Px | Notes |
|------|-------|----|-------|
| micro | 2px | 2 | Extracted spacing token |
| xs | 4px | 4 | Extracted spacing token |
| component-gap | 4.8px | 4.8 | Extracted spacing token |
| sm | 8px | 8 | Extracted spacing token |
| md | 12px | 12 | Extracted spacing token |
| base | 16px | 16 | Extracted spacing token |
| lg | 24px | 24 | Extracted spacing token |
| xl | 32px | 32 | Extracted spacing token |
| 2xl | 48px | 48 | Extracted spacing token |
| section-pad | 56px | 56 | Extracted spacing token |
| 3xl | 64px | 64 | Extracted spacing token |

## Elevation & Depth

Keep depth flat unless validated shadow or interaction evidence appears in the extraction payload. Do not invent shadows beyond this evidence boundary.

### Shadow Evidence
| Shadow Token | Layers | Details |
|--------------|--------|---------|
| n/a | 0 | No validated shadow payload |

### Interaction Signals
| Theme | Signal | Evidence |
|-------|--------|----------|
| Light | backdrop-filter | blur(8px) |
| Light | outline-color | rgb(0, 0, 0) ; rgb(115, 115, 115) ; rgb(10, 10, 10) |
| Light | outline-width | 3px |
| Light | outline-offset | 0px ; 1px |
| Light | transform | matrix(-1, 0, 0, -1, 38, 38) ; matrix(1, -8.74228e-08, -8.74228e-08, -1, 0, 38) ; matrix(1.98664, 0, 0, 1.98664, 0, 0) |
| Dark | backdrop-filter | blur(8px) |
| Dark | outline-color | rgb(255, 255, 255) ; rgb(163, 163, 163) ; rgb(250, 250, 250) |
| Dark | outline-width | 3px |
| Dark | outline-offset | 0px ; 1px |
| Dark | transform | matrix(-1, 0, 0, -1, 38, 38) ; matrix(1, -8.74228e-08, -8.74228e-08, -1, 0, 38) ; matrix(1.87643, 0, 0, 1.87643, 0, 0) |

## Shapes

Shape language maps directly to rounded tokens. Keep component corners consistent with the role mapping below before introducing bespoke geometry.

### Radius Roles
| Token | Value | Px | Role Mapping |
|------|-------|----|--------------|
| small | 6px | 6 | Subtle corner |
| card | 8px | 8 | Control corner |
| medium | 12px | 12 | Control corner |
| button | 14px | 14 | Card corner |
| large | 16px | 16 | Card corner |
| pill | 20px | 20 | Card corner |

### Geometry Evidence
| Radius Token | Shape | Units |
|--------------|-------|-------|
| button | 14px | px |
| card | 8px | px |
| small | 6px | px |
| large | 16px | px |
| medium | 12px | px |
| pill | 20px | px |

## Components

(none detected)

## Do's and Don'ts

Guardrails protect Dual typeface system without adding unsupported visual claims.

| Do | Don't |
|----|---------|
| Do maintain consistent spacing using the base grid | Don't make unsupported claims about absent visual features |
| Do maintain WCAG AA contrast ratios (4.5:1 for normal text) | Don't mix rounded and sharp corners in the same view |
| Do use the primary color only for the single most important action per screen |  |
| Do verify evidence before writing new design-system guidance |  |

## Responsive Evidence

### Breakpoints
| Name | Width | Key Changes |
|------|-------|-------------|
| Mobile | <= 600px | (max-width: 600px) |
| Breakpoint 2 | <= 767.98px | (max-width: 767.98px) |
| Breakpoint 3 | Unknown | (hover: none) and (pointer: coarse) |

## Agent Prompt Guide

### Example Component Prompts
- Create button component using validated primary color role and spacing tokens.
- Create card component with mapped radius role and evidence-backed elevation.
- Create form input component using inferred typography hierarchy and border roles.

### Iteration Guide
1. Start with extracted palette and typography roles only.
2. Map spacing and radius directly from token tables before visual polish.
3. Apply component patterns one section at a time and compare against source intent.
4. Keep elevation claims tied to explicit evidence in output.
5. Iterate with smallest diffs and re-check section hierarchy after each change.
