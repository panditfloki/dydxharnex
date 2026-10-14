# dydxHarneX User for Mac

dydxHarneX is a desktop workspace for the AI coding CLIs you already use: Claude Code, Codex, Gemini and more, side by side, on your own accounts.

This repository holds **release downloads only**. It contains no source code.

## Download

**[Download dydxHarneX User for Mac (Apple Silicon)](https://github.com/panditfloki/dydxharnex/releases/latest/download/dydxHarneX-User-arm64.dmg)**

- Apple Silicon Macs only (M1 or later). Intel Macs are not supported.
- macOS 12 Monterey or later.
- At least one AI coding CLI installed and signed in with your own account.

Every release lists the SHA-256 of each file next to it. To check a download:

```sh
shasum -a 256 ~/Downloads/dydxHarneX-User-arm64.dmg
```

## Install

1. Open the DMG and drag **dydxHarneX User** onto **Applications**.
2. Eject the dydxHarneX disk.

## First open

This build is not notarized by Apple yet, so macOS blocks the first launch. You only do this once.

**macOS 15 Sequoia or later**

1. Open dydxHarneX User from Applications. macOS says it cannot verify the app. Click Done.
2. Open System Settings > Privacy & Security, scroll down and click **Open Anyway** next to dydxHarneX User. Confirm with your password.

**macOS 12 to 14**

Right-click (or Control-click) dydxHarneX User in Applications, choose Open, then click Open again.

If macOS says the app "is damaged and can't be opened", run this once in Terminal, then open the app normally:

```sh
xattr -dr com.apple.quarantine "/Applications/dydxHarneX User.app"
```

## Limited preview

dydxHarneX User is in limited preview. It activates with the email address and licence key issued to you by DYDXFX. Online sign-up, free trials and paid plans are not available yet; they come with the paid launch later.

## Updates

The app checks this repository for signed updates on launch and every 6 hours. To check now, click the version at the bottom left of the sidebar, or choose **dydxHarneX User > Check for Updates**. Each update is verified against a DYDXFX signing key and a SHA-256 checksum, and nothing installs until you say so.

## Your data

Projects, chats and settings stay on your Mac in `~/Library/Application Support/dydxHarneX-User`. Your AI accounts and their usage stay with each provider.

## Licence

dydxHarneX User is proprietary software. Using it requires a licence issued by DYDXFX. See the [notice](LICENSE).

© 2026 dydxfx · https://dydxfx.com
