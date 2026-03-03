# Tab Suspender Pro - Save Memory & Speed Up Chrome

[![Chrome Web Store](https://img.shields.io/chrome-web-store/v/zovo-tab-suspender)](https://chrome.google.com/webstore/detail/zovo-tab-suspender)
[![Version](https://img.shields.io/badge/version-1.0.19-green.svg)](https://github.com/theluckystrike/zovo-tab-suspender-public)
[![License](https://img.shields.io/badge/license-BSL%201.1-blue.svg)](https://mariadb.com/bsl11/)
[![GitHub Stars](https://img.shields.io/github/stars/theluckystrike/zovo-tab-suspender-public?style=social)](https://github.com/theluckystrike/zovo-tab-suspender-public)
[![Discord](https://img.shields.io/badge/Discord-Zovo-blueviolet.svg?logo=discord)](https://discord.gg/zovo)
[![Website](https://img.shields.io/badge/Website-zovo.one-blue)](https://zovo.one)

> Automatically suspend inactive tabs to free memory and speed up Chrome.

**Tab Suspender Pro** is a Chrome extension that intelligently suspends inactive tabs to reduce memory usage and improve browser performance. Keep hundreds of tabs open without slowing down your system.

## Features

- **Automatic Tab Suspension** - Suspend inactive tabs after a configurable idle period to free up memory
- **Domain Whitelist** - Define domains that should never be suspended (e.g., streaming sites, work apps)
- **Configurable Idle Timer** - Set custom timeout periods (5 min, 15 min, 30 min, 1 hour, etc.)
- **Visual Indicator** - Easily identify suspended tabs with a clear visual marker
- **One-Click Restore** - Click any suspended tab to instantly restore it
- **Smart Exclusions** - Automatically excludes pinned tabs, tabs playing audio, and the active tab

## How It Works

1. Set your preferred idle timeout in the settings
2. Add any domains you want to whitelist (optional)
3. The extension automatically suspends tabs that have been inactive for the specified time
4. Click a suspended tab to restore it instantly
5. Monitor memory savings in the extension popup

## Permissions Explained

| Permission | Why |
|------------|-----|
| `tabs` | Monitor tab activity and suspend/restore tabs |
| `storage` | Save your settings and whitelist locally |
| `alarms` | Check for idle tabs periodically |
| `webNavigation` | Detect when tabs navigate to new pages |

## Privacy

**Tab Suspender Pro collects zero data.**

- Does NOT send any data to external servers
- Does NOT track your browsing activity
- Does NOT collect analytics or telemetry
- All tab management happens locally in your browser
- Your settings are stored only on your device

## License

This repository contains the community edition of Tab Suspender Pro, licensed under the **Business Source License 1.1 (BSL 1.1)**.

**What this means:**
- Free to use for personal and non-production purposes
- Source code is fully available for inspection
- Commercial use requires a separate license

See the full license text at: https://mariadb.com/bsl11/

## Installation

Install from the [Chrome Web Store](https://chrome.google.com/webstore) or load unpacked from source:

1. Clone this repository
2. Open `chrome://extensions` in Chrome
3. Enable "Developer mode"
4. Click "Load unpacked" and select the extension folder

## Built by Zovo

Part of the [Zovo](https://zovo.one) developer tools family.

## Support

- Report issues on [GitHub Issues](https://github.com/theluckystrike/zovo-tab-suspender-public/issues)
- Contact: support@zovo.one

## Contributing

Contributions are welcome! Please follow these steps:

1. **Fork** the repository
2. **Create** a feature branch: `git checkout -b feature/suspender-improvement`
3. **Make** your changes
4. **Test** locally by loading unpacked
5. **Commit** your changes: `git commit -m 'Add new feature'`
6. **Push** to the branch: `git push origin feature/suspender-improvement`
7. **Submit** a Pull Request

### Development Setup

```bash
# Clone the repository
git clone https://github.com/theluckystrike/zovo-tab-suspender-public.git
cd zovo-tab-suspender-public

# Make changes to the source files
# Then load in Chrome: chrome://extensions > Load unpacked
```

## See Also

### Related Zovo Repositories

- [zovo-permissions-scanner](https://github.com/theluckystrike/zovo-permissions-scanner) - Privacy scanner for Chrome extensions
- [zovo-extension-template](https://github.com/theluckystrike/zovo-extension-template) - Boilerplate for building privacy-first Chrome extensions
- [zovo-types-webext](https://github.com/theluckystrike/zovo-types-webext) - TypeScript type definitions
- [zovo-chrome-extensions](https://github.com/theluckystrike/zovo-chrome-extensions) - Collection of Zovo extensions

### Other Zovo Chrome Extensions

- [Zovo Focus](https://chrome.google.com/webstore/detail/zovo-focus) - Block distractions
- [Zovo Session Manager](https://chrome.google.com/webstore/detail/zovo-session-manager) - Save and restore tabs
- [Zovo Permissions Scanner](https://chrome.google.com/webstore/detail/zovo-permissions-scanner) - Check extension privacy grades

Visit [zovo.one](https://zovo.one) for more information.

---

Made with care by the Zovo team.
