# Lector — Offline Android PDF/EPUB Text-to-Speech Reader

[![Android](https://img.shields.io/badge/Android-Offline%20Reader-3DDC84?logo=android&logoColor=white)](https://developer.android.com/)
[![Kotlin](https://img.shields.io/badge/Kotlin-Jetpack%20Compose-7F52FF?logo=kotlin&logoColor=white)](https://kotlinlang.org/)
[![License](https://img.shields.io/github/license/AlakhiarovSalekh/Lector)](LICENSE)
[![Stars](https://img.shields.io/github/stars/AlakhiarovSalekh/Lector?style=social)](https://github.com/AlakhiarovSalekh/Lector/stargazers)

**Read text, PDF, and EPUB documents aloud — private, offline, and without an account.**

Lector uses the text-to-speech voices already available on the Android device. Open a TXT, Markdown, EPUB, or PDF file, scan a folder, paste text, or share content to Lector from another app. The reader presents the content in pages and highlights the current sentence while reading.

## Features

- Read TXT, Markdown, EPUB, PDF, and other text files
- Scan a folder into a local reading library
- Resume from the last reading position
- Page view with whole-document navigation
- Adjustable speech speed
- Sleep timer
- Background-friendly playback controls
- Current-sentence highlighting

## Privacy by Design

Lector is designed to work without accounts, ads, trackers, or network access. Text-to-speech runs through the engine available on the device, so document text does not need to be sent to a remote service.

See [PRIVACY_POLICY.md](PRIVACY_POLICY.md).

## Tech Stack

- Kotlin
- Jetpack Compose
- Android SDK
- min SDK 26
- target SDK 35
- PDFBox Android for PDF text extraction

## Build

```bash
./gradlew :app:assembleDebug
./gradlew :app:assembleRelease
```

The Android SDK must be configured through `local.properties` (`sdk.dir`) or `ANDROID_HOME`. Release output is unsigned unless signing is configured locally.

## Repository Areas

- `app/` — Android application
- `core/` — shared/core modules
- `fastlane/` — store/release metadata
- `fdroid/` — F-Droid related metadata

## Contributing

Contributions are welcome, especially for accessibility, document compatibility, device support, translations, testing, and documentation.

> If this project is useful to you, consider starring the repository. It helps you find it again and helps other developers discover the project.

## More Projects by Salekh

- [Notes App](https://github.com/AlakhiarovSalekh/Notes-App) — modern Kotlin/Compose notes application.
- [Weather App](https://github.com/AlakhiarovSalekh/Weather-App) — Android weather app with local data and charts.
- [Android Kotlin Bluetooth Chat App](https://github.com/AlakhiarovSalekh/Android-Kotlin-Bluetooth-Chat-App) — device-to-device Bluetooth chat.

## Author

**Salekh Alakhiarov** · [GitHub](https://github.com/AlakhiarovSalekh)

## License

GNU GPL v3.0 — see [LICENSE](LICENSE).
