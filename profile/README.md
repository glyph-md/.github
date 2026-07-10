# Glyph

A modern, cross-platform markdown viewer and editor — native styling, live preview, AI assistance, and offline-first.

[![CI](https://github.com/hamidfzm/glyph/actions/workflows/ci.yml/badge.svg?branch=main)](https://github.com/hamidfzm/glyph/actions/workflows/ci.yml)
[![codecov](https://codecov.io/gh/hamidfzm/glyph/graph/badge.svg)](https://codecov.io/gh/hamidfzm/glyph)

## Repositories

- **[glyph](https://github.com/hamidfzm/glyph)** — the app (Tauri v2 + React 19 + TypeScript)
- **[homebrew-tap](https://github.com/glyph-md/homebrew-tap)** — Homebrew formula for macOS and Linux
- **[scoop-bucket](https://github.com/glyph-md/scoop-bucket)** — Scoop manifest for Windows
- **[apt-repo](https://github.com/glyph-md/apt-repo)** — Debian/Ubuntu apt repository
- **[rpm-repo](https://github.com/glyph-md/rpm-repo)** — Fedora/RHEL dnf repository

## Install

```bash
# macOS
brew tap glyph-md/tap && brew trust glyph-md/tap && brew install --cask glyph

# Windows
winget install hamidfzm.Glyph

# Linux (Homebrew)
brew tap glyph-md/tap && brew install glyph

# Fedora / RHEL
sudo tee /etc/yum.repos.d/glyph.repo < <(curl -fsSL https://glyph-md.github.io/rpm-repo/glyph.repo) && sudo dnf install glyph
```

Full install instructions: see the [Glyph website](https://glyph-md.github.io/#download).

## Get involved

- [Open an issue](https://github.com/hamidfzm/glyph/issues/new/choose)
- [Roadmap](https://github.com/hamidfzm/glyph/issues?q=is%3Aissue+is%3Aopen+label%3Aenhancement)
- [Contributing guide](https://github.com/hamidfzm/glyph/blob/main/CONTRIBUTING.md)

## License

[MIT](https://github.com/hamidfzm/glyph/blob/main/LICENSE)
