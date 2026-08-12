---
title: Lembrô Privacy Policy
lang: en
doc: privacy
home: /en/
tagline: Lembrô privacy policy and terms of use
---

# Lembrô Privacy Policy

**App:** Lembrô (`com.damcode.lembro`)
**Last updated:** 11 August 2026

> **This is a translation, provided for convenience.** Lembrô is developed in Brazil and this
> policy is governed by Brazilian law. If the two versions ever disagree, the
> [Portuguese version](../privacidade.html) is the one that prevails.

---

## In one sentence

**What you record stays on your phone, and only leaves it if you allow it.** There is no
sign-up, no account, and no server of ours holding your data. The three situations in which
something does leave the device — saving a backup, sending a summary, and being followed by a
carer — are all started and authorised by **you**, and each one is described below.

The rest of this document spells that out, because the law asks for detail — but the sentence
above is the whole rule.

## Who is responsible

This app is developed and maintained by **Carlos Moisés Batista Henrique**, under the name
**DamCode**, an individual developer, in Brazil.

**Channel for any privacy matter, including the requests provided for by the LGPD** (Brazil's
General Data Protection Law): `moizezhenrique@gmail.com`

We answer within 15 days, the deadline set by article 19 of the LGPD.

**About the data protection officer (DPO):** as a small-scale processing agent, and under
Resolution CD/ANPD no. 2/2022, there is no formally appointed officer — but the channel above
exists, is attended to, and is where any request, question or complaint should arrive.

## What data the app stores, and where

Everything below stays **exclusively in your phone's internal storage**, in a database that only
Lembrô can reach:

| What | What for |
|---|---|
| The name and detail of your reminders | Showing them on screen and in the notification |
| Times, days and repetition | Knowing when to notify you |
| Records ("took it at 08:12") | Building the history and the carer view |
| The identifier of your NFC tags and the name you gave them | Recognising the sticker when you tap your phone on it |
| Your preferences (sound, vibration, notices already seen) | Remembering what you chose |

**We do not ask for and do not store:** your name, e-mail, phone number, national ID, address,
date of birth, contacts, photos, location, or any advertising identifier.

**We do not store health values.** Lembrô records that the task **happened**, never its result:
there is no field for blood pressure, blood sugar, weight or any measurement. That is a product
decision, not a temporary limitation.

## Sensitive health data

The information that you take a particular medicine, and at which times, is **sensitive personal
data** under article 5, II of the LGPD. That is why the app was built so this data **does not
circulate**:

- It is not transmitted to us or to third parties.
- It is not used for advertising, profiling or any commercial purpose. The LGPD expressly
  forbids the economic use of sensitive health data (art. 11, §4), and we have no interest in it
  either: that is not how this app sustains itself.
- It is not shared with pharmacies, health plans, laboratories or advertisers.

**We do not access this data.** It is worth being precise here, because it is easy to write
something that sounds good and says little: article 5, X of the LGPD defines "processing"
broadly, and the list includes *storage*. Storage does happen — **on your device**. What does
not happen is access by us: we receive no copy, and we have no way to read, export or delete the
contents of your reminders. What to record and what to delete is decided by you, on the device.

This is not a drafting detail: it is what makes the three situations below — the only ones in
which anything leaves the device — **triggered by you**, and not by us.

## The three times something leaves the device — and you decide all three

### 1. Saving a backup

In Settings, "Save a backup" builds a file with your reminders and your history and opens your
system's own share sheet, so that **you** choose where it goes (Google Drive, e-mail, WhatsApp,
another app).

- We do not receive that file and we do not know where it went.
- From the moment you send it, it is governed by the policy of the service you chose.
- The file **is not encrypted**, so that you yourself can open it and so that it stays
  restorable in the future. Keep it somewhere you trust.

### 2. Sending a summary

On the Tracking screen, "Send summary" builds a **text** with what happened and opens the same
system sheet. You choose whether to send it, and to whom. We do not see the content or the
recipient.

### 3. Being followed by a carer — optional, and the only one that uses the cloud

A son, daughter, relative or carer can, **with your explicit authorisation**, follow from afar
whether your times were recorded. It is the only feature in the app that sends anything over the
internet, and it **starts switched off**: it only comes into being after you tap "Authorise" on
your own screen, seeing the name of whoever asked.

