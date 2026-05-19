# Project Saucony23 — Running Dashboard

Interactive single-page dashboard summarizing 14 months of Garmin running activity (March 2025 – May 2026) and a 12-week training plan to reach a 7:30 min/mile pace.

## What's in here

**`Running Dashboard.html`** — open in any modern browser. Everything (data, charts, plan) is embedded in the single file; no build step, no server.

## Sections

- **Stats** — Total miles, total runs, best pace, recent pace, improvement, average HR.
- **Activity calendar** — Per-month grids, each day shaded by that day's average pace (green = fast, red = slow). Hover for details.
- **Monthly mileage** — Bar chart, bars colored by that month's average pace.
- **Monthly average pace** — Line with goal line at 7:30.
- **Per-run pace** — Every run plotted with a 5-run rolling average overlay.
- **Heart rate vs pace** — Scatter with recent runs highlighted; demonstrates aerobic efficiency gains.
- **Insights** — Plain-language summary of trends.
- **Training zones** — Easy / Long / Tempo / VO₂ / Goal pace targets.
- **12-week plan** — Base → Build → Peak → Test, with daily workouts.

## Key trends from the data

- Pace dropped ~85 sec/mi from mid-2025 (~10:00) to spring 2026 (~8:30).
- Heart rate held steady at ~150 bpm while pace got faster — classic aerobic-efficiency signature.
- Cadence climbed from ~158 to ~170 spm.
- Monthly volume grew from ~15 mi/mo to ~50 mi/mo once training got consistent in January 2026.

## Goal

Sustain a 7:30 min/mile pace, starting from a current 10-run average of ~8:30 and a single-run best of 8:07. The plan covers 12 weeks of structured periodization, ending with a 5K time trial at goal pace.

## Stack

- Plain HTML + CSS
- [Chart.js](https://www.chartjs.org/) via CDN
- All data inlined as JSON (no external fetches)
