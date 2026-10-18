---
layout: document
title: "Privacy policy — Dice Roll Calculator"
lang: en
permalink: /dicerollcalculator/legal/en/privacy-policy
counterpart: /dicerollcalculator/legal/fr/confidentialite
counterpart_lang: fr
---
_Last updated: 2026-10-18_

> Courtesy translation — only the [French version](/dicerollcalculator/legal/fr/confidentialite) is authoritative.

## 1. Data controller

François LAMBERT — see the [legal notice](/dicerollcalculator/legal/en/legal-notice). Contact: app.dicerollcalculator.polyester538@passmail.net

## 2. Data collected

| Data | Purpose | Legal basis |
|------|---------|-------------|
| Advertising identifier (IDFA on iOS, Google advertising ID on Android) — **free version, iOS and Android only** | Displaying personalised advertising through Google AdMob | Consent (Google UMP SDK, supplemented on iOS by App Tracking Transparency) |
| Dice roll history | App functionality — stored **locally only** (SQLite — Application Support directory on iOS/macOS, private internal storage on Android), never transmitted | — (no transmission, no legal basis required) |
| Purchase receipt (App Store or Google Play, depending on the platform) — **paid version only** | Validating the "remove ads" purchase | Performance of a contract (the purchase) |
| Technical diagnostic data when the app crashes — **all versions, all three platforms** | Fixing defects in the app (§4) | Legitimate interest: keeping the app reliable |

The paid version — or the free version once "remove ads" has been purchased — displays **no advertising**. Once it knows the purchase has been made, the app no longer starts the Google SDK: no consent form, no tracking authorisation request, no advertising identifier transmitted. Two limits come from the way the SDK works: during the session in which you make the purchase, the SDK that has already started keeps running until the app is closed; after a reinstall or on a new device, it may start once, until the store confirms the purchase. The crash reports described in §4 do apply to it like to any other version: fixing a crash does not depend on how the app is funded.

**The home screen widget reads the same data, on the device.** On iOS and macOS, saved rolls and the last roll are copied into a container shared between the app and its extension (an "App Group"): that is the only way an extension can read its application's data. On Android, the widget opens the app's local database directly. In both cases nothing leaves the device — with the understanding that a roll name you choose may then be displayed on your home screen.

**The macOS version displays no advertising**, including in its free form: Google AdMob does not cover that platform. It therefore collects no advertising identifier. The crash reports in §4, however, apply to it as well.

## 3. Advertising and third parties

On **iOS and Android**, the free version displays advertising through **Google AdMob** (Google Ireland Limited). AdMob may receive the device's advertising identifier in order to serve personalised ads, subject to the consent collected through the Google UMP (User Messaging Platform) SDK, supplemented on iOS by the App Tracking Transparency authorisation. Advertising is loaded only **after** the consent form has been answered.

To serve and measure ads and to prevent fraud, Google's SDK also transmits, including for non-personalised ads, the device's **IP address** (from which Google may infer an **approximate location** — never the precise location), **interactions** (app launch, taps, video views) and **diagnostic information** about how the app and the SDK run. Google processes this data under its own policy, below. The macOS version, which does not include AdMob, transmits none of it.

- Google AdMob privacy policy: https://policies.google.com/technologies/ads

## 4. Crash reports

When the app closes unexpectedly, a technical report is sent to **Sentry** (Functional Software, Inc.) so that the defect can be fixed. This applies to **all versions and all three platforms** — it is independent of advertising and of the "remove ads" purchase.

**What the report contains**: the crash stack trace, the app version, the operating system version, the device model, the language, and an installation identifier drawn at random by the app. That identifier only serves to tell how many distinct devices a given defect affects; it does not designate you, and it disappears if the app is uninstalled.

**What it does not contain**: no advertising identifier, no screenshot, nothing from your roll history (saved roll names included), no email address. The app is configured not to transmit your IP address — with the understanding that, as with any connection to a server, the server sees the address the connection comes from at the moment it is made.

**Hosting**: the data is processed in Sentry's **European region** (Germany). Sentry acts as a processor.

- Sentry privacy policy: https://sentry.io/privacy/

**Legal basis**: legitimate interest — an app that crashes without its publisher being able to know it does not get fixed. You may object to this processing by writing to the contact address (§9).

## 5. Retention

- Roll history: kept locally until the app is uninstalled or the user clears the history (dedicated button in the app).
- Advertising identifier: managed by AdMob/Google, not stored by the app itself.
- Crash reports: deleted by Sentry after **30 days** (the retention of the plan in use).

## 6. Your rights (GDPR)

Under the GDPR, you have the right to access, rectify, erase and object to the processing of your data. To exercise those rights: app.dicerollcalculator.polyester538@passmail.net. Local history can also be cleared directly from within the app ("clear history" button).

## 7. App Tracking Transparency (iOS)

This mechanism is specific to iOS: Android has no mandatory equivalent (only GDPR consent through the Google UMP SDK applies, see §3), and macOS displays no advertising. In the free version on iOS, the app requests ATT authorisation after GDPR consent and before any tracking for advertising purposes. Declining does not prevent use of the app; advertising is still displayed, but not personalised.

## 8. Security

No data is transmitted to any server belonging to the app: there is no backend. The only data leaving the device does so through three third-party libraries, each under its publisher's privacy policy:

- **Google Mobile Ads** (free version, iOS and Android only — §3);
- **Sentry** (all versions, all three platforms — §4);
- **the Google Play Billing Library** (Android only, all versions), which handles in-app purchases. Whether or not a purchase is made, it sends Google, after the app starts, logs about its own operation together with technical characteristics of the device: model and manufacturer, Android version, language and country, mobile carrier, connection type, time zone and app version. Google does not publish the detailed content of these logs and processes them under its own policy: https://policies.google.com/privacy

## 9. Contact

app.dicerollcalculator.polyester538@passmail.net
