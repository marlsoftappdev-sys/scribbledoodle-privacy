# Privacy Policy for Colin - My Phone Hates Me

Last updated: 5 November 2026

This policy applies to the Android app **Colin - My Phone Hates Me**
(package `com.marlsoft.colinpaid`), published by Marlsoft.

## Overview

Colin is an offline screen-time companion. There is no login, no account and
no cloud. Everything Colin knows about your phone stays on your phone.

## Data we collect

**None.** We do not collect, store, transmit or sell any personal data. No
name, email address, location, contacts, photos, messages, or device
identifiers ever leave your device. There is no analytics, no crash reporting,
no advertising and no tracking of any kind.

The app does not hold the `INTERNET` permission, which means Android itself
prevents it from sending anything to us or to anyone else. (The build does
declare `ACCESS_NETWORK_STATE`, a read-only connectivity query inherited from
standard Android support libraries; it cannot transmit data.)

## Data that stays on your device

The following is read or stored locally, only on the device, and is never
uploaded:

- **Screen time and app usage** (`PACKAGE_USAGE_STATS`, granted by you in
  Android's Usage Access settings) — used to compute screen time and change
  Colin's mood. Read on-device only.
- **App names of installed apps** — so Colin can show your stats by app.
- **Contacts** (`READ_CONTACTS`) — read only when a parent chooses, from
  Colin's own parental settings, which contacts may be called during curfew.
  Colin does not read, store or upload your address book; it resolves only the
  contact the parent picks.
- **Notifications** (notification listener) — Colin uses a notification
  listener service to know when it has been swiped away, which is the whole
  point of the character. Notification content is not stored or transmitted.
- **Parental rules, limits, curfew schedules, PIN and reminder settings** —
  stored in the app's private storage on that device. Never sent to us or to
  any server.

## Special app access

Colin asks for these only if you choose to use the features that need them,
always after an in-app explanation screen:

- **Usage Access** — to measure screen time.
- **Accessibility service** — used solely by the optional parental controls to
  enforce curfew, daily limits and the settings guard. It does not read text
  you type, does not capture screen content, and its data is never transmitted.
- **Notification listener** — to detect when Colin's notification is dismissed.
- **Display over other apps** — used only by the optional chat-head bubble in
  later versions.
- **Call redirection role** — used only by the optional curfew phone rule, so a
  call to a number the parent has not allowed can be cancelled. Emergency
  numbers are never intercepted.
- **Alarms and reminders** — for the optional medication reminder and Colin's
  daily nudges.

## Sharing

We share nothing with anyone. There are no third-party SDKs, ad networks,
analytics providers or data brokers in this app.

## Children

Colin does not collect personal data from anyone, including children under 13.
All processing happens on the device.

## Your rights and data deletion

Because no personal data is collected or stored off your device, there is
nothing for us to hold, disclose or delete. You can delete all locally stored
Colin data at any time by clearing the app's storage in Android settings or by
uninstalling the app. If you have questions about GDPR or any other privacy
law, contact us and we will answer them.

## Changes

If this policy changes, the updated version will be published at this URL with
a new "last updated" date.

## Contact

marlsoftappdev@gmail.com
