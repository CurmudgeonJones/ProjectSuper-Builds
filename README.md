# Project Super: builds

Download the latest test build of Project Super here. This repo holds builds only, no source code.

## Download

| System | Download |
|---|---|
| Windows | [ProjectSuper-windows.zip](https://github.com/CurmudgeonJones/ProjectSuper-Builds/releases/latest/download/ProjectSuper-windows.zip) |
| Linux | [ProjectSuper-linux.tar.gz](https://github.com/CurmudgeonJones/ProjectSuper-Builds/releases/latest/download/ProjectSuper-linux.tar.gz) |
| Mac | [ProjectSuper-mac.zip](https://github.com/CurmudgeonJones/ProjectSuper-Builds/releases/latest/download/ProjectSuper-mac.zip) |

The [Releases page](https://github.com/CurmudgeonJones/ProjectSuper-Builds/releases/tag/latest) shows the version, commit and date of the current build.

Everyone playing online must run the same version. Download again when a new build is announced.

## Windows

1. Unzip the file.
2. Run `ProjectSuper.exe`.
3. If Windows SmartScreen warns you, click **More info**, then **Run anyway**.

## Linux

```
tar xzf ProjectSuper-linux.tar.gz
./ProjectSuper/ProjectSuper.x86_64
```

If it will not start, run `chmod +x ProjectSuper/ProjectSuper.x86_64` first.

## Mac

1. Double-click the zip. Move `ProjectSuper.app` somewhere, such as Applications.
2. The app is not signed, so macOS blocks it. Right-click the app, choose **Open**, then click **Open**.
3. On macOS 15 and newer: try to open it once. Then go to System Settings, Privacy & Security, and click **Open Anyway**.
4. If macOS says the app is damaged, run this in Terminal:

```
xattr -dr com.apple.quarantine /path/to/ProjectSuper.app
```

## How to report a bug

- In the game: use the **Report a Bug** button (title screen and pause menu). It saves a zip with the version, log and a screenshot and opens a prefilled GitHub issue on this repo. You need a free GitHub account to submit it; attach the zip to the issue.
- If the button does not work: send the log. On Windows it is in `%USERPROFILE%\AppData\LocalLow\Project Super\Project Super\Player.log`.
- Or [open an issue](https://github.com/CurmudgeonJones/ProjectSuper-Builds/issues/new) by hand.
- Give the version number (title screen), what you clicked just before, and the round.

## Honest notes

These are test builds. The Linux and Mac builds have not been tested on real machines yet. Please tell us if they start or not.
