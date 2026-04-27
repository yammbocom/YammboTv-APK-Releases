# YammboTv-APK-Releases

Public distribution channel for YamboTV APK builds (`com.msandroid.mobile`).

Each tagged release contains a signed `YamboTV-modded-vN-signed.apk` ready to install. Source code lives in the private companion repo [`YammboTv-APK`](https://github.com/yammbocom/YammboTv-APK).

## Latest release

Always check [Releases](https://github.com/yammbocom/YammboTv-APK-Releases/releases) for the most recent build. The "latest" release is also exposed at:

```
https://api.github.com/repos/yammbocom/YammboTv-APK-Releases/releases/latest
```

The app uses this endpoint to detect new versions and offer in-app updates.

## Installation

Direct install:

```bash
adb install -r YamboTV-modded-vN-signed.apk
```

Or download to your device and tap to install. Same package + same certificate as previous builds, so no uninstall is needed when updating.

## Mirror

Builds are also mirrored at [`tv.yammbo.com/download/YamboTV.apk`](https://tv.yammbo.com/download/YamboTV.apk) (always points to the latest stable build).
