# Tivalsdeveloper Android App

Official Android app for **Tivalsdeveloper**.

## Features

- Tivalsdeveloper landing experience
- Tivelop ecosystem
- TivelText
- LoadFX
- Tivelop Agent
- GitHub integration
- Instagram integration
- Dark developer-focused interface
- Automatic APK builds with GitHub Actions

## Build locally

Install Android SDK and Gradle 8.10+, then run:

```bash
gradle assembleDebug
```

APK output: `app/build/outputs/apk/debug/app-debug.apk`

## GitHub Actions

Every push to `main` builds the debug APK automatically. The APK is uploaded as a workflow artifact.
