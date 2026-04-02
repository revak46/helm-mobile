# MixFlow

**Audio intelligence — playlists shaped by vibe, not algorithm.**

---

## What It Is

MixFlow is planned as the audio layer of the Helm ecosystem. The idea: ingest your music library, extract schema (tempo, energy, mood, genre), and generate playlists by *vibe* — not by what a streaming algorithm thinks you want, but by how you actually feel.

Connected to HypeBoard moods. Connected to Pulse rhythms. Connected to pillar momentum. Your music taste shifts with your energy — MixFlow will see that.

---

## Core Concept

```
Audio Files  →  Schema Extraction  →  Personal Library  →  Playlists by Vibe
                (tempo, energy,        (your music,          (mood-matched,
                 mood, genre)           your metadata)        pillar-aware)
```

---

## Planned Stack

| Layer | Technology |
|-------|-----------|
| Backend | Python + Flask |
| Frontend | React (MyAtlas tab) |
| Audio processing | ffmpeg + librosa + pydub |
| Source | yt-dlp + Apple Music export |

---

## Cross-System Integration

| Connection | How |
|-----------|-----|
| HypeBoard moods | Current mood influences playlist suggestion |
| Pillar momentum | Hot pillars get energizing tracks, silent pillars get reflective ones |
| Pulse rhythm | Morning/midday/evening rotation shapes audio energy |
| Apple Shortcuts | Apple Music library export feeds the schema engine |

---

## Status

Planning only. No code built yet.

**Known blocker:** YouTube 403 (yt-dlp widespread issue). Apple Music library export via Shortcuts is the alternative data source.

---

## Vision

MixFlow doesn't replace Spotify or Apple Music. It *understands* your library in a way those services never will — because it knows your pillars, your moods, your rhythms. The playlist isn't an algorithm's guess. It's a reflection.

---

<p align="center"><sub>Part of the Helm ecosystem &middot; A.KEMBI &middot; 2026</sub></p>
