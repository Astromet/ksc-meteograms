# KXMR Model Meteograms

Live time-height meteograms for KXMR (Cape Canaveral SFS) from four models, drawn in the browser each time the page opens:

**https://astromet.github.io/ksc-meteograms/**

| Model | Source | Length |
|---|---|---|
| GFS 0.25° | Open-Meteo | 7 days |
| ECMWF IFS 0.25° | Open-Meteo | 7 days |
| UKMET (Met Office Global 10 km) | Open-Meteo | ~6.5 days |
| NAM 12 km | Iowa State BUFKIT profile for XMR | 84 hours |

Shading: RH ≥70/80/90%. Isotherms +5 to −20 °C (0 °C blue). Wind barbs colored by speed. Red NOW line at the current time.

No build step or scheduled job: `index.html` loads `meteogram.js`, which fetches the data and draws the chart.