**What travels — and nothing beyond this:**

| Data | Example |
|---|---|
| Reminder name | "Losartan" |
| Scheduled time | 08:00 |
| Time recorded, or the absence of it | recorded at 08:12 / not recorded |
| How it was recorded | by the tag or by the button |
| The day this refers to | 2026-08-01 |

**What never travels:** the detail and notes field (where dosage is written), the names of your
tags, your settings, your location — which the app does not even collect — and any history from
before the authorisation.

**Where this lives:** in a **Google Firebase (Firestore)** database, contracted by us as
processor, on a server located in **São Paulo, Brazil** (region `southamerica-east1`). Device
identity is **anonymous**: a random code created by Firebase, with no name, e-mail or phone
number — there still is no account. The processing carried out by Google as processor is governed
by its own policy: https://firebase.google.com/support/privacy

**Who reads it:** only the devices **you** authorised, one by one, through the pairing code. The
authorisation is checked by the server on every read — it is not a promise made by the app, it
is a rule of the database. Whoever follows you **sees and does not touch**: they cannot record
on your behalf, and they cannot edit anything.

**You know about it:** while someone is following you, the home screen shows a permanent badge
with that person's name. There is no invisible mode.

**A signal that the app was opened also travels.** Alongside each day sent, the time of the
upload travels too, and the upload happens when you open Lembrô — not only when you record
something. This exists for a specific reason: without it, a day with no records looked identical
to a day when the phone stayed in a drawer, and whoever follows you had no way of telling
forgetfulness from a device that was switched off. With the signal, their panel can say "Lembrô
was not opened on this day" instead of implying nothing was taken.

What that means in terms of data: whoever follows you becomes able to estimate **when you last
used the app**. It is not location, it is not phone use in general, it is no screen other than
Lembrô — it is the time of the last upload, and nothing else. If you would rather not send that,
the way out is the same as for everything here: remove the carer.

**Whoever follows you can forward what they see.** Their app has a button to send the day as
text — to a sibling, to a doctor. The text goes out identified as sent by the person following
you, and carries the same content as the panel: names, times and whether it was recorded. **It
does not carry the dosage or your notes**, which never leave your device. Even so, it is worth
knowing: authorising someone to see is authorising someone who can tell others, exactly as would
happen if that person took a photo of the screen.

**To switch it off:** Settings → Who follows me → Remove. **One tap**, with no cascade of
confirmations. Access is cut immediately, the uploads stop. And the app **deletes from the cloud
everything it had already sent** — withdrawing consent leaves no trail behind.

**Retention:** each day sent is **deleted after 90 days**. It is the app itself that deletes it,
the first time it opens with an internet connection after expiry — there is no server of ours
running on its own. An honest consequence: if the app is uninstalled without you using Remove,
what has already been uploaded may stay there; in that case, write to the contact at the top and
we will delete it. Your full history goes on living only on your device.

**Legal basis:** your **consent** (LGPD, art. 11, I — sensitive data), collected specifically
and prominently on the authorisation screen. Revoking it is the Remove button.

## Notifications

Notifications are generated **inside your phone**, by the app itself, and scheduled with the
operating system. There is no notification server, there is no *push*, and no information about
your reminders travels over the internet for a notification to arrive.

The app asks for notification permission the first time it opens. If you decline, Lembrô keeps
working — it simply does not notify you.

## NFC tags

The NFC sticker holds **only an address with a random identifier** created by the app (for
example, `lembro://t/tag_a1b2c3`). It **does not contain** the name of the medicine, or any data
of yours.

That is deliberate: an NFC tag can be read by any phone. Since the identifier only means
anything inside your app, someone tapping another phone on your sticker learns nothing about
you.

The NFC permission on Android is granted at installation and is used only to read and write your
tags. We do not use NFC for payments or to identify you.

## Permissions and what they are for

| Permission | What for |
|---|---|
| NFC | Reading and writing your tags |
| Notifications | Notifying you at the reminder's time |
| Alarms during battery saving | Getting the notification through even with the phone idle |
| In-app billing | Buying full Lembrô through the store |

We do not ask for location, camera, microphone, contacts, external storage or phone.

## Purchases

Lembrô is free and functional. There is an optional paid full version, and a separate
subscription for someone who follows another person.

