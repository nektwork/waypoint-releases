# Waypoint Releases

This repository is the public download and update channel for Waypoint.

It intentionally does not contain the application source code. The private source repository builds signed installer artifacts and publishes them here as GitHub Release assets.

## Download

Use the latest release page:

```text
https://github.com/nektwork/waypoint-releases/releases/latest
```

Typical Windows release assets:

```text
Waypoint_<version>_windows_x86_64-setup.exe
Waypoint_<version>_windows_x86_64-setup.exe.sig
latest.json
```

`latest.json` is used by the in-app automatic updater. Do not edit it by hand unless you are intentionally doing a manual release repair.

## Source Code

Waypoint is distributed as a closed-source application for now. This repository is only a release channel.

## Support

If you received a direct installer link, prefer downloading from the latest GitHub Release page so you can verify you are using the newest public build.
