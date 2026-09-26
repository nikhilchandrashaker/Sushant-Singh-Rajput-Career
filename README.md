# Sushant Singh Rajput — Career Dashboard

A single-file HTML dashboard built from `sushant_singh_rajput_career_dataset.xlsx`, covering his documented television and film career, box office, awards, collaborators, and shelved/unreleased projects.

## Files

| File | Description |
|---|---|
| `ssr_career_dashboard.html` | Self-contained dashboard. No build step, no dependencies — open it in any browser. |
| `sushant_singh_rajput_career_dataset.xlsx` | Source dataset (11 sheets: filmography, television, awards, box_office, ratings, roles_genres, collaborators, unreleased_projects, career_milestones, counterfactual_career, sources). |

## What's in the dashboard

- **Filmography** — all 12 film credits, 2013–2020, with billing and verdict
- **Box office** — India lifetime net for the 8 films with reported figures
- **Genres & archetypes** — frequency breakdown across his filmography
- **Television career** — 2008–2014, including the Pavitra Rishta breakthrough
- **Awards** — 9 wins of 21 nominations, with the televised and film awards separated
- **Repeat collaborators** — directors he worked with more than once
- **Unreleased/shelved projects** — Chanda Mama Door Ke, Paani, Takadum, Rifleman, Murli, each with a confidence label rather than a definitive claim

## A note on the counterfactual layer

The source spreadsheet reserves a `counterfactual_career` sheet with three scenarios (Conservative / Career Continuation / Ambitious) for 2021–2026, left intentionally blank. The dashboard keeps that layer unfilled and describes it structurally instead — cadence and genre-mix trends rather than invented film titles or outcomes for a real person. If you want to take this further, the natural next step is a rate model (release cadence × genre mix × historical box-office distribution) that outputs ranges rather than specific hypothetical projects.

## Sources

Wikipedia, Bollywood Hungama, IMDb, and Indian Express, as cited in the `sources` sheet of the dataset. Award totals and credit counts vary slightly by database depending on what's counted as a primary acting credit.
