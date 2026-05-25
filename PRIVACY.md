# Privacy Policy — Tabata Timer ABS App

_Last updated: 2026-05-25_

## Summary

Tabata Timer ABS is an **offline workout timer**. The app does **not** collect, transmit, or
share any personal data. All information you enter (workout names, configured
times, XP progress) is stored **only on your device** using the operating system's
private application storage (Android `AsyncStorage` / iOS UserDefaults sandbox).

If you uninstall the app, that local data is removed by the operating system.

## What we collect

**Nothing.** Tabata Timer ABS does not have a backend. It does not perform any network
requests. It does not contain advertising SDKs, analytics SDKs, or crash
reporting services.

## What we store on your device

The following is kept locally on your device and is never sent off-device:

- Saved workouts (name and configuration: work time, rest time, rounds, sets, exercises)
- Selected language
- Selected mascot
- Total XP and the last few completed workouts (most recent 5)
- Sound and vibration preferences

## Permissions requested

| Platform | Permission | Why |
|----------|-----------|-----|
| Android  | `VIBRATE` | Haptic feedback during work / rest transitions |
| iOS      | (none)    | Audio playback and haptics use APIs that do not require user-facing permission prompts |

The app actively **declares it does not use** location, camera, microphone,
contacts, calendar, storage, phone state, Bluetooth, or network access
(see `app.json` → `android.blockedPermissions`).

## Children

The app does not knowingly collect any data from children under 13. Because the
app does not collect any data from anyone, this is enforced by design.

## iOS encryption export compliance

Tabata Timer ABS does not use, contain, or access any cryptographic functions beyond
those provided by Apple's operating system (`ITSAppUsesNonExemptEncryption = NO`).

## Changes to this policy

Updates will be reflected in this file in the public repository and, when the
app is published, on the store listing's privacy policy URL.

## Contact

For privacy-related questions, contact: **suri.arm@gmail.com**
