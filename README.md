# Fundy Tuner — Beta

**Early access beta for Android. Not yet on the Play Store.**

Fundy Tuner is a banjo tuner built specifically for clawhammer and old-time players. It goes beyond standard chromatic tuners with a sweetness slider for just intonation, a precision strobe, and a set of tools designed around the way banjo players actually work.

---

## Beta Notice

This is an early release for feedback from real players. Things work well but you may hit rough edges. Your bug reports and suggestions directly shape what gets fixed and what gets built next.

If something breaks or feels off, please let us know — details below.

---

## Features

**Main Tuner**
- Chromatic tape display with real-time cent deviation, sweetener-compensated so the target moves with your intonation setting
- Precision strobe tuner — single or multi-harmonic ring modes
- Sweetness slider: blend between equal temperament and just intonation, string by string, to get that open-chord ring
- Supports 5-string, tenor, and plectrum banjo with multiple tunings per instrument — including Oh Death, Pretty Polly (Doc Boggs), Indian Summer, Goodbye Old Paint, and more
- Fiddle tunings: Standard (GDAE), Cross G, Cross A — with pure-5th sweetening
- Guitar tunings: Standard (with James Taylor method sweetening), Drop D, DADGAD, Open G, Open D (Vestapol), Open D (Adrianne Lenker), Sawmill, Double Drop D, Open C, Orkney
- Auto string detection — plays the right string as you tune across the neck
- String locking — tap any string button to lock the tuner to that string, filtering out harmonics and adjacent strings. Tap again to unlock
- Capo / transposition controls
- Favorite tunings — star any tuning for quick access at the top of the list
- Long-press any tuning to edit its name or notes

**Tools**
- **Bridge Setup** — step-by-step intonation tool. Compares your 12th fret harmonic to the fretted note and tells you which direction to move the bridge and how far (in mm). Works even if your banjo isn't at concert pitch
- **Restring Helper** — plays a sustained drone of each string's target note while you're restringing, with a small strobe so you can tune by ear as you go
- **Custom Sweetened Tunings** — tune your banjo by ear until it sounds right, then record the string intervals as a named preset. The app captures your exact intonation and lets you retune to it any time
- **Identify Tuning** — record 30 seconds of someone playing and the app figures out what tuning they're in. Recognizes Standard G, Sawmill, Sandy River Belle, Double C, Open D, Drop C and more. Runs entirely on-device

**Settings**
- A4 reference adjustable from 400–500 Hz with Baroque, Verdi, and Standard presets
- Match Pitch: tap a button, play any note on a nearby instrument, and the app shifts all string targets to match its pitch for the session — useful for playing with an out-of-tune piano or matching a recording
- Dark / light mode with 13 color themes
- Sensitivity control — adjust how aggressively the tuner filters background noise
- Toggle individual features on or off to keep the screen clean
- Restore stock tunings or reset all settings to defaults

---

## Install (Android Sideload)

1. On your Android phone, go to **Settings > Apps > Special app access > Install unknown apps** and allow installs from your browser or file manager
2. Download the APK from the [Releases](../../releases) tab on this page
3. Open the downloaded file and tap Install
4. Open Fundy Tuner and grant microphone permission when prompted

> The APK is ~87MB — larger than a native app due to the React Native framework bundled inside. This is normal and doesn't affect performance.

> Tested on Android 10 and above. If you run into install issues on your specific device, let us know your Android version.

---

## Reporting Bugs & Feedback

Two ways to reach us:

- **GitHub Issues** (preferred for bugs): [Open an issue](../../issues/new) and describe what happened, what you expected, and your device/Android version if you know it
- **Direct contact**: [fundybanjos@gmail.com](mailto:fundybanjos@gmail.com) — feel free to email directly if you'd rather not use GitHub

All feedback is read. Thank you for helping make this better.

---

## Permissions

Fundy Tuner requests only what it needs to function. It has no internet access, makes no network requests, and collects no data.

| Permission | Why |
|---|---|
| Microphone | Pitch detection — the core function of the tuner |
| Modify Audio Settings | Drone playback in Restring Helper |
| Vibrate | Haptic feedback when a string locks in tune |
| Storage (Android 12 and below only) | Temporary audio buffer file for pitch detection |

No internet permission. No analytics. No ads. Nothing leaves your device.

---

## Planned

- iOS release
- Play Store listing
- Additional tunings and instruments

---

*Fundy Tuner v1.6.0 — Android beta*

---

© 2026 Fundy Banjos. Released under [CC BY-NC-ND 4.0](LICENSE) — free to share, not for commercial use.
