# Tab Suspender — The Great Suspender Replacement

Auto-suspend inactive Chrome tabs to reclaim memory. No tracking. No limits. Free and open source.

[![GitHub Stars](https://img.shields.io/github/stars/theluckystrike/zovo-tab-suspender-public?style=social)](https://github.com/theluckystrike/zovo-tab-suspender-public)

## Why This Exists

The Great Suspender was removed from the Chrome Web Store for containing malware. Tab Suspender is a clean, privacy-first replacement built from scratch on Manifest V3.

## Key Features

- **Auto-suspend after configurable timeout** — 5 min, 15 min, 30 min, 1 hour, or custom
- **Whitelist domains** — keep Gmail, Spotify, or any site always active
- **Suspend other tabs / restore all tabs** — one click or keyboard shortcut
- **Memory savings indicator** — see exactly how much RAM you are reclaiming
- **Smart exclusions** — pinned tabs, tabs playing audio, and the active tab are never suspended
- **Keyboard shortcuts** — `Alt+S` suspend current, `Alt+Shift+S` suspend others, `Alt+R` restore all

## Install

Download the packaged extension from [GitHub Releases](https://github.com/mrdear/tab-suspender-private/releases/latest), then unzip it.

1. Open `chrome://extensions`
2. Enable **Developer mode**
3. Click **Load unpacked**
4. Select the unzipped extension folder

## Privacy

Tab Suspender collects **zero data**. No analytics, no telemetry, no external requests. All settings are stored locally on your device.

## Permissions

| Permission | Reason |
|---|---|
| `tabs` | Monitor activity and suspend/restore tabs |
| `storage` | Save settings and whitelist locally |
| `alarms` | Periodically check for idle tabs |
| `scripting` | Inject the suspend/restore UI into tabs |

## Contributing

1. Fork the repo
2. Create a feature branch
3. Test locally via `chrome://extensions` > Load unpacked
4. Open a pull request

Issues and feature requests: [GitHub Issues](https://github.com/theluckystrike/zovo-tab-suspender-public/issues)

## Free Features

All extension features are free, with no in-app gates or whitelist caps.
