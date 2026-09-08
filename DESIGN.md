---
name: Academic Coordination & Advisor Portal
colors:
  surface: '#fcf8ff'
  surface-dim: '#dbd8e7'
  surface-bright: '#fcf8ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f5f2ff'
  surface-container: '#efecfb'
  surface-container-high: '#e9e6f5'
  surface-container-highest: '#e3e1ef'
  on-surface: '#1b1b25'
  on-surface-variant: '#474551'
  inverse-surface: '#302f3a'
  inverse-on-surface: '#f2effd'
  outline: '#787582'
  outline-variant: '#c8c4d3'
  surface-tint: '#5b53aa'
  primary: '#261a74'
  on-primary: '#ffffff'
  primary-container: '#3d348b'
  on-primary-container: '#aba3ff'
  inverse-primary: '#c6c0ff'
  secondary: '#4e50c3'
  on-secondary: '#ffffff'
  secondary-container: '#8789ff'
  on-secondary-container: '#191392'
  tertiary: '#392800'
  on-tertiary: '#ffffff'
  tertiary-container: '#553d00'
  on-tertiary-container: '#dca400'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#e4dfff'
  primary-fixed-dim: '#c6c0ff'
  on-primary-fixed: '#150066'
  on-primary-fixed-variant: '#433a91'
  secondary-fixed: '#e1dfff'
  secondary-fixed-dim: '#c1c1ff'
  on-secondary-fixed: '#08006c'
  on-secondary-fixed-variant: '#3635aa'
  tertiary-fixed: '#ffdea1'
  tertiary-fixed-dim: '#fcbc0c'
  on-tertiary-fixed: '#261900'
  on-tertiary-fixed-variant: '#5c4300'
  background: '#fcf8ff'
  on-background: '#1b1b25'
  surface-variant: '#e3e1ef'
  violet-deep: '#3D348B'
  violet-bright: '#7678ED'
  gold-warning: '#F7B801'
  orange-pending: '#F18701'
  deep-orange-urgent: '#F35B04'
  surface-pure: '#FFFFFF'
  surface-subtle: '#F8F8FC'
  surface-hover: '#EEEDFA'
  border-subtle: '#E5E4F5'
  text-primary: '#000000'
  text-inverse: '#FFFFFF'
typography:
  hero:
    fontFamily: Inter
    fontSize: 40px
    fontWeight: '700'
    lineHeight: 48px
    letterSpacing: -0.02em
  hero-mobile:
    fontFamily: Inter
    fontSize: 30px
    fontWeight: '700'
    lineHeight: 38px
    letterSpacing: -0.015em
  h1:
    fontFamily: Inter
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
    letterSpacing: -0.02em
  h1-mobile:
    fontFamily: Inter
    fontSize: 26px
    fontWeight: '700'
    lineHeight: 34px
    letterSpacing: -0.015em
  h2:
    fontFamily: Inter
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
    letterSpacing: -0.01em
  h3:
    fontFamily: Inter
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
    letterSpacing: -0.005em
  body-lg:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '500'
    lineHeight: 24px
  body:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  small:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 16px
  badge-label:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.02em
  metric-number:
    fontFamily: JetBrains Mono
    fontSize: 36px
    fontWeight: '700'
    lineHeight: 40px
    letterSpacing: -0.03em
  code-sm:
    fontFamily: JetBrains Mono
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  base: 0.25rem
  space-1: 0.25rem
  space-2: 0.5rem
  space-3: 0.75rem
  space-4: 1rem
  space-5: 1.25rem
  space-6: 1.5rem
  space-8: 2rem
  space-10: 2.5rem
  space-12: 3rem
  space-16: 4rem
  gutter-mobile: 1rem
  gutter-desktop: 1.25rem
  margin-mobile: 1rem
  margin-desktop: 2rem
  container-max-width: 90rem
  table-row-standard: 3.25rem
  table-row-dense: 2.75rem
  table-row-comfortable: 4rem
---

## Brand & Style

This design system establishes an institutional, high-trust environment tailored for university faculty, cooperative education supervisors, and academic advisors managing high-volume student cohorts. The visual language balances academic rigor and administrative authority with the high-velocity ergonomics of modern SaaS platforms.

