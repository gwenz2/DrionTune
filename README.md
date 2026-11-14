<div align="center">
  <img src="assets/icon.png" alt="DrionTune Icon" width="88" height="88" />
  <h1>DrionTune</h1>
  <p><strong>Stop background apps from stealing RAM and overheating your phone while gaming. No root needed.</strong></p>
  <p>Built for 3 GB to 6 GB Android phones that stutter mid-match when Facebook, shopping apps, and system services wake up in the background.</p>

  <p>
    <img src="https://img.shields.io/badge/Android-8.0%2B-10b981?style=flat-square&logo=android&logoColor=white" alt="Android 8.0+" />
    <img src="https://img.shields.io/badge/Root-Not%20Required-38bdf8?style=flat-square" alt="No Root Required" />
    <img src="https://img.shields.io/badge/Requires-Shizuku-6366f1?style=flat-square" alt="Requires Shizuku" />
    <a href="https://github.com/gwenz2/DrionTune/releases/latest/download/app-release.apk">
      <img src="https://img.shields.io/badge/Download-APK%20v1.0.0-10b981?style=flat-square" alt="Download APK" />
    </a>
  </p>

  <p>
    <a href="https://github.com/gwenz2/DrionTune/releases/latest/download/app-release.apk"><strong>Download DrionTune v1.0.0 (APK)</strong></a>
    &nbsp;|&nbsp;
    Requires free <a href="https://shizuku.rikka.app/">Shizuku</a> app
  </p>
</div>

---

## Screenshots

<table>
  <tr>
    <td align="center"><strong>Live CPU, RAM, ZRAM & 1-Click Fix</strong></td>
    <td align="center"><strong>Real App Freezer & Game Launcher</strong></td>
  </tr>
  <tr>
    <td><img src="assets/dashboard.jpg" alt="DrionTune Dashboard" width="300" /></td>
    <td><img src="assets/launcher.jpg" alt="DrionTune Game Launcher" width="300" /></td>
  </tr>
</table>

---

## <img src="assets/icons/cpu.svg" width="18" height="18" align="absmiddle" /> Why Other "Lag Fixers" Fail

<p align="center">
  <img src="assets/comparison.svg" alt="Play Store Boosters vs Root Tweaks vs DrionTune" width="100%" />
</p>

Play Store booster apps play a rocket animation and close apps that Android restarts 5 seconds later, burning more battery and RAM.

DrionTune uses Android's own system commands through Shizuku to actually **suspend** selected background apps (`0%` CPU, `0 MB` RAM) until you tap **Restore All Apps**. When you switch into your game, DrionTune stops polling telemetry so it does not eat CPU either.

---

## <img src="assets/icons/check.svg" width="18" height="18" align="absmiddle" /> What It Does

1. **1-Click Fix Lag:** Clears cache bloat, trims memory, and stops heavy background processes while showing live CPU, RAM, ZRAM swap, and battery temperature.
2. **Game Launcher:** Freezes noisy apps (social media, shopping, banking) before launching your game and keeps battery saver from throttling it.
3. **Restore All Apps:** One tap brings every paused app and its notifications right back after gaming.

---

## <img src="assets/icons/warning.svg" width="18" height="18" align="absmiddle" /> Downsides & Use at Your Own Risk

- **Needs Shizuku:** Android blocks normal apps from freezing other apps, so you must start Shizuku via Wireless Debugging once (and again after a reboot).
- **Frozen apps stay silent:** While an app is frozen for gaming, it will not send notifications until you tap Restore All Apps.
- **Hardware limits:** Freeing RAM and cooling thermals reduces stutter, though it cannot turn an old processor into a flagship chip.
- **Use at your own risk:** Tested on 3 phones. Because DrionTune uses Shizuku system privileges, disabling critical system apps or applying unsafe tweaks can break apps or cause missed notifications. The developer is not responsible for issues from misuse.
- **Free vs Pro:** Dashboard, 1-Click Fix Lag, and Game Launcher are free with ads, plus a 30-minute System Tweaks trial via rewarded ad. Pro ($3 one-time on [Gumroad](https://gwennydev.gumroad.com/l/driontune-pro)) unlocks Debloater, permanent System Tweaks, and removes all ads.

---

## <img src="assets/icons/shield.svg" width="18" height="18" align="absmiddle" /> Setup & In-App Updates

1. Install **Shizuku** from Google Play and start it via Wireless Debugging in Developer Options.
2. Install **DrionTune** (`app-release.apk`) and tap Allow when Shizuku asks for permission.
3. Open the menu and tap **Check for Updates** whenever a new version drops to download and install in place.
