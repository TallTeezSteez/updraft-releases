# Updraft downloads

Free dictation and meeting notes for Windows and Mac.

## Download

- **Windows:** [Updraft-Setup.exe](https://github.com/TallTeezSteez/updraft-releases/releases/latest/download/Updraft-Setup.exe)
- **Mac (Apple silicon):** [Updraft-Mac.dmg](https://github.com/TallTeezSteez/updraft-releases/releases/latest/download/Updraft-Mac.dmg)

These links always get the newest version. Older versions: [all releases](https://github.com/TallTeezSteez/updraft-releases/releases).

**First time:**
1. Run the installer.
2. If Windows shows **"Windows protected your PC"**, click **More info**, then **Run anyway**. You only do this once.

Updraft updates itself after that.

More about Updraft, with screenshots: https://draftlineapps.com/updraft

`latest-windows.json` and `latest-mac.json` are the signed files installed copies read to update themselves.

## How a new version goes out

Updraft is the one app built on Wyatt's own computers (its update-signing key and Mac certificate live there): in the updraft repo, `npm run release -- <version>` on the PC, then `npm run release -- --same-version` on the Mac. It posts the same permanent file names as every other app.

This repo is public so the downloads work for everyone. The app's code is in a private repo and isn't here.
