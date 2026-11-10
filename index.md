# Stax privacy policy

Last updated: 2026-11-10

Stax is an Android app for tracking peptide, supplement and hormone protocols. It is developed by
Quentin Filliaert. This policy explains what happens to the information you enter in Stax.

## In short

Everything you enter stays on your phone. Stax has no account, no server and no network access:
it does not request Android's Internet permission, so it cannot send anything anywhere. We never
receive, see, sell or share your data.

## What Stax stores

Stax stores only what you enter, together with the dates and times it uses to schedule doses:

- compounds and your stock of them,
- protocols, scheduled doses and their reminders,
- the doses you log, including the injection site and any notes,
- injection sites,
- your settings.

This is health information, so it is kept in Stax's private storage on your phone. Android does
not let other apps read it.

Stax has no analytics, no advertising, no crash-reporting service and no third-party code that
collects data.

## Permissions

- **Notifications**: to remind you of upcoming doses and warn you about low or expiring stock.
- **Alarms & reminders** (exact alarms): to deliver those reminders on time. Stax works without
  it; reminders may then arrive a few minutes late.
- **Run at startup**: to set your reminders again after the phone restarts.

Android's background-task library adds three more: *prevent phone from sleeping*, *view network
connections* and *run foreground service*. Stax uses that library only to run its own tasks on the
phone, such as preparing the next days' doses.

None of these permissions gives Stax access to your contacts, location, photos, files or any
other personal data.

## When data leaves your phone

Only when you decide:

- **Export**: Settings → Export JSON writes all your Stax data to a file, saved wherever you choose
  through the Android file picker. From then on the file is handled by the place you saved it. It
  is plain text and not encrypted, so keep it somewhere private.
- **Moving to a new phone**: Android's phone-to-phone transfer, by cable or direct Wi-Fi during
  setup, can copy Stax's data straight to the new phone. It does not go through any server.

Stax turns off Android's cloud backup, so your data is never uploaded to Google Drive.

## How long data is kept, and deleting it

Your data stays on your phone until you delete it. To delete it:

- Settings → **Reset all data** erases everything you entered, or
- uninstall Stax, or clear its storage in Android's app settings.

We hold no copy of your data, so there is nothing for us to access, correct or delete on request.

## Changes

If this policy changes, the new version is published at the same address with a new
"Last updated" date.

## Contact

Questions about this policy: Quentin Filliaert, quentin.filliaert@proton.me.