The design philosophy adheres to **Corporate / Modern** principles:
- **Tone:** Methodical, authoritative, lucid, and decisive. Interfaces reduce cognitive load across heavy data matrices, structured validation flows, and multi-signature sign-off pipelines.
- **Visual Stance:** Crisp white architectural surfaces, sharp contrast boundaries, precise grid alignments, and intentional chromatic signals. Clutter and decorative fluff are eliminated in favor of clean metrics, clear progress lines, and scannable tabular typography.
- **Emotional Response:** Confidence, institutional integrity, and actionable clarity. Advisors must immediately identify workflow blockers, impending student deadlines, and pending evaluations without hunting through bureaucratic layers.

## Colors

The chromatic architecture relies on a dominant institutional anchor paired with functional status tiers.

- **Primary Violet Deep (`#3D348B`)**: The institutional anchor. Used for primary calls to action, top-level navigation, key milestone confirmations, prominent table headers, and focused states.
- **Secondary Violet Bright (`#7678ED`)**: The interactive catalyst. Applied to interactive border outlines, secondary links, icon accents, active tab underlines, and hover fills.
- **Tertiary Gold (`#F7B801`)**: Attention and tracking tier. Highlights missing log alerts, active countdown milestones, and academic warning badges. Text on gold remains black for guaranteed WCAG AA compliance.
- **Urgency Signals**:
  - **Pending Orange (`#F18701`)**: Signals pending company reviews, application queues, and standard review windows.
  - **Urgent Deep Orange (`#F35B04`)**: Reserved exclusively for critical non-compliance, expired deadlines, rejected log submissions, and advisor interventions.
- **Neutral Structure (`#1A1A24` & `#000000` on `#FFFFFF`)**: All base surfaces remain immaculate white (`#FFFFFF`) with ultra-light lavender-tinted surfaces (`#F8F8FC`) for row alternate fills. Contrast remains maximal to assist prolonged reading of evaluation reports.

## Typography

Typography establishes immediate operational hierarchy through dual font assignments:

- **Inter**: Drives all administrative discourse, navigation, dashboard headlines, student identity titles, and narrative advisor feedback. Its clean grotesque architecture provides fatigue-free reading across continuous review sessions.
- **JetBrains Mono**: Deployed selectively for dense technical metadata: Student Identification Numbers (e.g., `STU-6501024`), academic course catalog codes, ISO dates, log timestamps, and cohort quantitative analytics. Monospaced tabular alignment prevents column jitter in sorting grids.

Text contrast rules:
- Dark text on white/light surfaces defaults to full black (`#000000`) for primary readability, with muted copy using `#4B4B5A`.
- Solid buttons and high-urgency badges (`#3D348B`, `#F18701`, `#F35B04`) exclusively use crisp white text (`#FFFFFF`).
- Tertiary warnings (`#F7B801`) use pure black (`#000000`) to ensure strict AA accessibility compliance.

## Layout & Spacing

The layout is built upon an institutional 4px mathematical rhythm within a 12-column responsive fluid grid bounded at a maximum width of `1440px` (90rem).

- **Desktop (>= 1024px)**: 12-column grid, 20px (`1.25rem`) gutters, 32px (`2rem`) horizontal page margins. Left-hand navigation rail fixed at 260px width.
- **Tablet (768px – 1023px)**: 8-column grid, 16px (`1rem`) gutters, 24px (`1.5rem`) margins. Navigation shifts into a collapsible icon rail or sticky drawer.
- **Mobile (< 768px)**: 4-column grid, 16px (`1rem`) gutters, 16px (`1rem`) margins. Full-width stacked modules with horizontal scrolling for dense matrix tables.

Vertical density is calibrated specifically for multi-student supervision:
- Module separation maintains a consistent 32px (`2rem`) separation.
- Table row densities offer three distinct heights: `44px` for tight administrative matrices, `52px` standard for daily operations, and `64px` comfortable for listings featuring student profile images, dual statuses, and multi-line feedback.

## Elevation & Depth

This design system avoids dark or heavy drop shadows, instead using crisp 1px borders tinted in `#7678ED` and subtle, violet-infused ambient occlusion to preserve a pristine academic paper aesthetic.

