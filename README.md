# CampusConnect

A student-built platform for the University of South Carolina, bringing navigation, dining, study spots, accessibility info, groups, events, and student recommendations into one place — instead of the four or five separate apps campus life currently runs on.

Built by [Alyssia Gaston](https://alyssia-gaston.netlify.app) — Computer Science student at UofSC.

**Launching for UofSC: August 18, 2026**

## What's in this repo

- **`/launch-page`** — the public pre-launch page (live at campusconnect-uofsc.netlify.app), email signup, countdown, project story.
- **`/platform`** — the full product prototype: campus map, social feed, groups & DMs, events with RSVP, study spot & dining directories, content moderation, and more.

## Status

This is a front-end prototype. Every feature is fully designed and working, but currently runs on in-memory fake data — nothing persists past a page refresh yet. A real backend (Supabase: Postgres + auth + storage) is the deliberate next step, once every feature is fully built and tested against fake data first.

## Running it locally

Both `/launch-page` and `/platform` are single-file HTML apps with no build step. Open `index.html` directly in a browser, or drag the folder into Netlify.

**Note:** each folder's `index.html` references photo assets by relative filename — keep every file in the same folder when deploying.

## Tech

Vanilla HTML/CSS/JS, no framework, no dependencies. Design system: garnet/black/white, built to feel like "a legal brief crossed with a code terminal."