**Payment is processed by the app store** (Google Play or the App Store), which is the legal
seller. Lembrô **does not see, does not receive and does not store** payment data: no card, no
tax ID, no billing address. The app only asks the store whether a valid purchase is associated
with your account, and gets "yes" or "no" back.

The processing of your payment data is governed by the store's privacy policy:

- Google Play: https://policies.google.com/privacy
- App Store: https://www.apple.com/legal/privacy/

## Usage analytics, tracking and advertising

**None of these exist in Lembrô.** We use no analytics tools, no crash reporting, no trackers,
no advertising identifiers, no *pixels* and no third-party SDKs for those purposes. We do not
know how many times you opened the app, or which reminders you have.

**One honest caveat about billing.** In order to sell the full version, the app includes Google
Play's own billing library. It belongs to Google, and it carries out its own diagnostics with
Google's servers about how the purchase is working — something that happens in every app that
sells through the store, and that does not pass through us: we do not receive it, we do not see
it, and we cannot access it. Nothing from your reminders or records is sent along that path. What
Google does with that data is governed by its privacy policy, linked above.

**And about Firebase.** The Firebase library, used by the carer feature, is present in the app —
but it only talks to the internet when a pairing of yours exists. We did not include Firebase
Analytics or Crashlytics: of Firebase, we use exactly two services, the mirror database
(Firestore) and the anonymous identity (Authentication), both described in the carer section.

As a consequence, we also **cannot** recover your data if you lose your phone without having
saved a backup — and that is why the backup exists.

## Children and teenagers

Lembrô is not directed at anyone under 13, and it collects no data from anyone, of any age. If a
carer uses the app to organise a child's routine, the data stays on the carer's device, under
their control.

## Your rights (LGPD, article 18)

Since all the data is on your device and under your control, you exercise your rights directly,
without depending on us and with no waiting period:

| Right | How to exercise it |
|---|---|
| **Access** the data | It is visible in the app; "Save a backup" exports everything into a readable file |
| **Correct** it | Edit the reminder, or correct/delete a record in the history |
| **Portability** | The backup file is open JSON, not a closed format |
| **Erasure** | Delete the reminder, or uninstall the app — uninstalling removes the whole database |
| **Erase the carer mirror** | Settings → Who follows me → **Remove**: cuts access and deletes from the cloud everything already sent, in the same tap |
| **Withdraw consent** | For the carer feature: the Remove button. For everything else: uninstall — there is nothing of ours left to withdraw |

If you would still like to talk to us about privacy, use the contact at the top.

## Retention and erasure

The data stays on your device for as long as you want. **Uninstalling the app deletes the
database.** There is no copy of ours, so nothing survives uninstalling — except the backup files
you yourself have kept somewhere else and, if you use the carer feature, the days already sent to
the mirror. **If you use the carer feature and are about to uninstall, use Remove first**: that
is what deletes the mirror in the cloud. Uninstalling without it leaves what has already been
uploaded there, and erasure then depends on a request through the contact at the top.

## Security

The data lives in the app's private area, protected by the operating system: other apps cannot
read it. Apart from the carer mirror — which only exists with your authorisation, travels
encrypted (TLS) and carries the minimum described above — there is no transmission over the
network, which removes the entire class of interception and server-breach risks for everything
else.

We recommend keeping your phone's lock screen active, with a passcode or biometrics — that is
what protects any app, including this one, if the device is lost.

## Incidents

The only database outside the device is the carer mirror described above — with the least data
possible, anonymous identity, and reads restricted by a server rule. Should any vulnerability be
identified in the app or in those rules, we will fix it and publish an update; if there is
relevant risk to data subjects, we will communicate through the store's channels and through
this page, as provided by article 48 of the LGPD.

## Changes to this policy

The previous version of this policy promised: if any feature began sending data off the device,
this page would be updated **before** release and the app would ask for **specific, prominent
consent** on screen. Being followed by a carer is exactly that case, and that is how it arrived:
described here before it existed in the store, off by default, and switched on only by your tap
on "Authorise".

The promise still holds for whatever comes next: a change that widens what leaves the device will
be published here first, with the date at the top changed, and never switched on silently or by
default.

## Applicable law

This policy is governed by Brazilian law, in particular Law no. 13.709/2018 (LGPD) and Law no.
8.078/1990 (Consumer Protection Code).
