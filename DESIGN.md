---
name: Institutional Sovereign Fintech
colors:
  surface: '#0c1513'
  surface-dim: '#0c1513'
  surface-bright: '#323b39'
  surface-container-lowest: '#07100e'
  surface-container-low: '#141d1b'
  surface-container: '#18211f'
  surface-container-high: '#232c29'
  surface-container-highest: '#2d3734'
  on-surface: '#dbe5e1'
  on-surface-variant: '#c0c8c5'
  inverse-surface: '#dbe5e1'
  inverse-on-surface: '#293230'
  outline: '#8a928f'
  outline-variant: '#404846'
  surface-tint: '#a2d0c4'
  primary: '#a2d0c4'
  on-primary: '#05372f'
  primary-container: '#0f3e36'
  on-primary-container: '#7ca99e'
  inverse-primary: '#3b665d'
  secondary: '#bac8dc'
  on-secondary: '#243141'
  secondary-container: '#3a4859'
  on-secondary-container: '#a8b6ca'
  tertiary: '#e9c349'
  on-tertiary: '#3c2f00'
  tertiary-container: '#cba72f'
  on-tertiary-container: '#4e3d00'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#bdece0'
  primary-fixed-dim: '#a2d0c4'
  on-primary-fixed: '#00201b'
  on-primary-fixed-variant: '#224e46'
  secondary-fixed: '#d6e4f9'
  secondary-fixed-dim: '#bac8dc'
  on-secondary-fixed: '#0f1c2c'
  on-secondary-fixed-variant: '#3a4859'
  tertiary-fixed: '#ffe088'
  tertiary-fixed-dim: '#e9c349'
  on-tertiary-fixed: '#241a00'
  on-tertiary-fixed-variant: '#574500'
  background: '#0c1513'
  on-background: '#dbe5e1'
  surface-variant: '#2d3734'
typography:
  display-lg:
    fontFamily: Inter
    fontSize: 36px
    fontWeight: '700'
    lineHeight: 44px
    letterSpacing: -0.03em
  display-lg-mobile:
    fontFamily: Inter
    fontSize: 28px
    fontWeight: '700'
    lineHeight: 34px
    letterSpacing: -0.025em
  headline-lg:
    fontFamily: Inter
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 30px
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Inter
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 26px
    letterSpacing: -0.015em
  headline-sm:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '600'
    lineHeight: 22px
    letterSpacing: -0.01em
  title-md:
    fontFamily: Inter
    fontSize: 15px
    fontWeight: '500'
    lineHeight: 20px
    letterSpacing: -0.005em
  body-lg:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
    letterSpacing: 0em
  body-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
    letterSpacing: 0em
  body-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 16px
    letterSpacing: 0.01em
  label-lg:
    fontFamily: Inter
    fontSize: 13px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.02em
  label-md:
    fontFamily: Inter
    fontSize: 11px
    fontWeight: '600'
    lineHeight: 14px
    letterSpacing: 0.04em
  label-sm:
    fontFamily: Inter
    fontSize: 10px
    fontWeight: '700'
    lineHeight: 12px
    letterSpacing: 0.06em
  numeric-ledger:
    fontFamily: Inter
    fontSize: 22px
    fontWeight: '600'
    lineHeight: 28px
    letterSpacing: -0.02em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1rem
  gutter-tablet: 1.5rem
  gutter-desktop: 2rem
  margin: 1rem
  margin-tablet: 2rem
  margin-desktop: 3rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2rem
---

## Brand & Style

This design system establishes an institutional, sovereign financial experience engineered for ultra-high-net-worth mobile wealth management and cross-border liquidity transactions. The brand character projects absolute solvency, mathematical precision, and disciplined authority. It eschews volatile retail trends in favor of an opulent, high-security private-banking presence.

The visual style blends disciplined corporate minimalism with selective tactile and glassmorphic depth. Structural surfaces rely on deep emerald and obsidian-slate tonal layers. Micro-interactions convey physical permanence through subtle, high-performance haptics and deterministic transitions. Security indicators, hardware-grade biometric states, and dual-currency ledgers (PKR ₨ and SAR ﷼) are treated not as peripheral badges, but as core architectural pillars within the interface hierarchy.

## Colors

The palette is engineered around dark-mode operational security, mitigating eye fatigue during prolonged analytical sessions while preserving maximum visual contrast for rapid data scanning.

- **Primary (`#0F3E36`):** Deep Sovereign Emerald. Anchors primary interactive controls, authenticated surface glows, and active states.
- **Secondary (`#0D1B2A`):** Opulent Navy Slate. Forms structural backgrounds, nested module wrappers, and data-density separations.
- **Tertiary (`#D4AF37`):** Refined Sovereign Gold. Deployed selectively for asset appreciation indices, premium yield indicators, active currency exchange conduits, and verified institutional markers. Never used indiscriminately as background fill.
- **Neutral Base (`#091210`):** Abyssal Pine Black. The foundation canvas across all top-level mobile viewports.
- **Semantic Accents:**
  - Positive / Gain: `#10B981` (Muted Mint Green)
  - Negative / Drawdown: `#F43F5E` (Precise Crimson)
  - Security / Hardware Pass: `#38BDF8` (Cryo Cyan)
  - Surface Border: `rgba(212, 175, 55, 0.12)` on active containers; `rgba(255, 255, 255, 0.08)` on standard structural panels.

## Typography

Typography prioritizes tabular alignment, immediate scan-speed, and total cross-script legibility. The primary Latin typeface is Inter, specified with automated OpenType features enabled: `tnum` (tabular figures) and `cv05` / `cv08` for unambiguous mathematical distinction between characters (`0` vs `O`, `l` vs `1`).

