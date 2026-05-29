# Team Effectiveness Instrument — demo

Interactive prototype of a team-effectiveness instrument for organizing federations. Built for PICO California DPI ahead of staff development week (June 22–25, 2026).

Scores each organizing team on Wageman & Hackman's three essential conditions — **Right People**, **Real Team**, **Compelling Purpose** — with the PICO organizing-context additions (powerful-leader rubric, 75% attendance bar, power play, federation representation).

Three views of the same data:
- **Scorecard** — per-team radar + bars + Health Index, with GitHub-style contribution grid showing balance across the three dimensions.
- **Effectiveness grid** — teams plotted on a 2×2: Organizer-led ↔ Leader-distributed × Reactive (mobilizing) ↔ Strategic (organizing). Quadrants labeled with the corresponding response ("Effective" / "Coach into strategy" / "Develop core leaders" / "Restart / rebuild").
- **Federation roll-up** — N effective / developing / stalled teams, distribution across quadrants, federation-wide flags.

Every field is tagged with its provenance — **CRM** (could be auto-filled from the org's CRM of record: Groundwork, EveryAction, Salsa, an Airtable base) or **Self** (coach / organizer judgment). Toggling "CRM connected" in the topbar shades the CRM-fillable fields so it's visually clear what is *not* self-report.

Demo only — no auth, no backend, no persistence. Includes seed data and an Export JSON button.

## Live

[lizmckenna.github.io/team-effectiveness-demo](https://lizmckenna.github.io/team-effectiveness-demo/)

## Run locally

Open `index.html` in any browser. No build step.

## Framework sources

- Wageman & Hackman — *Senior Leadership Teams: What It Takes to Make Them Great* (HBR Press)
- PICO California DPI — Lisa Aceves & Hannah Bermudez, "Effective Team Measurement Tool" (May 2026 draft)
- Obama '08 organizing — "Strategizing Sheet" and "OT Assessment" team worksheets
- Cushman (2014 / 2023) — 2×2 power-actor framing
