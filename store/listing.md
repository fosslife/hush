# Play Store listing copy

Paste into Play Console → Main store listing.

## App name (30 max — 28 used)

```
Hush: Block Calls by Pattern
```

## Short description (80 max — 70 used)

```
Block spam callers by pattern, not one number at a time. Works offline.
```

## Full description (4000 max — ~2000 used)

```
If the same company keeps calling you from a slightly different number every time,
blocking them one number at a time gets you nowhere. Hush lets you block the whole
range at once: write +91 80 4718 and every number starting with those digits stops
ringing.

There are four ways to write a rule:

- the exact number
- anything starting with certain digits
- a pattern, where # stands for one digit and * for any run of them
- a regular expression, if you want that much control

Each rule can block the call, silence it so it still shows up as a missed call, or
always let it through. That last one is for exceptions — block the whole +91 80 4718
range, but let your bank at +91 80 4718 0000 ring normally.

Tell Hush your country code once and it stops mattering how a number is written. A
rule you typed as 080 4718 will still catch a call from +91 80 4718, and the other way
round.

Nothing you do in Hush leaves your phone. The app has no internet permission at all —
it is stripped out when the app is built, so it cannot send anything anywhere even if
it tried. No account, no ads, no analytics, no caller ID lookups, no shared spam list.
Your rules and your call history sit in the app's own storage and are left out of cloud
backups. If you want a copy, you export it to a file yourself.

Hush also won't guess for you. The Blocked tab lists every call it screened, including
the ones that rang through, and tapping one opens the rule editor with that number
already filled in. What to block is yours to decide.

Open source under GPL-3.0: https://github.com/fosslife/hush

A few things worth knowing before you install:

- You need Android 10 or newer.
- Android only lets one app screen calls at a time, so Hush takes over from Truecaller
  or whatever you use now.
- Calls from people saved in your contacts never reach a screening app. That is
  Android, not Hush. To block someone you have saved, use the Contacts tab, which turns
  on Android's own send-to-voicemail switch for them.
- It can't filter text messages. Android only allows your default SMS app to do that.
```

## Other listing fields

- **App icon:** `icon-512.png`
- **Feature graphic:** `feature-graphic-1024x500.png`
- **Phone screenshots:** `screenshots/1-rules.png` … `4-settings.png`
- **Category:** Tools
- **Tags:** call blocking, privacy
- **Privacy policy URL:** `https://raw.githubusercontent.com/fosslife/hush/master/PRIVACY.md`
