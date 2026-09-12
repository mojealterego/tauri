# Plan audytu — tauri

## Status
AUDYT ZAKOŃCZONY — 2026-09-12.

## Ustalenia
Upstreamowy framework do budowania aplikacji desktopowych z frontendem webowym i backendem Rust. Projekt referencyjny dla aplikacji desktopowych.

## Ryzyka
IPC, allowlist/capabilities, filesystem i shell access, window permissions, updater, bundling oraz podpisywanie artefaktów.

## Dalsza praca
Traktować jako upstream/reference. Przy własnych aplikacjach stosować minimalne capabilities, jawne permissions, bezpieczny updater i weryfikację podpisów.
