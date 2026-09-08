Privacy Policy — Talking Bloop
Last updated: 6 September 2026

Talking Bloop is a toy. It does not have accounts, it does not have servers, and it does not send anything you do to anyone.

The short version
Everything the app records or remembers stays on your device. Nothing is uploaded, nothing is shared, and nothing is sold. There is no analytics, no advertising, and no tracking of any kind.

The microphone
Talking Bloop listens through your device's microphone so that Bloop can repeat what you say back to you in a silly voice. This is the whole point of the app.

Recording happens only while the app is open and in the foreground. The app releases the microphone the moment you switch away from it, and it does not record in the background.

Each recording is written to a temporary file in the app's private cache, played back once, and deleted immediately afterwards.

Recordings are never uploaded. The app contains no code that sends audio anywhere, and makes no network requests of any kind.

The app does hold the Android internet permission. It is added automatically by React Native, the framework the app is built with, and is present in every app built that way. Nothing in Talking Bloop uses it: there is no server, no account system, no analytics and no advertising, so there is nothing for it to talk to.

Nothing is transcribed. The app does not use speech recognition and has no idea what you said — it only measures how loud the sound is, so it knows when you started and stopped talking.

You can revoke microphone access at any time in your device's settings. The app will still open; Bloop simply will not be able to hear you.

What is stored on your device
The app keeps one small save file, in its own private storage, containing:

your level, experience and coins
how hungry Bloop is
your best scores and progress in the mini-games
This never leaves your device. Uninstalling the app deletes it.

Children
Talking Bloop contains no advertising, no in-app purchases, no social features, no links out of the app, and no user-generated content that anyone else can see. Nothing is collected from anyone, of any age.

Permissions
Permission	Why
Microphone (RECORD_AUDIO)	So Bloop can hear you and repeat you back.
Modify audio settings (MODIFY_AUDIO_SETTINGS)	To route playback through the speaker at a sensible volume.
Keep screen awake (WAKE_LOCK)	So the screen does not dim while you are playing with Bloop.
Internet (INTERNET, ACCESS_NETWORK_STATE)	Declared by React Native, the framework the app is built with. Talking Bloop does not use it — see the microphone section above.
The app explicitly declines several permissions that libraries would otherwise request on its behalf — background recording, notifications, storage access and others — because it does not need them.

Changes
If this policy ever changes, the new version will be published at this address and the date at the top will be updated.

Contact
Questions about this policy can be sent to the developer at the contact address listed on the app's store page.