- **Base Level (Level 0)**: Un-elevated flat white surfaces (`#FFFFFF`) layered on subtle page containers (`#F8F8FC`).
- **Standard Card (Level 1)**: Flat `#FFFFFF` surface enclosed by a 1px solid border in `#7678ED` at 40% opacity or `#E5E4F5`. Resting state has no shadow.
- **Interactive Card Hover (Level 2)**: The card transitions upward with a tinted ambient bloom:
  `box-shadow: 0 4px 12px rgba(61, 52, 139, 0.10); border-color: #7678ED;`
- **Active / Selected Surface (Level 3)**: Structural focus with high contrast:
  `box-shadow: 0 8px 24px rgba(61, 52, 139, 0.15); border: 2px solid #3D348B;`
- **Floating Modals & Inspection Drawers (Level 4)**: Modal dialogues use high-diffuse spread with a backdrop wash blur:
  `box-shadow: 0 20px 40px rgba(0, 0, 0, 0.12); backdrop-filter: blur(4px);`

## Shapes

The design system employs **Roundedness 2** (balanced 8px / 0.5rem standard rounding), delivering an approachable modern SaaS feel while respecting official university governance forms.

- **Micro Controls (Inputs, Form Fields, Dropdown Triggers)**: `6px` to `8px` corner radius. Maintains structural precision when nestled inside high-density tables.
- **Interactive Buttons & Base Cards**: `8px` (`0.5rem`) to `10px` radius for physical tactility.
- **Containers & Modal Drawers**: `16px` (`1rem`) radius to delineate distinct window contexts cleanly.
- **Indicators, Chips & Avatar Badges**: Complete circular radius (`9999px`) for full pill profiles, preventing visual collision with square structural table cells.

## Components

### Buttons
- **Primary CTA**: Solid fill in Violet Deep (`#3D348B`), white text (`#FFFFFF`), Inter Semi-Bold (600), 44px min height, 8px radius. Hover shifts to Violet Bright (`#7678ED`) over 120ms ease; active press downscales to 0.98.
- **Secondary / Outlined**: White background, 1px solid border in Violet Bright (`#7678ED`), black text (`#000000`). Hover induces a light violet background tint (`#EEEDFA`).
- **Urgent Action**: Deep Orange fill (`#F35B04`), white text, used strictly for non-compliance expulsion, rejection of logs, or urgent safety alerts.

### Status Badges & Chips
Rendered as 9999px pill shapes, 12px Inter Semi-Bold, with 4px vertical / 10px horizontal padding:
- **Approved / Active**: Violet Deep (`#3D348B`) fill with white text and trailing check icon.
- **Pending / In Review**: Orange (`#F18701`) fill with white text and clock icon.
- **Action Required / Missing Log**: Deep Orange (`#F35B04`) or Gold (`#F7B801`) fill with black text on gold, white on orange.
- **Draft / Incomplete**: White fill, 1px `#7678ED` border, black text.

### Input Fields & Search
- Standard height: 40px. Surface: `#FFFFFF`. Border: 1px solid `#7678ED` at 60% opacity, 8px radius.
- Focus: 2px solid `#3D348B` with a 2px outer halo ring in `rgba(118, 120, 237, 0.25)`.
- Integrated Search: Accommodates leading 20px stroke search icon and integrated trailing badge filters (Academic Year, Faculty Division, Status).

### Data Tables
- Sticky headers with a solid 1px `#7678ED` bottom divider, uppercase 12px Inter bold labels in Violet Deep (`#3D348B`).
- White rows alternating with subtle hover tint (`#EEEDFA`). Cell paddings strictly enforced at 16px horizontal.
- Student identifiers, log entry timestamps, and evaluation scores are rendered in `JetBrains Mono` for tabular scanning.

### Cards & Module Tiles
- **Weekly Log Submission Tile**: Displays student photo, week integer, submission timestamp in monospaced type, sign-off checkbox, and status badge. Missing logs flag a persistent gold border highlight (`#F7B801`).
- **Document Dropzone**: 2px dashed border in `#7678ED`, transitioning to solid `#3D348B` with a subtle lavender backdrop (`#F8F8FC`) upon drag-over.