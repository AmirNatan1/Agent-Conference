# Industry grid images

The grid renders 8 cells (4 across x 2 rows). Each cell loads `INDUSTRIES/<slug>.jpg`.
A missing file degrades gracefully to a dark hatched tile with the label still shown.

| Cell | Required filename | Status |
|---|---|---|
| Industry 4.0 | `industry-4-0.jpg` | **needed** |
| Physical AI & Robotics | `physical-ai-robotics.jpg` | placeholder (from old composite) |
| Defense | `defense.jpg` | placeholder (from old composite) |
| Energy & Climate | `energy-climate.jpg` | **needed** |
| Infrastructure | `infrastructure.jpg` | **needed** |
| Logistics & Supply Chain | `logistics-supply-chain.jpg` | **needed** |
| Maritime | `maritime.jpg` | placeholder (from old composite) |
| Automotive & Mobility | `automotive-mobility.jpg` | placeholder (from old composite) |

Guidance: landscape, roughly 4:3, min 800px wide. Colour is fine — the CSS applies
`saturate(0) brightness(0.45) contrast(1.1)`, so everything renders black and white to match.
