# Privacy Policy — Tabata Quest App

_Last updated: 2026-07-16_

## Summary

Tabata Quest is a **fully offline workout timer**. The app contains **no
advertising, no analytics and no tracking SDKs**, and it does not send any data
off your device. Everything (workout configuration, XP, preferences) is stored
**only on your device** in the operating system's private application storage
(Android `AsyncStorage`).

If you uninstall the app, that local data is removed by the operating system.

## What we collect

**Nothing.** Tabata Quest does not have a backend and does not integrate
any third-party data-collecting service. The developer does not receive, store,
or have access to any personal data about you.

## Third-party services

None. The app does not embed advertising, analytics, crash-reporting or any
other third-party SDK that collects data.

## Children

The app does not knowingly collect personal data from anyone, including
children — it collects no data at all.

## What we store on your device

Kept locally and never sent off-device:

- Saved workouts (name, work / rest times, rounds, sets, exercises)
- Selected language and mascot (including mascot evolution progress)
- Total XP, daily XP counter and the most recent completed workouts
- Sound, vibration and voice-assistant preferences

## Permissions requested (Android)

| Permission | Why |
|------------|-----|
| `VIBRATE` | Haptic feedback during work / rest transitions |
| `WAKE_LOCK` / foreground service (media playback) | Keeps the timer cues playing while the screen is off |
| `INTERNET` / `ACCESS_NETWORK_STATE` | Required by the underlying framework tooling; the app makes no network requests of its own |

The app actively **declares it does not use** location, camera, microphone,
contacts, calendar, external storage, phone state or Bluetooth
(see `app.json` → `android.blockedPermissions`).

## Your choices

- **Stop all local storage:** uninstall the app — all data is removed with it.

## Changes to this policy

Updates will be reflected in this file in the public repository and on the
store listing's privacy policy URL.

## Contact

For privacy-related questions, contact: **suribel.labs@gmail.com**
