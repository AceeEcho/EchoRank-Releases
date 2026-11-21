# EchoRank

EchoRank ranks every FBS and FCS college football team and player with its own rating model, and gives every
team, player and game a page. This repository holds the downloads for the Windows app. It holds no source code.

## Install

1. Open the [app release](https://github.com/AceeEcho/EchoRank-Releases/releases/tag/app) and download
   **EchoRank-win-Setup.exe**. (If that page doesn't exist yet, the first version hasn't been published.)
2. Run it. Windows may show "Windows protected your PC" because the app isn't code-signed yet: choose
   **More info**, then **Run anyway**.
3. EchoRank installs for your Windows user only (no administrator rights), opens, and downloads its data once
   (about 200 MB). After that it starts in about a second.

Needs Windows 10 or 11.

## Updates

EchoRank keeps itself up to date. It checks when it starts and every hour while it is open, downloads new
ratings and new versions in the background, and tells you in the top-right corner. With no internet connection
it opens as it is and shows the data it already has.

Ratings, predictions and stats are computed by EchoRank and arrive as data updates, so what you see is as
fresh as the last update (shown in the top-right corner and in Settings).

## Remove it

Windows Settings → Apps → EchoRank → Uninstall. This removes the app and its downloaded data.

## About the files here

- The **app** release: the installer and the app's update packages.
- The **data** release: the data the app downloads. There is nothing to install from it by hand.

EchoRank is an independent project. It is not affiliated with or endorsed by the NCAA, any conference, school,
or data provider. Team names and logos belong to their owners.
