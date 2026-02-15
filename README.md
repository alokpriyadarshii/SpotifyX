# SpotifyX

A Flutter project that recreates a modern Spotify style **UI** with smooth layouts and a bottom tab experience.  
This is a **UI/learning project** (no real Spotify API/auth) — great for practice, demos, and customization.

---

## ✨ What’s inside
- Get Started / Welcome screen  
- Login UI  
- Home UI (mixes, artists, weekly picks)  
- Search UI (browse + input)  
- More / Library style UI  
- Top Hits page (SliverAppBar style header)

---

## 🚀 Quick Start (all commands at once)

~~~bash
set -euo pipefail
cd "/Users/alok/Desktop/SpotifyX"
flutter doctor
flutter pub get
flutter run
~~~

---

## 🧹 If build issues (optional)

~~~bash
set -euo pipefail
cd "/Users/alok/Desktop/SpotifyX"
flutter clean
flutter pub get
dart format .
flutter analyze
flutter test
~~~

---

## 📦 Release build (optional)

~~~bash
set -euo pipefail
cd "/Users/alok/Desktop/SpotifyX"
flutter build apk --release
flutter build ios --release
~~~

---

## 📁 Project structure (high level)

~~~text
SpotifyX/
  android/
  ios/
  linux/
  macos/
  windows/
  web/
  assets/
    images/
  lib/
    main.dart
    constants/
    data/
    view/
      get_started/
      login/
      tab/
        home/
        search/
        more/
      top_hits/
  test/
  pubspec.yaml
  pubspec.lock
~~~

---

## 🛠 Customize
- **Colors / theme**: check `lib/constants/` (commonly `colors.dart`)
- **Sample content (titles, artists, playlists)**: check `lib/data/`
- **Images**: `assets/images/`
- **App title / launcher icons**: update platform folders (`android/`, `ios/`) if needed

> Folder name is **SpotifyX**. If you want the Flutter package name to match, update `name:` in `pubspec.yaml` and refactor imports if required.




