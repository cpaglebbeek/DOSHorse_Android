# ARCHITECTURE — DOSHorse_Android

> Skeleton-fase.

## Doel

DOSHorse op Android via NDK-build van DOSHorse_Core + Compose-UI.

## Geplande structuur (v0.0.5+)

```
DOSHorse_Android/
├── core/                  # git submodule -> DOSHorse_Core
├── app/
│   ├── src/main/cpp/      # JNI glue
│   ├── src/main/kotlin/   # Compose UI
│   └── build.gradle.kts
├── settings.gradle.kts
└── gradle/
```

## Open beslispunten

| # | Vraag | Wanneer |
|---|-------|---------|
| A1 | Engine: dosbox-x via DOSHorse_Core, of DOSBox Pure libretro? | v0.0.5 |
| A2 | Distribution: F-Droid (GPL-friendly), Play Store, of beide? | v0.0.7+ |
| A3 | Touch-overlay: vaste preset of per-game customizable? | v0.0.6 |
