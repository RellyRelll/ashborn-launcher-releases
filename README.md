# Ashborn Launcher — releases

Compiled installers for the [Ashborn](https://ashbornsurvival.com) desktop
launcher only. No source code lives here — this repo exists purely so the
download from ashbornsurvival.com works without requiring a GitHub login
(the launcher's own source repo is private).

Built by [.github/workflows/launcher-release.yml](https://github.com/RellyRelll/Ashborn/blob/main/.github/workflows/launcher-release.yml)
in the main repo on every `launcher-v*` tag.

## Current build

**v0.1.1 — unsigned test build, Windows only.**

Windows will show a SmartScreen warning before you run it ("Windows
protected your PC" → More info → Run anyway) — there's no code-signing
certificate yet. macOS isn't built yet (needs a larger source icon +
an Apple Developer ID). This is the launcher app itself (devlog, account,
playtest status) — Ashborn is still in pre-alpha and isn't downloadable
through it yet.

- [`v0.1.1/Ashborn-Launcher-Setup-0.1.1.exe`](v0.1.1/Ashborn-Launcher-Setup-0.1.1.exe) — 92.4 MB
- sha256: `d9d258cfa718462ee1640a952741abf46449a3a553a54963ca4cb899520b043b`
