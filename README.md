# DOSHorse_Android

> **Status:** v0.0.1-Hoff skeleton. Géén code-import in deze fase. Prio 3.

Android-variant van DOSHorse. NDK-build van `DOSHorse_Core` + Kotlin/Jetpack-Compose UI.

## Doel

DOS-emulatie op Android telefoons en tablets met gamepad-/touch-input.

## Strategie

- DOSHorse_Core via NDK r26+ compileren naar `.so` libraries
- JNI-bridge in `bindings/jni/` van Core
- Kotlin/Compose-UI in deze repo (gamepad-mapping, touch-overlay, virtuele keyboard, OSD)

Alternatief (beslispunt O4): DOSBox Pure libretro core in plaats van dosbox-x. Te beslissen wanneer Android-fase actief wordt.

## Codenaam

v0.0.1 = **Hoff** (Marcian "Ted" Hoff, Intel 4004 designer) — past bij mobile-chip-pionier-werk.

Pool-bron: `Meta_DOSHorse/CLAUDE.md`.

## Status

| Component | Status |
|-----------|--------|
| Skeleton | ✓ |
| NDK build | open (v0.0.5) |
| Kotlin/Compose UI | open |
| Touch-overlay | open |
| Gamepad-mapping | open |
| Engine-keuze (dosbox-x vs DOSBox Pure) | open beslispunt O4 |

## Deploy

APK in `releases/` + GitHub Releases + `icthorsecloud.nl/DOSHorse/downloads/android/`. Mogelijk later F-Droid (GPL-friendly).
