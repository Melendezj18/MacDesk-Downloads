# MacDesk downloads

MacDesk combines a customizable Dock and notch companion in one installation, with one shared menu-bar control.

## Download

[Download MacDesk 0.1.8 for Apple silicon](https://github.com/Melendezj18/MacDesk-Downloads/releases/download/v0.1.8/MacDesk-0.1.8-arm64.dmg) · [All releases and matching source](https://github.com/Melendezj18/MacDesk-Downloads/releases)

No GitHub account is needed. Requires an Apple silicon Mac running macOS 15.5 or newer. This is a personal, locally signed build, **not Apple-notarized**.

## Install

1. Open the DMG.
2. Drag MacDesk into Applications.
3. Open the installed app, then eject the disk image.

For upgrades, quit MacDesk normally and replace it in its existing folder, including ~/Applications if that is where you installed it. Avoid keeping two copies. macOS may require its normal approval in System Settings → Privacy & Security → Open Anyway. Do not disable Gatekeeper or change certificate trust.

The app asks for macOS privacy permissions only as needed for enabled integrations. New installations auto-hide MacDesk and temporarily suppress Apple's Dock edge reveal while MacDesk runs; its recovery guardian restores original Dock settings on normal quit/controller crash. Settings → Dock → General offers the opt-out.

## Updates

Download and replace the app manually from this repository. Version 0.1.8's built-in updater still targets the private development channel and does not provide account-free automatic updates. No token is needed to download, install or run MacDesk. Never share a GitHub token or signing key.

## Source and attribution

Each release includes a matching **MacDesk-VERSION-source.zip** plus checksums. Use this archive for the app source; GitHub's automatically generated source archives contain this download repository's documentation only. The source archive includes build scripts, lockfiles, resources and dependency provenance. See SOURCE_README.md inside it for build instructions.

MacDesk is a derivative of [Boring Notch v2.7.3](https://github.com/TheBoredTeam/boring.notch/releases/tag/v2.7.3), with an original Dock companion. MacDesk source is under [GPLv3](LICENSE); dependency notices are in [THIRD_PARTY_LICENSES](THIRD_PARTY_LICENSES) and the source archive. Independent project, not endorsed by upstream. DockFix was a feature reference; no DockFix code or assets are included.

The development repository remains private; this repository publishes release downloads and their corresponding source snapshots without development history or local test records.
