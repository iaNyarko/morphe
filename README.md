# Morphē

**One photo a day. Watch yourself change.**

Morphē (Greek *μορφή*, "form, shape", the root of *metamorphosis*) is a free progress-photo app. Take a photo every day lined up with yesterday's outline, and after a few weeks develop the whole roll into a timelapse video.

**Open the app:** https://ianyarko.github.io/morphe/

---

## Features

| | |
|---|---|
| **Face and Full body** | Two separate rolls: face for hair, beard or skin; full body for fitness |
| **Line-up modes** | Show yesterday's photo as a red **Outline**, a **Split** screen (half now, half yesterday), a faint **Ghost**, or **Off** |
| **Adjust** | After taking a photo, drag, pinch and tilt it to match yesterday's outline, so slightly-off days still give a smooth video |
| **Dashed outline** | An oval for faces, a full figure with a floor line for bodies |
| **Timer** | 3 or 10 seconds, so you can prop the phone up and step back |
| **Notes** | Add a note to any day, like "78 kg" or "started gym" |
| **Roll** | Every day as a frame; missed days show as blanks |
| **Compare** | Drag a slider between any two days |
| **Develop** | Turn the roll into a video with date stamps, notes and smooth fades, then share it |
| **PIN lock** | Keeps casual snoopers out of your photos |
| **Backup** | Save every photo in one .zip and restore it on a new phone |

## Getting started

1. Open **https://ianyarko.github.io/morphe/** and **add it to your Home Screen**:
   - iPhone: in **Safari**, tap **Share → Add to Home Screen**
   - Android: in **Chrome**, tap **⋮ → Install app**
2. Open Morphē from the new icon and allow the camera.
3. Pick **Face** or **Full body**, line up with the dashed guide, and take your first photo. From day two, match yesterday's red outline (or try **Split**), and use **Adjust** if you're slightly off.
4. Come back every day. Same spot, same light, same pose.
5. After a few weeks, open **Develop** and make your video.

> **Why install it?** On iPhone, Safari can clear a website's saved data if you don't open it for about a week. Apps added to the Home Screen are kept.

## What's new in v4

- Faster roll: small thumbnails are saved with each photo (older photos get them automatically).
- Light check in the camera ("too dark", "darker than yesterday") and an "Even out the lighting" option for videos.
- Status / Reels 9:16 videos, plus an optional "Made with Morphē" end card.
- Smart align is now in Settings for everyone (beta), and any photo can be set as your line-up reference.
- Daily reminder via Google Calendar or any calendar app.
- Milestone cards at 7, 14, 30, 60, 100, 180 and 365 photos.
- Storage info in Settings and a monthly backup reminder.
- Lighter first load (the backup library only downloads when you back up).

## Privacy

- Your photos are stored **only on your phone**, in the app's own storage. They are never uploaded, including to this repository.
- The PIN lock stops someone casually opening the app. It does not encrypt the photos.
- Back up regularly from **Settings → Backup**. If you lose your phone without a backup, the photos are gone.
- The app counts anonymous visits with [GoatCounter](https://www.goatcounter.com) (no cookies, no personal data). It never sees your photos.

## Releasing an update

1. Upload the new `index.html`.
2. In `sw.js`, bump the version line (e.g. `morphe-v2` → `morphe-v3`) and upload it too.

---

Made by [@iaNyarko](https://github.com/iaNyarko) in Accra, built with the help of Claude.
