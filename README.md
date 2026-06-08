# ⚽ World Cup 2026 — 🐔 Predictor

A self-contained, single-file web app to predict and simulate the **2026 FIFA World Cup** (48 teams, USA / Canada / Mexico). No build step, no dependencies — just open `index.html` in a browser.

## Features

- **Group stage** — all 72 group matches with score inputs; live standings, points, goal difference and FIFA tiebreakers for all 12 groups (A–L). Each match shows date, kickoff time, city, average temperature and altitude. Teams show their FIFA world ranking.
- **Best 3rd-placed teams** — ranks the 12 third-place finishers and marks the 8 that advance.
- **Knockout bracket** — a connected pyramid from the Round of 32 to the Final, using FIFA's official **Annexe C** third-place allocation table (all 495 combinations). Penalty-shootout picker for ties. Each match shows venue, date, time, temperature and altitude.
- **Advancing** — the teams reaching each round (R32 → R16 → QF → Top 4), with the final standings (1st–4th) decided by the final and 3rd-place match.
- **Goals** — every team ranked by goals scored; click a team to see its suggested top-3 national-team goalscorers (last ~24 months) with national-team penalty takers highlighted.
- **Live draw tracker** and **PDF export** of the full prediction. Scenarios auto-save to your browser.

## Usage

Open `index.html` in any modern browser. Everything runs client-side; your predictions are saved in `localStorage`.

## Data notes

- Fixtures, venues and the knockout structure follow the published 2026 schedule and FIFA regulations.
- Temperatures are late-June/July climate averages (not forecasts). FIFA rankings are the April 2026 reference. Suggested-goalscorer figures are reference/approximate, not live stats.
