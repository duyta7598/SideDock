# SideDock

Download and update the SideDock macOS app.

[Download the latest release](https://github.com/duyta7598/SideDock/releases/latest)

## Install

1. Download the `SideDock-*-macOS-arm64.zip` file from the latest release.
2. Extract it and move `SideDock.app` to `/Applications`.
3. Open SideDock. Sign in to your Apple Account, select a Team, then choose an IPA to sign.

The current build supports Apple Silicon and macOS 27 or later. The app is ad hoc signed and is not notarized.

## Updates

Choose **Settings → Updates → Check for Updates…** in SideDock. Update feeds and app archives are signed with the app's pinned Ed25519 update key.

The update address is unchanged, so existing SideDock versions with the updater can continue checking this repository. Versions before 0.4.0 require a manual installation to gain the updater.

## Files

- `SideDock-*-macOS-arm64.zip`: the app.
- `appcast.xml`: the signed in-app update feed.
- `SHA256SUMS.txt`: release file checksums.
- `ReleaseNotes.md`: changes in that version.
- `SideDock-*-ThirdParty-Sources.zip`: sources and build recipes for bundled third-party components. Additional licenses and source archives are included in the app under `Contents/Resources/ThirdParty`.

This repository hosts release assets and this download page. Development is maintained separately.
