<div align="center">

# B-BakaEngine

**A Live2D anime wallpaper for Android — she's alive, she's reactive, and she absolutely did not miss you.**

![Android](https://img.shields.io/badge/Android-11%2B-3DDC84?style=flat-square&logo=android&logoColor=white)
![OpenGL ES](https://img.shields.io/badge/OpenGL%20ES-2.0%2F3.0-5586A4?style=flat-square)
![Live2D](https://img.shields.io/badge/Live2D-Cubism%205-FF69B4?style=flat-square)
![License](https://img.shields.io/badge/License-CC%20BY--NC--ND%204.0-lightgrey?style=flat-square)
![Version](https://img.shields.io/badge/version-1.1.0-FF69B4?style=flat-square)

</div>


## What is this?

B-BakaEngine is a live wallpaper for Android featuring a tsundere anime girl powered by Live2D Cubism 5. She renders directly on your home screen using native OpenGL ES, reacts to your taps, and responds differently depending on the time of day, how often you bother her, and how patient she's feeling.

The only Live2D wallpaper with weather, memory, time-of-day, and seasonal awareness built into a native C++ engine. She is not impressed by you. Probably.


## Features

- **Live2D rendering:** smooth, real-time character animation directly on your wallpaper
- **Tap interaction:** tap her and she reacts. Tap too much and she gets annoyed
- **Time-aware dialogue:** different responses at 3AM vs 6AM vs noon. She notices
- **Weather-aware dialogue:** she comments on the weather outside
- **Tap escalation:** the more you tap, the more done with you she becomes
- **Battery efficient:** 0% CPU usage when screen is off. ~5 minutes 19 seconds per 1% battery drain screen-on, running a full Live2D model with physics. Throttles to 30fps when battery is low and unplugged
- **Gyroscope parallax:** tilt your phone and she drifts with it. Smooth, natural, like she's floating
- **Battery-aware dialogue:** she reacts to your battery level. Panics at 5%. Judges you at 30%
- **Background themes:** pick from Pink, Purple, Blue, or Peach in the settings app
- **Async loading:** wallpaper appears instantly, no freezing while assets load
- **Memory system:** she remembers how often you tap her. Affection (or irritation) persists across reboots, with natural decay over days
- **Seasonal & holiday awareness:** dialogue shifts with the month, season, and holidays. She knows what time of year it is

### Coming Soon

- Voice keyword detection: she hears you
- Outfit and expression packs
- Personality modes
- LLM integration: real responses, not just dialogue arrays


## Download

Grab the latest APK from [Releases](../../releases).

**Requirements:**
- Android 11 or higher (API 30+)
- ARM64 device
- ~25MB free storage

> Sideloading required — not on Play Store yet. Enable "Install from unknown sources" in your Android settings.


## Installation

1. Download the latest `app-release.apk` from [Releases](../../releases)
2. Open the APK on your device and install it
3. Go to **Settings → Wallpaper & Style** (or your launcher's wallpaper picker)
4. Select **Live Wallpaper → B-BakaEngine**
5. Apply and enjoy


## Support & Community

Got feedback, found a bug, or just want to hang out?

**[Join the Discord](https://discord.gg/dXEabqftTb)**


## Support Development

B-BakaEngine is free with no ads and will stay that way. If you want to support development:

- **Amazon gift cards** (`.in` — India) sent via Discord DM
- Global users can purchase Amazon.in gift cards from reputable third-party sources
- Find me on the Discord server above

No pressure. She would tell you not to bother anyway.


## Technical Stack

| Component | Technology |
|-----------|-----------|
| Character rendering | Live2D Cubism SDK 5-r.5 (Native) |
| Graphics | OpenGL ES 2.0 / 3.0 |
| Native layer | C++17 via Android NDK |
| Java layer | Android WallpaperService + Choreographer |
| Text rendering | FreeType 2 |
| Build system | Gradle + CMake |


## Credits

**Developer:** [BakaDev / HEBEI77](https://github.com/HEBEI77)

**Live2D Sample Model:** Hiyori — © Live2D Inc., used under the [Live2D Free Material License](https://www.live2d.com/en/download/sample-data/)

> This content uses sample data owned and copyrighted by Live2D Inc.

> This project is not affiliated with or endorsed by Live2D Inc.


<div align="center">
<sub>B-Baka... it's not like I wanted you to use this wallpaper or anything.</sub>
</div>
