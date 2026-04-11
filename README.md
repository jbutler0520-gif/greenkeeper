# Links Lab Greenkeeper

A 5-app operating system for golf course maintenance teams, built for Haggin Oaks Golf Complex (MacKenzie Course, 1932 / Arcade Creek, 1952).

**Live demo:** open `index.html` in any browser (or visit the GitHub Pages URL for this repo).

## Apps

| Role | File | What it does |
|---|---|---|
| Superintendent | `greenkeeper-super-v1.html` | Daily ops, spray & fertility, course health, green speed, aeration, **soil moisture (POGO sensor network)**, irrigation, pin sheets, tasks |
| Director | `greenkeeper-director-v1.html` | Budget, labor, capital projects, member comms |
| Mechanic | `greenkeeper-mechanic-v1.html` | Fleet status, PMs, repairs, parts, downtime, cost tracking |
| Crew | `greenkeeper-crew-v1.html` | Daily assignments, timecards, training |
| Super in Training | `greenkeeper-training-v1.html` | Curriculum, cert tracking, field notes |

## Tech

Pure vanilla HTML + CSS + JavaScript. Zero dependencies, zero build step, works offline, loads from `file://` or any static host.

## Flagship feature: Soil Moisture

Superintendent app → **Soil Moisture** tab. 38 POGO sensors across MacKenzie (18), Arcade Creek (18), and 2 practice greens. Live VWC, soil temp, EC salinity, Clegg firmness, battery & signal per probe. 14-day trend with ET₀ overlay. Tonight's irrigation plan with savings calc. YTD ROI: 1.84M gallons saved, $14,200, 186 labor hours, +8% NDVI.

## License

All rights reserved — Josh Butler, 2026.
