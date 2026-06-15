# Barter Checklist Changelog

## v1.4.2 — 2026-06-15
- Reduced trade row horizontal padding to prevent long material names from wrapping

## v1.4.1 — 2026-06-15
- Material checkboxes moved to the right side of each material row

## v1.4 — 2026-06-15
- Added wiki item icons next to each material ingredient
- Added wiki item icons next to each barter trade item; icon spans full row height

## v1.3.3 — 2026-06-15
- Switched to 4-column grid on desktop, 1-column on mobile

## v1.3.2 — 2026-06-15
- Added viewport meta tag so mobile browsers respect screen width
- Raised mobile breakpoint to 768px for single-column layout

## v1.3.1 — 2026-06-15
- Fixed recipe tooltip clipping caused by overflow on material list container

## v1.3 — 2026-06-15
- Added individual material checkboxes — tick each ingredient separately; trade auto-checks when all materials are done
- Clicking a trade row quick-toggles all materials at once
- Added collapsible Materials divider per trade to show/hide ingredients
- Full-width clickable material rows with thin dividers between them
- Clicking a location header (e.g. Karu Forest) toggles all trades and materials in that location

## v1.2.2 — 2026-06-15
- Fixed Shrimp Taming Bait recipe tooltip to account for yield of 10 per craft

## v1.2.1 — 2026-06-15
- Recipe tooltip ingredient quantities now scale by barter trade amount

## v1.2 — 2026-06-15
- Added recipe tooltips on material hover showing required ingredients
- Fixed tooltip clipping; tooltips now position below the material label

## v1.1 — 2026-06-15
- Location sections arranged in 2×2 grid on desktop, collapses to 1 column on mobile

## v1.0 — 2026-06-15
- Initial release — weekly barter trade tracker for Karu Forest, Oasis, Calida, and Pera
- Checkbox UI per trade; currency label corrected to Ducats
- Auto-resets on weekly rollover via localStorage
