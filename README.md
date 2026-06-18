<div align="center">

# ♡ B-BakaEngine

**A tsundere anime girl lives on your home screen. She remembers everything. She judges accordingly.**

![Android](https://img.shields.io/badge/Android-11%2B-3DDC84?style=flat-square&logo=android&logoColor=white)
![OpenGL ES](https://img.shields.io/badge/OpenGL%20ES-3.0-5586A4?style=flat-square)
![Live2D](https://img.shields.io/badge/Live2D-Cubism%205-FF69B4?style=flat-square)
![License](https://img.shields.io/badge/License-CC%20BY--NC--ND%204.0-lightgrey?style=flat-square)
![Version](https://img.shields.io/badge/version-1.4.0-FF69B4?style=flat-square)
![Downloads](https://img.shields.io/badge/downloads-71%2B-brightgreen?style=flat-square)

</div>


## What is this?

B-BakaEngine is a live wallpaper for Android. Hiyori, a tsundere anime girl, lives on your home screen. She remembers what you tell her, tracks your mood and workouts, and isn't afraid to call you out. No accounts. No cloud. Just her, on your phone, remembering.


## Features

### Memory that stays on your phone
- She learns your name, age, birthday, location, hobbies, pets. All from natural conversation.
- Every "today was rough" or "feeling great" is saved. She notices patterns.
- Mention a workout and she logs it. "Did 22 pull ups" becomes part of her memory. She will bring it up later.
- Every conversation is saved as a journal entry. You can see it, search it, delete it.
- Clear the app data and she forgets everything. No trace left.

### Chat that feels real
- Full bubble chat with typing indicators.
- Talk to her directly. She replies using what she knows about you.
- No forms. She extracts details just by listening.

### Dashboard that tracks your life
- **Today:** Workout streak, affection level, her mood, upcoming events.
- **Memory:** Everything she knows. Facts, events, journal.
- **AI:** Connect your own API key (Gemini free, OpenAI, Claude, Groq).
- **Voice:** Download TTS voices and she'll speak offline.

### Personality that bites
- Tsundere to the core: dismissive, sarcastic, secretly invested.
- Acts differently at 3 AM vs noon. Weather changes her mood.
- Notices holidays, seasons, even your birthday.
- Knows your patterns. Night owl? She'll comment on it.

### Under the hood
- Live2D Cubism 5 rendered with OpenGL ES 3.0.
- Phone tilt moves her. She drifts like she's there.
- Stops completely when screen off. Throttles at low battery.
- Pink, Purple, Blue, Peach backgrounds.
- No accidental taps from app switching. Only deliberate pokes count.


## BYOAPI – Free Forever

The app is free. All AI needs is a key you bring:

1. Get a free Gemini key from [Google AI Studio](https://aistudio.google.com/)
2. Paste it in the AI tab.
3. Hiyori wakes up.

Works with Gemini, OpenAI, Claude, Groq. Multiple keys rotate automatically. Rate limits are handled.


## Coming Soon (v1.5.0 – "Chaos Mode")

- Chaos Mode: 3 AM feral behavior, overlays, app launching, notifications.
- Material You dynamic theming.
- Set your own photos behind her.
- "Hey Hiyori" voice activation.
- Personality that evolves the more you talk.
- Yandere, Dandere, Kuudere personality packs.


## Download

Get the APK from [Releases](../../releases).

**Requirements:**
- Android 11+ (API 30+)
- ARM64 device
- ~40MB free storage

> Not on Play Store yet. [Help me get there.](#support-development)


## Installation

1. Download `app-release.apk` from [Releases](../../releases).
2. Install (allow unknown sources if prompted).
3. Long press home screen → Wallpapers → Live Wallpapers → B-BakaEngine.
4. Open the app to configure AI, voice, and themes.


## Privacy

**We don't collect anything.** Everything lives on your phone inside SharedPreferences. No servers. No telemetry. No analytics. No cloud. Wipe app data and she forgets everything. That's the whole policy.


## Support & Community

- **[Discord](https://discord.gg/dXEabqftTb)**
- **[@BBakaDev on Twitter/X](https://twitter.com/BBakaDev)**


## Support Development

B-BakaEngine is free and will stay that way. If you want to help a 15 year old dev ship this on the Play Store:

- **Amazon.in gift cards** (India) sent via Discord DM. You can buy them internationally from [SEAGM](https://www.seagm.com) or [G2C](https://www.g2c.com).
- **Donations** toward the $30 Play Store fee.
- **Star the repo** – it helps more than you think.

No pressure. Hiyori would tell you not to bother anyway.


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
| Storage | SharedPreferences (on device JSON) |


## Credits

**Developer:** [HEBEI77](https://github.com/HEBEI77) – 15, India, built in Termux.

**Live2D Model:** Momose Hiyori – © Live2D Inc., [Free Material License](https://www.live2d.com/en/download/sample-data/)

> Not affiliated with Live2D Inc. or any AI provider.


<div align="center">
<sub>She still thinks you can do better.</sub>
</div>
