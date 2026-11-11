# Privacy Policy — Scribble & Doodle

_Last updated: 11 November 2026_

Scribble & Doodle (the "App") is published by **Marlsoft** ("we", "us").
Contact: marlsoftappdev@gmail.com

## The short version

- The App needs **no account** and we never ask for your name, email, or any
  personal details.
- Your game progress stays **on your device** — plus, when Android backup is on,
  a copy in your own Google Drive (see *Cloud backup*).
- The App offers **optional rewarded ads** from **Google AdMob**. No ad is ever
  shown unless you tap "WATCH AD" to earn coins — you can play the whole game
  without ever watching one. One video is fetched in advance so it starts
  instantly; that fetch is the only ad traffic you do not start by tapping.
- We run **no servers** and never see your data. Google, as the ad provider,
  receives limited technical information (detailed below) in order to serve and
  measure an ad.

## What the App stores (on your device only)

Your progress — stars per level, coin balance, skip count, the date of your last
daily coin gift, how many ads you have watched today, the order of puzzles in
your current run — and settings such as sound and haptics are saved **locally on
your device** using Android's standard local storage (SharedPreferences). This
data:

- leaves your device only through the Android cloud backup described below,
- is not readable by us (we have no access mechanism),
- is deleted from the device if you uninstall the App.

### Cloud backup

Android's **Auto Backup** is switched on for this App, so the same progress file
can be copied to **your own Google Drive** and restored when you reinstall or
move to a new phone. That copy belongs to **your Google account**, not to us: we
cannot read it, list it, or restore it for you. It can also outlive an uninstall.

To remove a backup copy, delete this App's backup in your Google account
(Android **Settings → System → Backup**, or Google Drive → Backups); the copy is
also dropped when the account's backup is refreshed or expires. Turning Auto
Backup off before installing means no copy is ever made — the game works
identically either way.

## Advertising (optional, reward-based)

Coins can be earned by playing, by claiming a free daily gift, or by choosing to
watch a rewarded video. Only the third involves advertising.

- Ads are supplied by **Google AdMob** (Google Mobile Ads SDK).
- **No ad is ever shown unless you tap "WATCH AD"** in the coin shop. If you
  never open the coin shop, no video ever appears on screen.
- So that the video starts instantly, the App **fetches one rewarded video in
  advance** — at launch, and again after you finish watching one. That request
  reaches Google before you tap, and is the only ad-related traffic that does not
  follow a tap. If it fails (offline, no fill), the shop reports that no ad is
  available and nothing else happens.
- To serve and measure an ad, Google may collect and process: your device's
  advertising identifier (or an identifier set by the app on recent Android
  versions), your IP address, coarse location derived from that IP address,
  device model and operating-system version, app version and language, and your
  interaction with the ad (such as whether it was viewed to completion).
- This information is collected by **Google, not by us**. We receive only
  aggregate revenue reporting and cannot identify any individual player.
