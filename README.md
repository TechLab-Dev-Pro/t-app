# FamFit

A clean and focused Flutter app for interval training and infinite Pomodoro sessions.

---

## Overview

FamFit is a production-style Flutter app designed for:
- interval training sessions
- Pomodoro productivity cycles
- long-running timers with reliable resume system

### Core Features

* 🏋️ Interval training (warmup, work, rest, cooldown)
* 🍅 Infinite Pomodoro mode (no total cycle limit in UI)
* ⏱ Fullscreen minimal timer view
* ⚡ Quick preset slots
* 💾 Local persistence (shared_preferences)
* 🔔 Sound alerts
* 🔄 Timestamp-based resume after app minimize

Built to handle multi-hour sessions reliably.

---

## Tech Stack

* Flutter
* Dart
* shared_preferences
* audioplayers

---

## Getting Started

```bash
flutter pub get
flutter run
```

Build release APK:

```bash
flutter build apk --release
```

---

## Project Structure

```
lib/
  main.dart
assets/
  sounds/
```

---

## Roadmap

* Foreground service for stronger background reliability
* Local notifications
* Session statistics & history
* UI polish & performance tuning

---

## Status

🚧 Active development

---
