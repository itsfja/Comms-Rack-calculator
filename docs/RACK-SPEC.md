# Rack specification — reference data

Long-term reference for designing fascias, panels and mounts for this rack.
Measured values come from the owner's rack; standard values from the EIA rack
drawing (screenshot supplied 2026-10-16).

## Owner's rack (measured)

- Rack width, edge to edge: **281mm**
- Fascia width used by all existing fascias: **252mm** edge to edge
- Owner's working U height for quick measurements: **46mm** (approximation —
  use the standard 44.45mm for drawings)
- Cage mounting: M6 screws and cage nuts; nut rows measured **35mm apart**
  vertically in the cage wings (correction offsets applied per trial)

## Standard rack dimensions (EIA drawing)

- 1U height: **44.45mm** (1.75")
- Vertical hole group pattern within a U: 12.70mm (0.5"), 15.875mm (0.625"),
  15.875mm (0.625), 44.45mm (1.75") pitch
- 10" rack horizontal widths: inner pair **222.25mm** (8.75"), 236.525mm
  (9.312"), outer **254.00mm** (10")
- 19" equivalents: 450.85 / 465.12 / 482.60mm

## Fascia design rules (from the TerraMaster trials)

- The TerraMaster F4-425 Pro fascia is a **3.5U part**: 252 x 155.575mm,
  0.5mm trial depth / 3mm final depth
- Lower spar: exactly 1U (void bottom edge at y = 44.45 from plate bottom)
- Upper spar: 10mm
- Void: 180mm wide, 15mm-radius internal corners
- M6 clearance holes: Ø6.6, centred per U row, x per the 10" inner pair
  (14.875mm from each 252mm plate edge)
- Outer notches clear the tray-cage mounting: 16mm wide x 64mm tall

## Trial history (STL versions)

v5.6 (252mm plate) -> v5.7 (15mm radii) -> v5.8/v5.10 (spar corrections,
merged early by accident) -> v5.11 (void flush to NAS) -> v5.12 (Ø6 holes,
deeper notches, void pulled up) -> v5.13 (fourth hole row) -> v5.14 (notch
16x64, lower spar 24mm) -> v5.15 (standard-drawing dimensions, M6 holes).

Note: PRs merged mid-trial twice (#77, #80) — branches move fast during
trial cycles; only merge when the contributor says the branch is ready.
