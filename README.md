**Here's how to install the `NetrunnerRising.apk` on your Android phone / Android 16).**
 1. Download the APK
Tap the file below to download it to your phone:
(Alternatively, transfer it via USB, email, Google Drive, etc. if you already have it elsewhere.)
2. Allow installation from unknown sources
Android blocks APKs that don’t come from the Play Store by default. When you try to open the file, the system will usually prompt you. If not:
1. Go to **Settings → Apps → Special access → Install unknown apps** (or search for “Install unknown apps”).
2. Select the app you’ll use to open the APK (usually **My Files**, **Chrome**, or your browser).
3. Toggle **Allow from this source** on.
### 3. Install the APK
1. Open the **My Files** app (or your Downloads folder).
2. Find `NetrunnerRising.apk`.
3. Tap it.
4. Tap **Install** and wait for it to finish.
5. Tap **Open** (or find “Netrunner Rising” in your app drawer).
That’s it. This APK is a packaged web app (it wraps the Netrunner Rising interface in a WebView), so once installed it should run offline like a normal app.
Tip:** If the install is blocked or you get a “harmful app” warning, it’s just Android’s default caution for sideloaded APKs—you can proceed since you generated/own the file. After installing, you can turn the “Install unknown apps” permission back off for better security.
Netrunner Rising** is packaged as a borderless fullscreen Chromium kiosk (app mode) for Steam Deck, aimed at [https://netrunnerrising.neocities.org/](https://netrunnerrising.neocities.org/). It includes a controller layer so the left stick moves a highlight and A selects (B goes back).
Install (Desktop Mode)
1. Switch the Deck to **Desktop Mode**.
2. Unzip the folder somewhere convenient, e.g. `~/Downloads/netrunner-rising-deck`.
3. Open **Konsole**, `cd` into that folder, then run:
   ```bash
   chmod +x install.sh launch.sh
   ./install.sh
The script installs the Chromium Flatpak (if needed), sets up the app under `~/Applications/netrunner-rising`, and creates a desktop entry.
4. Launch **Netrunner Rising** from the application menu to test it.
Add to Gaming Mode
1. Still in Desktop Mode, open **Steam**.
2. Go to **Games → Add a Non-Steam Game → Browse**.
3. Select:
     /home/deck/Applications/netrunner-rising/launch.sh
4. Rename the entry to **Netrunner Rising**.
5. Optionally set the icon to `netrunner-rising.png` from the same folder.
6. Switch back to **Gaming Mode**, launch it, then open the controller icon on the game page and pick the **Gamepad** template (not Desktop). Desktop mode turns the left stick into a mouse and skips the highlight.
Controls
- **Left joystick** — move the cyan highlight  
- **A** — select / confirm  
- **B** — back (or leave a text box)  
- **Steam + X** — on-screen keyboard (for the handle name box)  
- Right stick is ignored.  
- Quit with **Steam + B** (or Alt+F4 in Desktop Mode).
### Notes
- Browser profile (handles, etc.) is stored at `~/.local/share/netrunner-rising`. Delete that folder to wipe saves.
- Default resolution is the Deck panel (1280×800). Override with:
  ```bash
  NR_WIDTH=1920 NR_HEIGHT=1080 ./launch.sh
 That’s the full process from the included `README.txt`. After the `install.sh` step it should appear ready to launch and add to Steam.# Netrunner-Rising

**How to install Netrunner Rising on iPhone / iPad**

This is a Progressive Web App (PWA), not an App Store app. You host the files online once, then use Safari’s “Add to Home Screen” so it runs fullscreen and works offline.

### Fastest way (if the site is already live)
1. Open **Safari** on your iPhone or iPad.
2. Go to:  
   `https://insightjokes.github.io/Netrunner-Rising/`
3. Tap the **Share** button (square with the upward arrow).
4. Tap **Add to Home Screen** → **Add**.
5. Launch Netrunner from the new Home Screen icon. It runs fullscreen and works offline.

### Host it yourself (recommended if the link above isn’t working)
Unzip `NetrunnerRising-iOS-WebApp.zip` and upload **everything** (index.html, sw.js, manifest.webmanifest, icons/, fonts/) to one of these free hosts:

**GitHub Pages**
1. Upload the files to the root of `https://github.com/InsightJokes/Netrunner-Rising`
2. Go to the repo → **Settings → Pages**
3. Set Source to “Deploy from a branch”, Branch `main`, folder `/` (root)
4. After a minute the game is live at the URL above. Then follow the Add to Home Screen steps.

**Neocities** (you’ve used this before)
1. Upload all the files to the root (or a subfolder) of your Neocities site.
2. Open the resulting URL in Safari.
3. Share → Add to Home Screen → Add.

### Important notes
- You **must** use Safari. Other browsers on iOS don’t support proper Add to Home Screen.
- The Home Screen version keeps its own saves (separate from Safari and from the Android version).
- To update later, just re-upload the new files to the same place and refresh (or remove + re-add) the Home Screen app.

I also saved a clean text version of these instructions you can download or share:



Let me know if you want a shorter version, a version tailored specifically for Neocities, or any changes.
**Netrunner Rising — Windows Download & Install Guide**

Here’s a simple, step-by-step guide you can share with anyone who wants to download and run

 **NetrunnerRising.exe** on Windows.

### Download Instructions

1. **Download the file**  
   Click the download link/button below to save `NetrunnerRising.exe` to your computer.  
   (Recommended location: your **Downloads** folder or Desktop.)

2. **Locate the file**  
   Open **File Explorer** and go to the folder where the file was saved (usually `Downloads`).

3. **Run the application**  
   - Double-click **NetrunnerRising.exe**.  
   - If Windows SmartScreen or antivirus shows a warning, click **More info** → **Run anyway** (this is normal for unsigned indie apps).

4. **Play**  
   The game should launch. No installation is required — it runs directly from the executable.

### Tips

- Keep the `.exe` file somewhere permanent if you want easy access later (or create a desktop shortcut by right-clicking → **Send to** → **Desktop**).
- The game checks for updates from the official site: **netrunnerrising.neocities.org**.
- Works on Windows 10 and Windows 11.

---

**Download the file here:**



That’s everything needed. Just share this text + the file and people can get running in under a minute.
