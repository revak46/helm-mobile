# MyAtlas

**Your life, mapped with intention.**

> The primary interface for the Helm intelligence system. Web, desktop, and mobile.

---

## What It Is

MyAtlas is where signals become visible. Every email, note, photo, and thought that Helm captures surfaces here — classified by pillar, enriched with context, linked to the arcs that define what's happening in your life.

Not a dashboard. Not a to-do app. A personal atlas — a map of where your energy flows and where attention is needed.

---

## Views

| View | Purpose |
|------|---------|
| **Pods** | Signal cards grouped by pillar — tap to explore, filter by tag |
| **Week** | Seven-day timeline with signal density and arc overlap |
| **Day** | Travel arcs on dial, swimlane bars, trip panel with status chips |
| **Helm** | 5 pillar buckets, AI digest, suggestions with human reactions (+/→/✕) |

---

## The Stack

| Layer | Technology |
|-------|-----------|
| Frontend | React + TypeScript + Vite |
| Desktop | Tauri wrapper |
| Mobile | Expo SDK 54 + React Native |
| Intelligence | Helm Capture API (:7777) |
| Hosting | Vercel (web), local (desktop) |

---

## Signal Intelligence

Every signal carries:
- **Pillar classification** — which of the five pillars it belongs to
- **Enrichment block** — corrected pillar, cluster, group, arc links
- **Source tracking** — gmail, capture app, manual, photo vision
- **Timestamp + context** — when it arrived, what triggered it

The Helm tab shows these as interactive cards with AI-generated digest and actionable suggestions. React with +/→/✕ to train the system.

---

## Five Pillars in MyAtlas

```
┌──────────┐ ┌──────────┐ ┌──────────┐ ┌──────────┐ ┌──────────┐
│  Family   │ │  Travel  │ │  Photo   │ │  Growth  │ │ Finances │
│           │ │          │ │          │ │          │ │          │
│  Silent   │ │   Hot    │ │   Hot    │ │   Hot    │ │  Silent  │
│  0 signals│ │ 9 signals│ │13 signals│ │30 signals│ │ 1 signal │
└──────────┘ └──────────┘ └──────────┘ └──────────┘ └──────────┘
```

Momentum tracking shows heat at a glance. Hot pillars have active arcs driving them. Silent pillars need attention — or permission to rest.

---

## Arc Narratives

Signals cluster into arcs — ongoing stories that cross pillars:

- **Houston Trip** — Photography + Travel (6 signals)
- **Photography Gear Audit** — Photography (10 signals)
- **Device Inventory** — Growth + Photography + Work (11 signals)
- **Intentional Curation** — Finances + Travel (6 signals)
- **DBA Growth** — Growth (2 signals)
- **Photography Community** — Photography + Travel (2 signals)

Cross-pillar bridges reveal connections you'd otherwise miss.

---

## Live

| Surface | URL |
|---------|-----|
| Web | [myatlas-nine.vercel.app](https://myatlas-nine.vercel.app) |
| Desktop | Tauri build (local) |
| Mobile | Web preview (native blocked on EAS Build) |

---

<p align="center"><sub>Part of the Helm ecosystem &middot; A.KEMBI &middot; 2026</sub></p>
