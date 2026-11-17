# DJConnect Firmware Release Agent Instructions

## DJConnect Platform Bootstrap

For a clean Codex/AI-agent session in this repository, start here:

`BOOTSTRAP_CODEX_SESSION.md`

That local bootstrap points back to the canonical platform foundation in
`djconnect-music-dj/djconnect` and then returns to the repository-specific rules in this
file. This repository extends the DJConnect Platform Foundation. It does not
redefine it.

This repository follows the canonical DJConnect design foundation in `djconnect-music-dj/djconnect`.

Read first:

- `djconnect-music-dj/djconnect/DJCONNECT_CONSTITUTION.md`
- `djconnect-music-dj/djconnect/ARCHITECTURE_PRINCIPLES.md`
- `djconnect-music-dj/djconnect/PLATFORM_GOVERNANCE.md`
- `djconnect-music-dj/djconnect/PLATFORM_QUALITY_STANDARD.md`
- `djconnect-music-dj/djconnect/SYNC_PROMPTS.md`
- `djconnect-music-dj/djconnect/PRODUCT_ROADMAP.md`

## Role

This repo is a distribution surface for public DJConnect ESP32 firmware releases.

It publishes artifacts, manifests and release notes. It does not own product logic, firmware source, platform contracts or roadmap decisions.

## Rules

- Do not add firmware source logic here.
- Do not fork roadmap, sync prompts or product contracts locally.
- Release artifacts should be traceable to source commits in `djconnect-music-dj/djconnect-esp32`.
- Release notes should describe user-visible behavior and compatibility.
- Do not publish secrets, signing keys, tokens, WiFi credentials, Home Assistant tokens or provider credentials.
- Artifact integrity should be preserved with hashes/checksums where supported.
- Keep release behavior aligned with `PLATFORM_QUALITY_STANDARD.md`.
