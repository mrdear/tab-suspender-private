# Tab Suspender - Testing Checklist

## Setup

1. Open `chrome://extensions/`.
2. Enable Developer mode.
3. Click Load unpacked.
4. Select the extension directory or `release/tab-suspender-1.0.19`.

## Install And Shell

- [ ] Extension loads without errors.
- [ ] Toolbar icon appears.
- [ ] Popup title shows "Tab Suspender".
- [ ] Settings page title shows "Tab Suspender - Settings".
- [ ] No feature-gating UI appears.

## Free Feature Access

- [ ] Custom timing slider is visible in Settings by default.
- [ ] More than 5 whitelist domains can be added.
- [ ] Additional whitelist entries save without a gating modal.

## Suspension

- [ ] Suspend Other Tabs suspends eligible inactive tabs.
- [ ] Active tab is not suspended.
- [ ] Whitelisted, pinned, audio, form, and browser pages are excluded according to settings.
- [ ] Suspended tabs use the sleep favicon.
- [ ] Clicking a suspended page restores the original URL.

## Restoration

- [ ] Restore All restores all suspended tabs.
- [ ] Popup restore button works for an individual suspended tab.
- [ ] Auto-restore on focus works when enabled.

## Settings

- [ ] Relaxed, Balanced, and Aggressive profiles update the timeout.
- [ ] Custom timeout from 1 to 120 minutes saves correctly.
- [ ] Protection toggles save and update badges.
- [ ] Whitelist entries can be added, removed, exported, and imported.

## Stats

- [ ] Dashboard opens from Settings.
- [ ] Memory, tab count, daily average, and top sites render.
- [ ] Export downloads valid stats JSON.
- [ ] Reset clears statistics after confirmation.

## Final Smoke Test

- [ ] `node --check` passes for extension scripts.
- [ ] `manifest.json` parses as valid JSON.
- [ ] Release zip passes `unzip -t`.
