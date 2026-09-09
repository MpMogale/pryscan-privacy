---
layout: default
title: Privacy
---

# Privacy Policy

**Effective date:** 8 September 2026
**Contact:** pryscan@gmail.com

> This is a draft prepared from the app's actual behaviour, not legal advice.
> Have it reviewed before publishing, particularly if you plan to distribute in
> the EU or California, where specific wording and disclosures may apply.

## The short version

Pryscan does not collect anything about you. There are no accounts,
no analytics, no advertising, and no tracking. Your baskets, trips and settings
are stored only on your own device.

The app makes exactly one kind of network request: fetching public exchange
rates. That request contains nothing about you or your shopping.

## What the app does with your camera

Pryscan reads shelf prices through the camera. When you scan:

1. A still photo is captured.
2. Text recognition runs **entirely on your device**, using Google's ML Kit
   library bundled inside the app. The image is not uploaded anywhere.
3. The photo is deleted from the device's temporary storage as soon as it has
   been read.

Photos are never saved to your photo library, never transmitted, and never seen
by anyone but you. Camera access is requested only when you open the scanner,
and the app works without it — prices can be typed in by hand.

## What is stored, and where

The following is kept **on your device only**, in the app's private storage:

- Your home and shopping currencies, and other settings
- Your trip budget, if you set one
- The current basket: prices, quantities and any names you type
- Finished trips, with the totals as they stood when you closed them
- Downloaded exchange rates, and any rate you enter by hand

None of this is sent anywhere. It is not backed up to any server we control. It
may be included in your own device backups (iCloud or otherwise) if you have
those enabled — those backups are governed by Apple's privacy policy, not ours.

**Deleting the app deletes all of it.** There is nothing held elsewhere to
request, export or erase, because nothing left your device.

## The one network request

To convert between currencies, the app downloads a table of public exchange
rates from `open.er-api.com`, operated by ExchangeRate-API.

- The request is the same for every user and contains **no** personal
  information, no identifier, and nothing about what you scanned or bought.
- As with any internet request, the provider necessarily sees the IP address it
  came from. We neither collect nor receive that.
- Rates are cached on your device so the app works offline. It will not contact
  the network again until they are stale.

Their privacy policy: https://www.exchangerate-api.com/terms

## What the app does not do

- No account, sign-up, email address or phone number
- No analytics, crash reporting, or usage measurement
- No advertising, and no advertising identifiers
- No location access
- No contacts, photos library, microphone or health data
- No third-party SDKs that transmit data
- No selling or sharing of data, because there is none to sell or share

## Children

The app is not directed at children and collects no personal information from
anyone, including children under 13.

## Changes

If this policy changes, the updated version will be published here and the
effective date above updated. Material changes will be noted in the app's
release notes.

## Contact

Questions about this policy: pryscan@gmail.com
