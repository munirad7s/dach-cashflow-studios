# Design System: DACH Cashflow & Sovereign Legal-Engineering Studios

## 1. Visual Theme & Atmosphere
An authoritative, Swiss-German Private Bank and Sovereign Legal-Engineering Cockpit (Density 8, Variance 7, Motion 6). The interface pairs gallery-grade editorial typography with high-density tabular financial telemetry. Every statutory calculation (Art. 16 DSA, Section 615 BGB, ECJ C-264/23, Section 7g EStG, Section 7a SGB IV) is presented like an audited Bundesbank or Big-Four dossier: dark architectural slate surfaces, crisp 1px hairline ledger dividers, asymmetric split-screen proportions, and tabular monospace figures.

## 2. Color Palette & Roles
- **Obsidian Slate** (#090A0F) — Primary background canvas (never pure #000000)
- **Graphite Ledger** (#11131A) — Elevated container, dossier panel, and interactive calculator surface
- **Elevated Carbon** (#171A24) — Hover state and active row highlight surface
- **Alabaster Ink** (#F4F4F6) — Primary headline and critical figure ink
- **Muted Titanium** (#8E929F) — Secondary descriptions, statutory citations, and court case references
- **Hairline Rule** (rgba(244, 244, 246, 0.09)) — 1px structural architectural grid borders and table dividers
- **Sovereign Emerald** (#1E9E6A) — Single calibrated accent (saturation < 80%) for verified EUR recovery yields, primary action triggers, and focus rings

## 3. Typography Rules
- **Display:** Outfit — Track-tight (-0.03em), controlled architectural scale, weight-driven hierarchy (600–700)
- **Body:** Geist — Relaxed leading (1.6), 65ch max-width, Muted Titanium (#8E929F) for narrative copy
- **Mono:** JetBrains Mono — Mandatory for all EUR figures, statutory citations, case numbers (BGH VI ZR 34/15, EuGH C-264/23), percentages, and MVP indices with `tabular-nums`
- **Banned:** Inter, generic serif fonts, neon gradients, outer button glows, and decorative emojis

## 4. Component Stylings
* **Buttons:** Flat architectural rectangles with 6px radius, no outer glow. Tactile -1px translate on active state. Sovereign Emerald (#1E9E6A) fill with #F4F4F6 text for the single primary CTA; 1px Hairline Rule outline for secondary actions.
* **Dossier Panels & Ledgers:** High-density border-top and 1px hairline structural grid cells instead of floating drop-shadow cards. Subtle 8px radius on outer containers only.
* **Inputs & Search:** Label above input in uppercase JetBrains Mono (11px, letter-spacing 0.08em). Graphite Ledger (#11131A) fill with 1px Sovereign Emerald focus border.
* **Loaders:** Skeletal shimmer matching exact row dimensions.
* **Empty States:** Structured statutory query reset prompt.

## 5. Layout Principles
- Asymmetric 7:5 Split Hero: Left column houses the typographic thesis with inline visual pills and a single primary CTA; Right column houses the live interactive B2B Outbound Telemetry Ledger.
- No 3-column equal card grids: Flagship B2B Snipers use an asymmetric 2-column editorial feature matrix + full-width tabular audit ledger.
- Contained within a 1380px max-width architectural grid with 1px exposed structural hairlines.
- Strict single-column collapse below 768px with zero horizontal overflow.

## 6. Motion & Interaction
- Spring physics (`cubic-bezier(0.22, 1, 0.36, 1)`) on all interactive row expansions, filter transitions, and drawer reveals.
- Subtle live status pulse dot on the active telemetry header.
- Hardware-accelerated `transform` and `opacity` transitions only.

## 7. Anti-Patterns (Banned)
- No emojis anywhere in the interface
- No Inter font
- No pure black (#000000)
- No AI purple/blue neon gradients or outer glow shadows
- No 3-column equal feature card rows
- No centered Hero sections
- No generic placeholder names or fake round percentages
