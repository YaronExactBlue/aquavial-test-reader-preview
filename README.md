# AquaVial Test Reader — preview build

A hosted preview of the AquaVial Test Reader, for trying the app on a phone or
desktop. Open the link, no install and no account:

**https://yaronexactblue.github.io/aquavial-test-reader-preview/**

This repository holds only the built page — a single self-contained HTML file
with the script, styles and vial photos inlined. The application source lives
elsewhere.

## What it is

A field app for running AquaVial water test kits: pick the method, record the
sample and incubation conditions, get reminded when the vial is due, then read
the result by colour change. Everything is stored in your own browser; there is
no server and no account.

## Before you rely on a result

The colour-difference thresholds that drive the suggested verdicts have **not
been calibrated** against AquaVial chemistry yet. Treat the app as a way to
record what you see, not as a second opinion — the operator's eye decides, and
the app says so throughout.

These kits are presumptive screening tests, not a certified laboratory
analysis, and today's range detects microbial contamination only. The full
disclaimer is shown in the app and travels with any result you export.

## Notes for testers

- **Use a phone if you can.** Photographing the vial is the core of the flow.
- Your data stays on your device. Clearing site data erases it, so export from
  Settings before you do.
- Reminders: the calendar file offered at the end of the start flow is the
  dependable option. A browser tab cannot wake itself hours later.
- Found something odd? The Settings screen exports a CSV with one row per vial
  reading — that plus a note about what you saw is the most useful bug report.