For bilateral and foreign exchange ledger modules incorporating PKR (₨) and SAR (﷼), typography falls back gracefully to system Naskh/Nastaliq Unicode baselines with matched x-height and normalized line metrics. Font weights remain strictly within medium (500), semi-bold (600), and bold (700) tiers for financial values to eliminate pixel jitter and anti-aliasing blur against OLED dark grounds.

## Layout & Spacing

The system enforces an explicit 8-point spatial cadence tailored to dense handheld viewports.

- **Mobile Canvas (375px - 430px):** Single-column layout with 4 structural sub-columns, utilizing `1rem` outer canvas margins and `1rem` gutters. Touch targets adhere strictly to an absolute minimum dimension of 48×48 points.
- **Tablet / Split Screen (768px - 1024px):** 8-column layout with `2rem` margins and `1.5rem` gutters. The primary balance ledger locks to a fixed side-panel, while transaction histories and candlestick analytical engines fill the secondary pane.
- **Desktop Management (1200px+):** 12-column fixed grid capped at 1440px total container width, with `3rem` margins and `2rem` gutters.

Vertical rhythm adheres strictly to tokens: micro-spacers (`space-xs`, `space-sm`) separate numeric values from currency symbols and contextual metadata, while macro-spacers (`space-lg`, `space-xl`) define autonomous analytical modules and ledger groupings.

## Elevation & Depth

Visual hierarchy does not use high-diffuse white drop shadows. Instead, it relies on tonal luminosity stepping, ambient green-tinted cast shadows, and subtle glassmorphic edge reflections.

- **Base Floor (Elevation 0):** Absolute background `#091210`. Flat, non-reflective canvas.
- **Card Tier (Elevation 1):** `#0D1B2A` mixed with an overlaid 4% sovereign emerald gradient. Rimmed with a single-pixel low-contrast border: `rgba(255, 255, 255, 0.07)`.
- **Raised Interactive Panes (Elevation 2):** `#0F3E36` at 85% opacity with a `16px` backdrop-blur filter. Casts a soft ambient occlusion shadow: `0 12px 32px -8px rgba(0, 0, 0, 0.65), 0 4px 12px -2px rgba(15, 62, 54, 0.25)`.
- **Modals & Critical Security Sheets (Elevation 3):** `#081614` with a gold hairline structural perimeter (`rgba(212, 175, 55, 0.25)`) and a deep protective shadow: `0 24px 48px -12px rgba(0, 0, 0, 0.85)`.
- **Tactile Feedback:** Depressed states reduce component elevation by shifting borders from gold/light tones to dark emerald while scaling content by `0.985` to mirror physical key travel.

## Shapes

The design system applies a disciplined `Level 2` curvature schema, balancing ergonomic handheld comfort with institutional precision.

- **Base Radii (`rounded` / 0.5rem / 8px):** Applied to form fields, nested metric chips, biometric verification badges, and currency pills.
- **Intermediate Radii (`rounded-lg` / 1rem / 16px):** Applied to internal transaction cards, mini-charts, modular widgets, and contextual sheets.
- **Macro Radii (`rounded-xl` / 1.5rem / 24px):** Reserved for primary wealth summary portfolio cards, root modal containers, and quick-action navigation pods.
- **Pills (`9999px`):** Used exclusively for system status indicators (e.g., "Encrypted Session", "Ledger Synchronized") and isolated binary toggles.

## Components

### Buttons
- **Primary Sovereign:** Height 52px. Solid background `#0F3E36` with a hairline top border highlight of `rgba(212, 175, 55, 0.4)`. Text set in Inter SemiBold 15px in `#FFFFFF`. Smooth press response (`transform: scale(0.985)`).
- **Secondary Outlined:** Background `rgba(13, 27, 42, 0.6)` with a 1px border in `rgba(255, 255, 255, 0.12)`. Hover and active states tint to `rgba(212, 175, 55, 0.15)`.
- **Critical Action:** Background `#1F1014` with an edge highlight in `#F43F5E`, paired with high-contrast warning text.

### Currency Badges & Ledger Pills
- **PKR (₨) & SAR (﷼) Selectors:** Compact horizontal capsules (32px height) housing the localized currency symbol, a monospaced ISO label, and an live conversion rate differential. Active state features a 1px amber border (`#D4AF37`) with an emerald-black interior fill (`#0A1D1A`).

### Input Fields & Keypads
- **Numeric Wealth Inputs:** Height 60px. Surface color `#07100E` recessed with a 1px border `rgba(255, 255, 255, 0.08)`. Values display using `numeric-ledger` styling in high-contrast white. Focus shifts the outer border to sovereign gold (`#D4AF37`) with an ambient emerald glow (`0 0 0 3px rgba(15, 62, 54, 0.3)`).

### Biometric & Security Indicators
- Hardware-backed modules featuring a dual-ring concentric layout. Standby state rendered in `rgba(255, 255, 255, 0.2)`; authenticated state pulses in `#10B981` (Mint) with an encrypted session key label rendered in `label-sm`.

### Financial Cards & Chart Wrappers
- Constructed with `rounded-lg` (16px) or `rounded-xl` (24px) geometry. Surfaces employ a vertical gradient transitioning from `#0D1B2A` to `#091210`. The chart area utilizes sparklines and area fills defined with linear gradient stops: `#D4AF37` at 25% tapering down to `rgba(15, 62, 54, 0.0)` at the lower baseline. Gridlines maintain a strict `rgba(255, 255, 255, 0.04)` threshold.

### Lists & Transaction Rows
- Edge-to-edge container alignment with separated internal dividers (`rgba(255, 255, 255, 0.04)`). Left asset icon features a 40px rounded square (`rounded`, 8px) in `#0F3E36`. Left text stacks counterparty and timestamp; right alignment hosts the monospaced tabular transaction amount, color-coded by flow direction.