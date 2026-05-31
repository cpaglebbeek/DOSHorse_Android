---
date: 2026-05-31
repo: DOSHorse_Android
status: done
resume: ""
session: newp DOS Emulator — cross-repo verwijzing
agent: Claude Opus 4.7 (1M context)
---

# Newp DOS Emulator — DOSHorse_Android cross-repo verwijzing

Dit is een **pointer-stub** voor het cross-repo prompt-protocol (Meta_Master/CLAUDE.md §Prompt Sessie Documentatie §Wanneer §4).

## Master sessie-MD

**Volledige sessie:** [`Meta_DOSHorse/prompts/2026-05-31_newp_dos_emulator.md`](https://github.com/cpaglebbeek/Meta_DOSHorse/blob/main/prompts/2026-05-31_newp_dos_emulator.md)

## Wat is hier vastgelegd (DOSHorse_Android-specifiek)

- v0.0.1-Hoff (Marcian "Ted" Hoff, Intel 4004 designer) — past bij mobile-chip-pionier-werk
- Rol: Variant 3 — NDK-build van DOSHorse_Core + Kotlin/Jetpack-Compose UI
- Engine-keuze open: dosbox-x via DOSHorse_Core vs DOSBox Pure (libretro core)
- Skeleton-fase: README + CLAUDE + ARCHITECTURE + CHANGELOG + LICENSE (AGPL-3.0) + VERSION + .gitignore — géén code-import
- Open beslispunten in `ARCHITECTURE.md`: A1 (engine), A2 (F-Droid/Play Store), A3 (touch-overlay preset/custom)
- Build-protocol uit `CLAUDE.md`: +0.0.1 bij elke bugfix, `assembleRelease` altijd, stable APK → `releases/`

## Volgende sessie

v0.0.5 of later — NDK + Compose skeleton (volgt op X86 + Core in v0.0.2-3).
