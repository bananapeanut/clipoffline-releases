# ClipOffline Desktop Helper Releases

This repository hosts **release builds of the ClipOffline desktop helper** for macOS and Windows.

The helper is a small app that runs downloads on **your** computer using your own internet
connection and disk. [clipoffline.com](https://www.clipoffline.com) only creates and
tracks jobs – the helper does the actual fetching locally.

---

## Downloads

### macOS

- `ClipOfflineHelper-mac-<version>.zip`

Each macOS zip contains:

- `ClipOffline.app` – the desktop helper app.
- `install.txt` – step-by-step installation instructions.

### Windows

- `ClipOfflineHelper-win-<version>.zip`

Each Windows zip currently contains:

- `helper_main.py` – Python CLI helper.
- `requirements.txt` – Python dependencies.
- `README-windows-cli.txt` – usage instructions.

> ⚠️ Note: The Windows helper is currently provided as a Python CLI. You’ll need Python
> installed and a virtual environment to run it. A packaged Windows app may be added later.

---

## Installation (macOS)

The macOS install instructions in `install.txt` are:

```text
ClipOffline Helper – macOS install instructions
==============================================

1. Unzip the download
---------------------
You downloaded a file like:

    ClipOfflineHelper-mac-arm64.zip

Double-click it to unzip. This will give you:

    ClipOffline.app


2. Move the app to Applications
-------------------------------
Drag `ClipOffline.app` into your macOS Applications folder. For example:

    /Applications/ClipOffline.app


3. Open the app once
--------------------
In Finder, go to the Applications folder and double-click `ClipOffline.app`.

The first time you open it, macOS may warn you that it’s from the internet or an
unidentified developer. If you see this:

- Click “Open” to confirm you trust the app.

Opening it once lets macOS register it as the handler for:

    clipoffline://

links.


4. Use ClipOffline.com
----------------------
After the helper is installed and opened once:

- Go to https://www.clipoffline.com in your browser.
- Paste a video or audio URL.
- Click “Download with desktop app”.

Your browser will launch the ClipOffline helper when needed, and downloads will be
saved directly to your computer (typically in a “ClipOffline” folder inside your
Downloads).
