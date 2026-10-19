# Bouncy Bros! website

The public pages for Bouncy Bros!, hosted free with GitHub Pages at
**https://bouncybros.github.io/**

- `index.html`: home page with contact info (App Store **Marketing URL**, and
  for now the **Support URL**)
- `privacy.html`: privacy policy (App Store **Privacy Policy URL**)
- `terms.html`: terms of use (linked from the game's Ad-Free screen)
- `app-ads.txt`: tells ad buyers which AdMob account may sell ads in the app

## Publishing

1. Open https://github.com/bouncybros/bouncybros.github.io and click
   **uploading an existing file** (or **Add file › Upload files**).
2. Drag in everything inside this folder (not the folder itself), so
   `index.html` sits at the top level, and click **Commit changes**.
3. Open **Settings › Pages**, set Source to **Deploy from a branch**, Branch
   **main**, folder **/ (root)**, and click **Save**.

A minute or two later the site is live. `app-ads.txt` is at the root of the
address, which is where AdMob looks for it.

## App Store Connect URLs

| Field | URL |
|---|---|
| Marketing URL | `https://bouncybros.github.io/` |
| Support URL | `https://bouncybros.github.io/#contact` |
| Privacy Policy URL | `https://bouncybros.github.io/privacy.html` |

AdMob finds `app-ads.txt` through the Marketing URL in the App Store, so set
that first; AdMob can take a day or two to verify it.

Contact: bouncybros.app@gmail.com

© 2026 Timothy Squires. All rights reserved.
