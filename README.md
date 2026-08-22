# Euchre Tracker — releases

The release history for **Euchre Tracker**, the euchre game tracker my cousins
and I use on game nights.

**[Open the app →](https://euchre-tracker-chi.vercel.app)** ·
**[What's new →](https://euchre-tracker-chi.vercel.app/whats-new)**

## There is nothing to download

Euchre Tracker is a web app. It updates by being deployed, so — unlike my
desktop apps — there is no `.dmg` here and no updater reading this repo. Every
release carries notes only.

This repo exists so the release history has a permanent public home outside the
app: the source repository is private, so these releases and the app's own
What's New page are the whole public record.

## What's in here

- **[Releases](../../releases)** — one per version, `v0.1.0` through today.
- **`releases/`** — the same notes as markdown files, one commit per version,
  each tagged. The commit graph is the release history.

Everything is generated from the app's `CHANGELOG.md` by
`scripts/publish-releases.mjs`, so a release is worded identically here and on
the site. Releases before **v2.3.0** predate the changelog and were
reconstructed from the roadmap; each one says so.

## The versions

| | |
|---|---|
| **2.x** | Rebuilt on a design system, moved to the cloud, opened up to more than four players |
| **1.x** | Analytics, duo and head-to-head records, the Hall of Fame |
| **0.x** | October 2025 — the first hand ever recorded |
