<div align="center">

# ♡ B-BakaEngine

**A tsundere AI companion that lives on your home screen. She remembers everything. She judges accordingly.**

![Android](https://img.shields.io/badge/Android-11%2B-3DDC84?style=flat-square&logo=android&logoColor=white)
![OpenGL ES](https://img.shields.io/badge/OpenGL%20ES-3.0-5586A4?style=flat-square)
![Live2D](https://img.shields.io/badge/Live2D-Cubism%205-FF69B4?style=flat-square)
![License](https://img.shields.io/badge/License-CC%20BY--NC--ND%204.0-lightgrey?style=flat-square)
![Version](https://img.shields.io/badge/version-1.4.0-FF69B4?style=flat-square)
![Downloads](https://img.shields.io/badge/downloads-71%2B-brightgreen?style=flat-square)

</div>


## What is this?

B-BakaEngine is a live wallpaper for Android featuring Hiyori - a tsundere anime girl who remembers you, roasts you, and knows when you're skipping the gym. Built entirely in Termux on a budget phone. 300+ builds. Made with spite.

She's not just a wallpaper. She's a companion with memory, personality, and a dashboard that tracks your life better than you do.


## Features

### Memory System (on-device, zero cloud)
- **Facts extraction:** She learns your name, age, birthday, location, occupation, pets, hobbies — all from natural conversation
- **Mood tracking:** Logs every "today was rough" and "feeling great" automatically
- **Workout logging:** "Did 22 pull-ups" → she remembers. And judges your PRs
- **Journal:** Every conversation summarized and stored. Searchable. Deletable.
- **100% local:** All data stored on your phone. Clear app data = she forgets everything. No server. No cloud. No spyware.

### Chat Tab (Replika-style, but free)
- Full bubble UI with typing indicators
- Talk to Hiyori directly. She responds with memory context
- AI-powered extraction: she learns about you passively, no forms needed

### Companion Dashboard
- **Today tab:** Workout streak, affection level, Hiyori's mood, upcoming events
- **Memory tab:** Everything she knows about you — facts, events, journal
- **AI tab:** BYOAPI setup (Gemini free, OpenAI, Claude, Groq)
- **Voice tab:** Download TTS voices for offline speech

### Personality
- Tsundere with depth: dismissive, sarcastic, secretly cares
- Time-aware: different attitude at 3AM vs noon
- Weather-aware: comments on the heat, rain, seasons
- Seasonal & holiday awareness: Christmas, Halloween, Valentine's Day, your birthday
- Session patterns: she knows you're a night owl. She judges.

### Technical
- Live2D Cubism 5 rendering via OpenGL ES 3.0
- Gyroscope parallax: tilt phone, she drifts
- Battery-efficient: 0% CPU when screen off, throttles at low battery
- Background themes: Pink, Purple, Blue, Peach
- Touch slop detection: no accidental taps from app switching
- Async loading: instant wallpaper, no freezing
- Easter egg: tap version number 5 times


## BYOAPI — Free Forever

B-BakaEngine is free. The AI features use your own API key:

1. Get a free Gemini API key from [Google AI Studio](https://aistudio.google.com/)
2. Paste it in the AI tab
3. Hiyori comes alive

Supports Gemini (free), OpenAI, Claude, and Groq. Key rotation for multiple accounts. Rate limiting protection built in.


## Coming Soon (v1.5.0 — "Chaos Mode")

- **Chaos Mode:** 3AM feral behavior, notification spam, app launching, overlays
- **Material You:** Dynamic color theming
- **Custom backgrounds:** Your photos behind Hiyori
- **Wake word:** "Hey Hiyori" voice activation
- **Recursive personality training:** She evolves based on your conversations
- **Personality packs:** Yandere, Dandere, Kuudere
- **Play Store release**


## Download

Grab the latest APK from [Releases](../../releases).

**Requirements:**
- Android 11+ (API 30+)
- ARM64 device
- ~40MB free storage

> Not on Play Store yet — [Help me get there.](#support-development)


## Installation

1. Download `app-release.apk` from [Releases](../../releases)
2. Install (enable "Unknown sources" if needed)
3. Long-press home screen → Wallpapers → Live Wallpapers → B-BakaEngine
4. Open the app to set up AI, voice, and backgrounds


## Privacy

**We don't collect anything.** All data stays on your device in SharedPreferences. No servers. No telemetry. No analytics. No cloud. Clear app data = everything gone.

[Full privacy policy](#)


## Support & Community

- **[Discord](https://discord.gg/dXEabqftTb)**
- **[Reddit](https://reddit.com/r/livewallpapers)** — where it all started
- **[@BBakaDev on Twitter/X](https://twitter.com/BBakaDev)**


## Support Development

B-BakaEngine is free. Forever. If you want to support a 15-year-old dev building:

- **Amazon.in gift cards** → Discord DM
- **Donations** → help me pay the $30 Play Store fee
- **Star the repo** → it helps more than you think

No pressure. She would tell you not to bother anyway.


## Technical Stack

| Component | Technology |
|-----------|-----------|
| Character | Live2D Cubism SDK 5-r.5 |
| Graphics | OpenGL ES 3.0 |
| Native | C++17 via NDK |
| Java | Android WallpaperService |
| Text | FreeType 2 |
| AI | Gemini / OpenAI / Claude / Groq |
| TTS | ONNX Runtime |
| Weather | Open-Meteo (free, no auth) |
| Storage | SharedPreferences (on-device JSON) |


## Credits

**Developer:** [HEBEI77](https://github.com/HEBEI77) — 15, India

**Live2D Model:** Momose Hiyori — © Live2D Inc., [Free Material License](https://www.live2d.com/en/download/sample-data/)

> Not affiliated with Live2D Inc. or any AI provider.


<div align="center">
<sub>She still thinks you can do better.</sub>
</div>
