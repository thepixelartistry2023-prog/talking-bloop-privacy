# Privacy Policy — Talking Bloop

**Last updated: 16 October 2026**

Talking Bloop is a toy. It does not have accounts, it does not have servers, and
it does not send anything you do to anyone.

## The short version

Everything the app records or remembers stays on your device. Nothing you say
is uploaded, and nothing you do is sold. The app shows ads from Google AdMob,
see the Advertising section below. Apart from that, there is no analytics and
no tracking of any kind.

## The microphone

Talking Bloop listens through your device's microphone so that Bloop can repeat
what you say back to you in a silly voice. This is the whole point of the app.

- Recording happens **only while the app is open and in the foreground.** The
  app releases the microphone the moment you switch away from it, and it does
  not record in the background.
- Each recording is written to a temporary file in the app's private cache,
  played back once, and **deleted immediately afterwards.**
- Recordings are **never uploaded.** The app contains no code that sends audio
  anywhere. The only network use is loading ads, described below, and none of it
  carries your voice.
- Nothing is transcribed. The app does not use speech recognition and has no
  idea what you said — it only measures how loud the sound is, so it knows when
  you started and stopped talking.

You can revoke microphone access at any time in your device's settings. The app
will still open; Bloop simply will not be able to hear you.

## What is stored on your device

The app keeps one small save file, in its own private storage, containing:

- your level, experience and coins
- how hungry Bloop is
- your best scores and progress in the mini-games

This never leaves your device. Uninstalling the app deletes it.

## Advertising

Talking Bloop shows ads from Google AdMob, a service provided by Google. To show
and measure ads, Google's ad SDK may collect the device's advertising ID, IP
address, app and device details, and information about ads you view or click.

- The app tells Google the audience is children. Ads are **not personalised**,
  and only ads suitable for a general audience are shown.
- Users in the European Economic Area, the UK and Switzerland see Google's consent
  form on first launch. Ads only load after you have answered it.
- Ads appear only between games or when you choose to watch one for a bonus or
  to continue a game. They never appear while you are playing a game.

Google's use of data is described in its privacy policy at
https://policies.google.com/privacy.

## Children

Talking Bloop has no in-app purchases, no social features, no links out of the
app, and no user-generated content that anyone else can see. Ads shown in the app
are the non-personalised, child-appropriate kind described above. Nothing else is
collected from anyone, of any age.

## Permissions

| Permission | Why |
| --- | --- |
| Microphone (`RECORD_AUDIO`) | So Bloop can hear you and repeat you back. |
| Modify audio settings (`MODIFY_AUDIO_SETTINGS`) | To route playback through the speaker at a sensible volume. |
| Keep screen awake (`WAKE_LOCK`) | So the screen does not dim while you are playing with Bloop. |
| Internet (`INTERNET`, `ACCESS_NETWORK_STATE`) | To load ads from Google AdMob. |
| Advertising ID (`AD_ID`) | Added by Google's ad SDK so ads can be shown and measured. |

The app explicitly declines several permissions that libraries would otherwise
request on its behalf — background recording, notifications, storage access and
others — because it does not need them.

## Changes

If this policy ever changes, the new version will be published at this address
and the date at the top will be updated.

## Contact

Questions about this policy can be sent to the developer at the contact address
listed on the app's store page.
