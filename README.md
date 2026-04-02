# HELM

**Personal intelligence system built by A.KEMBI**

Helm is a signal-driven intelligence layer that turns daily noise into structured meaning. Every email, note, photo, and thought becomes a signal — classified, enriched, and connected to the arcs that define your life.

---

## The Ecosystem

| Surface | What It Does | Status |
|---------|-------------|--------|
| [**Live Dashboard**](https://revak46.github.io/helm-mobile/) | Pillar momentum, arcs, suggestions, AI digest | Live |
| [**Architecture**](https://revak46.github.io/helm-mobile/architecture.html) | Interactive system diagram with animated pipeline | Live |
| [**MyAtlas**](https://revak46.github.io/helm-mobile/myatlas.html) | The primary interface — orbital dial showcase | Live |
| [**HypeBoard**](https://revak46.github.io/helm-mobile/hypeboard.html) | Mood engine — swipeable quotes, vibes, energy | Live |
| [**Pulse**](PULSE.md) | Daily intention cards for the family | Live |
| [**MixFlow**](MIXFLOW.md) | Audio intelligence — playlists by vibe | Planning |

---

## Five Pillars

Every signal maps to what you've decided matters.

```
  Family     Travel     Photography     Growth     Finances
    |           |            |             |           |
    +-----+-----+-----+------+-----+------+-----+-----+
                       |                         |
                   [ HELM ]                 [ Bridges ]
                       |                         |
                  Intelligence              Connections
                  that adapts               you'd miss
```

---

## How It Works

```
Sources                    Pipeline                     Surfaces
─────────                  ────────                     ────────
Gmail          ──┐
HelmCapture    ──┼──▶  Capture ──▶ Enrich ──▶ Suggest  ──▶  MyAtlas
Manual notes   ──┘         │                     │       ──▶  Mobile Dashboard
                           ▼                     ▼       ──▶  Email Digest
                        Digest (AI)          State Layer  ──▶  Pulse
```

Full interactive architecture: **[View Pipeline Animation →](https://revak46.github.io/helm-mobile/architecture.html)**

---

## The Agents

| Agent | Role | Philosophy |
|-------|------|-----------|
| **Helm** | Intelligence core | Routes context, maintains state, strategic decisions |
| **Recon** | Builder | Four-phase: Research, Plan, Execute, Report |
| **Dash** | Auditor | Strengthens what ships — quality, security, confidence |

> *Dash doesn't audit Recon to catch failures. Dash audits to strengthen what ships.*

---

## Principles

- **Discuss before building** — propose before generating
- **Collaboration always** — excellence through connection, not competition
- **Identity with dignity** — agents have names, principles, and voice
- **Weight is a design smell** — ambient solutions over additive ones
- **Governance over convenience** — process is not overhead

---

## Infrastructure

Running on Mac Mini (Apple Silicon, 16GB) with 7 launchd services:

| Service | Schedule | Function |
|---------|----------|----------|
| Helm Capture | Always on | Signal intake, :7777 |
| Helm System | Always on | Health dashboard, :7778 |
| Helm Gmail | Hourly | Email intelligence fetch |
| Helm Refresh | Hourly | Full pipeline cycle |
| Helm Status Push | Hourly | Mobile dashboard update |
| Helm Outbox Digest | Daily 8am | Draft email via GitHub |
| Helm Outbox Poller | Every 15 min | Send approved emails |

---

<p align="center">
  <strong>Built with intention. Powered by Helm Intelligence.</strong><br>
  <sub>A.KEMBI &middot; 2026</sub>
</p>
