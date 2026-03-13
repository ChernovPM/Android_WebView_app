# Aqvicoin Android WebView App (Historical Project)

## Overview
This repository contains an **archived Android mini browser app** built around a single `WebView` screen.
The application opens a predefined website URL and keeps navigation inside the app.

It is preserved as a **historical personal project** targeting **Android SDK 26** (Android 8.0 era).

## Features
- Launches directly into a full-screen `WebView`
- Loads a predefined site URL on startup
- Keeps clicked links inside the app using `WebViewClient`
- Requests internet access through the Android manifest

## Tech Stack
- **Language:** Java
- **UI:** Android XML layout + `ConstraintLayout`
- **Core component:** Android `WebView`
- **Android target era:** SDK 26 project generation
- **Build system context:** Gradle/Android Studio project style (legacy Android app structure)

## Project Status
- **Status:** Archived / showcase repository
- **Purpose:** Portfolio reference for an early Android `WebView` implementation
- **Maintenance level:** Minimal; no active modernization planned

## How to Run
1. Open the project in **Android Studio**.
2. Let Android Studio sync dependencies and project metadata.
3. Build and run on an emulator or physical device with internet access.
4. The app should open the configured URL inside the embedded `WebView`.

> If this repository is used as a code snapshot (rather than a full Android Studio project tree), place the files into standard Android module paths (`app/src/main/...`) before building.

## Notes
- This app reflects older Android development practices and dependencies.
- The configured website URL may no longer be available.
- Network security, WebView behavior, and platform requirements may differ on modern Android versions.
- This repository intentionally prioritizes historical accuracy over aggressive modernization.
