# VEVOR Weather Station · App Prototype

Single-file interactive prototype (`index.html`, no build step, no external assets). All data is simulated.

Live preview: https://cqxkm289-dev.github.io/Weather-Station-App-Prototype/

## Redesign requirements covered

| ID | Requirement | Where to see it |
|---|---|---|
| P0-01 | Each metric opens its own detail page (no tab jump); back restores scroll | Home → tap any tile |
| P0-02 | History stats change with Day / Week / Month / Year | History |
| P0-03 | Contrast: solid cards with dark text, darker sky, no photo background | All pages |
| P0-04 | Consistent status text; status chips use icon + text, not color only | Devices → Device health |
| P1-01 | Hero order: condition → temperature → feels like / high-low → freshness | Home |
| P1-02 | Wind compass, pressure trend arrow, rain rate, 24 h temperature sparkline | Home |
| P1-03 | Issue banner on Home links to device health / diagnostics | Home (Lakeside Station) |
| P1-04 | Two card styles only: metric tile and list row | Home |
| P1-05 | Dedicated icons (wind, gauge, barometer, moon phase, station tab) | All pages |
| P1-06 | One "Demo · simulated data" label per page; ⓘ for calculated values | All pages |
| P2-01 | History headline numbers, drag-to-read chart, metric switcher, legend | History |
| P2-02 | Compare previous period uses an iOS switch | History |
| P2-03 | Alert templates: Frost, High wind, Heavy rain, Heat | Alerts |
| P2-04 | Alert form: units on threshold, range validation, live preview | Alerts → template / Create |
| P2-05 | iOS-style back (`‹ Home`) and left-edge swipe back | Any detail page |
| P2-06 | Units (°F/°C, mph/km/h, inHg/hPa, in/mm), station switcher, offline state, dark mode | Settings icon; station name; Backyard Station |
| P2-07 | Tabular figures for all numbers | All pages |
| P2-08 | Page title is the product name | Browser tab |
