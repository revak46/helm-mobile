# Pulse

**Daily intention cards for the people who matter.**

---

## What It Is

Pulse generates a daily card — a moment of intention delivered every morning at 7am. Not a notification. Not a reminder. A designed moment that says *this is what today could hold*.

Two cards. Two people. Two design languages.

---

## The Cards

| Recipient | Design | Aesthetic |
|-----------|--------|-----------|
| **Ideka** | Warm honey | Gold shimmer, particle drift, Cormorant Garamond |
| **Yemi** | Dark bold | Blue accent, clean geometry, SF Pro |

Each card carries a rotation theme: **Deepen**, **Think**, or **Smile**. The theme shapes the quote, the energy, and the visual treatment.

---

## How It Works

```
7:00 AM  →  pulse_builder.py runs via launchd
         →  Reads rotation schedule (30-day cycle)
         →  Selects quote matching today's theme
         →  Generates styled HTML card
         →  Deploys to Vercel
```

No AI in the loop. Pure design automation. The builder knows the schedule, the quotes, and the aesthetic. It builds and ships.

---

## Current Cycle

- **Dates:** Mar 10 – Apr 8, 2026
- **Rotation:** Deepen → Think → Smile (repeating)
- **Day count:** 30-day cycle

---

## Live

| Surface | URL |
|---------|-----|
| Ideka's card | [pulse-ruddy-three.vercel.app](https://pulse-ruddy-three.vercel.app) |
| Yemi's card | /me.html (same domain) |

---

<p align="center"><sub>Part of the Helm ecosystem &middot; A.KEMBI &middot; 2026</sub></p>
