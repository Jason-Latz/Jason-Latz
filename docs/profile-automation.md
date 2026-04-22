# Profile Automation Notes

This profile repo only keeps automation that updates content the README
actually renders.

## Active generators

- `.github/workflows/activity-graph.yml` refreshes the
  `profile-3d-contrib/*.svg` files that power the contribution graph section.
- `.github/workflows/recent-activity.yml` rewrites the
  `<!--RECENT_ACTIVITY:start-->` block inside `README.md`.

## Removed generator

The old metrics workflow wrote `assets/metrics.svg` and `github-metrics.svg`,
but the README no longer referenced either file. Keeping that workflow meant:

- an extra scheduled Actions run every day
- generated-file churn with no visible effect on the profile
- more maintenance surface for a repo that is mostly static markdown

That workflow and its unused artifacts were removed so scheduled work stays
tied to assets the profile actually shows.

## Rule for future automation

Before adding a new profile generator, make sure its output is linked from
`README.md` or another published surface in this repository.
