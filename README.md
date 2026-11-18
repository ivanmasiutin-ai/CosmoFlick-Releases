# CosmoFlick

Your apps, one flick away. A radial launcher for Windows 10 and 11.

Open the wheel at your pointer with a keyboard shortcut or a side mouse button. Aim at an app; the magnetic puck follows your direction. Flick outward or click to launch, or bring an already open app to the front.

[Website](https://cosmoflick.app) · [Releases](https://github.com/ivanmasiutin-ai/CosmoFlick-Releases/releases) · [Support](https://cosmoflick.app/#support)

<img src="images/wheel.png" width="560" alt="CosmoFlick wheel with example app shortcuts and the magnetic puck pointing toward a shortcut">

## Features

- Launch apps from a wheel wherever you are working.
- Add apps with fast search, including installed Steam games.
- Use a keyboard shortcut, a side mouse button or number keys.
- Adjust the magnet, gesture distance and sound to suit your hand.
- Use the interface in English, Russian or Romanian.

| Free | Pro |
| --- | --- |
| One wheel with up to 8 shortcuts | Unlimited shortcuts |
| Magnet, flick gesture, search and sound | Actions, commands and text |
| Aurora theme | All themes, subwheels and app wheels |

Pro keeps working offline after activation. See the [website](https://cosmoflick.app/#pro) for current availability and terms.

<img src="images/search.png" width="700" alt="Add to wheel search with example app results">

## Install

Download the [CosmoFlick 1.1.5 Dev installer](https://github.com/ivanmasiutin-ai/CosmoFlick-Releases/releases/tag/manual-v1.1.5) for Windows 10 and 11.

**The app and installer are unsigned. Windows may show an unknown publisher or a SmartScreen warning. This Dev release requires manual installation and updating.** Read the release notes and limitations before testing.

For portable: extract the ZIP to a writable folder and run **CosmoFlick.exe**. Keep the folder when updating so your settings and shortcuts remain available.

The installer installs for your Windows account without administrator access. It can import settings and wheels from a portable folder, keeping the original files. Close CosmoFlick from the tray before installing. Uninstalling keeps your settings, wheels and Pro activation.

To update an installed copy, back up your data, close CosmoFlick from the tray, then download and run the new installer in the same installation folder. Settings, wheels and Pro activation are kept. Unsigned packages are never installed automatically by CosmoFlick.

After starting, open CosmoFlick from the tray to configure its shortcut and mouse button. The new installer starts with an empty wheel: choose **+** to add your first app. Example shortcuts in the screenshots are not bundled.

## Dev and Stable

**Stable** is the default update channel for tested releases. **Dev** includes GitHub pre-releases for testing upcoming versions. No Stable installer is published yet. Choose a channel in **Settings → System**. Starting with 1.1.5, manual releases can be discovered there using **Dev → Check for updates → Open release**. Earlier builds may not discover this manual channel; use the release page directly.

A Dev release is promoted to Stable only after testing and the owner's decision. Promotion keeps the same version, tag and installer. If the package needs a fix, it gets a new version. Unsigned manual releases use `manual-v<version>` tags and include `unsigned-release.json` with their version, changes, SHA-256 and actual `NotSigned` status. `releaseReady: false` means ineligible for automatic installation. Hashes check integrity, not publisher identity. Future signed releases use `v<version>` and `release.json`; trusted publisher checks remain mandatory for automatic installation.

## Support

Email [support@cosmoflick.app](mailto:support@cosmoflick.app) with your Windows version, CosmoFlick version, what you expected and what happened. Do not include license keys, payment details, private shortcuts or clipboard contents.

[Restore Pro](https://cosmoflick.app/restore) · [Privacy](https://cosmoflick.app/privacy) · [License terms](https://cosmoflick.app/license-terms)

This repository hosts public downloads and release information. CosmoFlick source code is maintained separately.