- Google's handling of that data is described in Google's Privacy Policy
  (https://policies.google.com/privacy) and "How Google uses information from
  sites or apps that use our services"
  (https://policies.google.com/technologies/partner-sites).

### Your choices

- **You are never required to watch an ad.** Ignoring the coin shop leaves the
  game fully playable; the daily gift costs you nothing.
- **Consent.** If you are in the European Economic Area, the United Kingdom or
  Switzerland, a Google-certified consent form appears when you first open the
  App, before any ad can be requested, and lets you accept or refuse
  personalised advertising. Refusing still lets you play — you may be offered
  non-personalised ads or none at all.
- **Changing your mind.** In those regions the coin shop shows an
  "Ad privacy settings" link that reopens the consent form at any time.
- **Resetting your advertising ID.** You can delete or reset the advertising
  identifier at any time in Android Settings → Privacy → Ads.

## Permissions

- **Vibrate** — haptic feedback on button presses.
- **Internet** and **Network state** — used by the Google Mobile Ads SDK to fetch
  a rewarded video and to check the consent requirement, and by nothing else in
  the App.

The Google Mobile Ads SDK adds the following to the installed app. They belong
to Google's advertising and Privacy Sandbox support; the App's own code never
uses them — it starts no foreground service and takes no wake lock:

- **`com.google.android.gms.permission.AD_ID`** — lets the SDK read the
  advertising ID so an ad can be measured.
- **`ACCESS_ADSERVICES_AD_ID`, `ACCESS_ADSERVICES_ATTRIBUTION`,
  `ACCESS_ADSERVICES_TOPICS`** — Android's Privacy Sandbox permissions, used by
  the ads SDK.
- **`WAKE_LOCK`** and **`FOREGROUND_SERVICE`** — declared by the ads SDK for its
  own ad loading and playback.
- **`DYNAMIC_RECEIVER_NOT_EXPORTED_PERMISSION`** — generated automatically by
  AndroidX so the App's internal broadcasts stay private to it.

The App requests **no** location, contacts, storage, camera, microphone,
calendar or SMS permission, and nothing beyond the permissions listed above.
Your progress is never uploaded by the App, and the feedback form is opened in
your own browser rather than sent by the App.

## Children

The App is a word-puzzle game suitable for all ages, but it is **not directed to
children under 13**: it is listed for a general (13+) audience and its ads are
supplied by Google under that audience setting. We do not knowingly collect
personal information from children. If you believe a child has used the App and
you have a concern about advertising data, contact us at the address above and
we will help you exercise the choices described in the Advertising section.

## Third-party services

Two third parties are involved, and neither is under our control:

- **Google Mobile Ads (AdMob)** and Google's consent SDK, **User Messaging
  Platform**, both from Google LLC — serve the optional rewarded video and handle
  the advertising data described above.
- **Tally** (tally.so) — hosts the feedback form that the FEEDBACK button opens
  **in your own browser**. The App sends nothing to it: only if you choose to
  fill the form in does Tally receive what you type (which may include an email
  address, if you enter one) along with your IP address and browser details,
  under Tally's privacy policy (https://tally.so/help/privacy-policy). Closing
  the form sends nothing.

The App contains no analytics, crash-reporting, social, or attribution SDKs, and
no advertising other than the optional rewarded video described above. All
puzzle artwork, characters and fonts are bundled inside the App.

## How to request deletion of your data

This page is the data deletion route for **Scribble & Doodle**, published by
**Marlsoft**. You do not need an account, and we hold no personal data about
you — but you can still ask us to delete anything associated with you, and here
is exactly how.

### Step by step

1. Email **marlsoftappdev@gmail.com** with the subject line
   **"Data deletion request"**.
2. Include whichever of these you have, so we can identify the request: the
   Google account you installed from, the approximate date you installed the
   App, or the Google Play order number from your purchase history. Because the
   App has no accounts, we cannot identify you from inside the App itself.
3. We reply within **30 days** confirming what was deleted, or explaining why
   nothing was held. If you ask us to, we will also tell you what we can see
   about your installation — which is nothing beyond the email you sent.

### What is deleted

- **Game progress** — stars, coin balance, skips, the date of your last daily
  gift, how many ads you have watched, and sound/haptics settings — lives on
  your device. It is erased when you uninstall the App or use the in-game run
  reset. It is never uploaded to us, so there is no server-side copy for us to
  delete.
- **Anything sent to us by email** as part of a deletion request is deleted once
  the request is closed, or within 30 days — whichever is sooner.

### What is kept, and for how long

- **A cloud backup copy** of local progress, if Android Auto Backup was on, sits
  in your own Google account. We cannot see or delete it; remove it from Android
  Settings → System → Backup, or from Google Drive → Backups.
- **Advertising data** collected by Google AdMob when you choose to watch a
  rewarded video (advertising identifier, IP address, coarse location derived
  from it, device model, OS version, app version and language, and your
  interaction with the ad) is held by **Google, not by us**. We cannot delete it
  on your behalf, and Google's retention periods are described in Google's
  Privacy Policy (https://policies.google.com/privacy).
- You can limit or remove that data yourself at any time: reset or delete your
  advertising ID in **Android Settings → Privacy → Ads**, or use the
  **"Ad privacy settings"** link in the App's coin shop to change or withdraw
  your advertising consent.

### If you are in the EEA, UK or Switzerland

Withdrawing consent through the coin shop's "Ad privacy settings" link stops
personalised advertising from that point on; already-collected data remains
subject to Google's retention as described above.

## Changes to this policy

If a future version of the App changes what it collects or how, this policy will
be updated **before** that version is released, and the Play Store Data Safety
form will be updated to match. The date at the top always reflects the current
version.

## Contact

Questions about this policy: marlsoftappdev@gmail.com
