# Tab Suspender Pro — The Great Suspender Replacement

Auto-suspend inactive Chrome tabs to reclaim memory. No tracking. No limits. Free and open source.

[![Chrome Web Store](https://img.shields.io/chrome-web-store/v/ofgncemnlblfnocjbojdhamacfffcpnm)](https://chromewebstore.google.com/detail/tab-suspender-pro-save-me/ofgncemnlblfnocjbojdhamacfffcpnm)
[![License](https://img.shields.io/badge/license-BSL%201.1-blue.svg)](https://mariadb.com/bsl11/)
[![GitHub Stars](https://img.shields.io/github/stars/theluckystrike/zovo-tab-suspender-public?style=social)](https://github.com/theluckystrike/zovo-tab-suspender-public)

## Why This Exists

The Great Suspender was removed from the Chrome Web Store for containing malware. Tab Suspender Pro is a clean, privacy-first replacement built from scratch on Manifest V3.

## Key Features

- **Auto-suspend after configurable timeout** — 5 min, 15 min, 30 min, 1 hour, or custom
- **Whitelist domains** — keep Gmail, Spotify, or any site always active
- **Suspend / unsuspend all tabs** — one click or keyboard shortcut
- **Memory savings indicator** — see exactly how much RAM you are reclaiming
- **Smart exclusions** — pinned tabs, tabs playing audio, and the active tab are never suspended
- **Keyboard shortcuts** — `Alt+S` suspend current, `Alt+Shift+S` suspend others, `Alt+R` restore all

## Install

**[Get it from the Chrome Web Store](https://chromewebstore.google.com/detail/tab-suspender-pro-save-me/ofgncemnlblfnocjbojdhamacfffcpnm)**

Or load from source:

```bash
git clone https://github.com/theluckystrike/zovo-tab-suspender-public.git
```

1. Open `chrome://extensions`
2. Enable **Developer mode**
3. Click **Load unpacked** and select the cloned folder

## Privacy

Tab Suspender Pro collects **zero data**. No analytics, no telemetry, no external requests. All settings are stored locally on your device.

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

## License

[Business Source License 1.1](https://mariadb.com/bsl11/) — free for personal and non-production use. Commercial use requires a separate license.
