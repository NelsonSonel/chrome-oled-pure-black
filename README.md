# OLED Pure Black — Chrome Theme

A minimal, **true `#000000` pure black** theme for Google Chrome (and Chromium-based browsers), built specifically for **OLED monitors**.

Unlike Google's official *Just Black* theme (which leaves the toolbar and bookmarks bar dark grey), **OLED Pure Black** keeps the **bookmarks bar, toolbar surround, inactive tabs, and New Tab page at true `#000000`** (pixels turned off), while keeping the **active tab** clearly readable with a subtle carbon-grey (`#181818`) top fade.

## Features

- **True `#000000` pure black** on the tab strip, toolbar background, bookmarks bar, and New Tab page
- **Clear active tab highlight**: subtle `#181818` (~0.5% OLED luminance) with a smooth vertical fade into `#000000`
- **Crisp white typography** tuned for WOLED/QD-OLED subpixel clarity
- **Zero scripts, zero permissions** — just `manifest.json` + a 1×200px PNG

## Installation (30 seconds)

1. Click **Code → Download ZIP** (or clone this repo) and unzip the folder somewhere permanent.
2. Open **`chrome://extensions`** in Chrome.
3. Enable **Developer mode** (top right).
4. Click **Load unpacked** (top left) and select the unzipped folder.
5. *(Optional)* Turn **Developer mode** back off — the theme stays applied.

## Note on the URL bar

Chromium's Material UI automatically applies a subtle contrast tint (`#1F1F1F`) to the omnibox pill when the toolbar is pure `#000000` — this is hardcoded in Chromium and cannot be overridden by a theme.

## License

[MIT](LICENSE)
