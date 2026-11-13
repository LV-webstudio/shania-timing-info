**English** · [Español](README.es.md) · [Français](README.fr.md) · [Deutsch](README.de.md) · [Português](README.pt.md)

# Shania Timing

> A light, read-only dashboard that shows what each AI coding session is doing and how much time is left.

## What it is

Shania Timing collects a "heartbeat" from every AI coding session working on a project (state, task title, progress) and shows it in a small always-on-top desktop window and in a session dashboard. It is used inside the studio and is available on request for teams that work with several AI sessions. It only displays information and has no buttons that act on the sessions.

## Who it is for

- People who run several AI coding sessions or machines at once and keep asking "how long is left?".
- Available on request for teams that work with several AI sessions.

## What it does

- Per-session heartbeat with explicit states: in progress, waiting for the owner, waiting for a turn, waiting for a resource, cut short, done.
- A session with no recent heartbeat is shown as "no data", never as "in progress".
- Remaining-time estimate based on measured averages per task type and machine, not guesses; queue waits are shown separately from task time.
- Small frameless desktop window (Windows, Tauri) that stays on top; about 28 MB of RAM in the team's test.
- Dashboard page with one card per session, an animated chart of the AI usage quota, a timeline of the day, deployments and commits per repository. Read-only.
- Privacy filter: e-mail addresses, Spanish phone numbers and tax/ID numbers are redacted before anything is written; commit authors are not copied.

## Status

**In use (version 0.1.2), available on request**

Used inside the studio and available on request for teams that work with several AI sessions. No public download. Planned: replace the provisional icon, code signing and event-driven refresh.

## About this repository

This repository contains information only: the source code is private.

## Contact

- Email: hola@shaniawebstudio.com
- Website: https://shaniawebstudio.com

---
*A product by Shania Webstudio.* · Copyright (c) 2026 Shania Webstudio.
