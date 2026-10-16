# Privacy policy

Last updated: 16 October 2026

"Where the Party People at?" (the app) is a personal events finder used only by the person who built it (the owner). It is not offered to the public. This policy explains what the app does with data from the owner's Google account.

## Data the app accesses

The app signs in to a single Google account that the owner set up for event mail, with the owner's consent, and uses these Google permissions:

- **Gmail, read only** (`https://www.googleapis.com/auth/gmail.readonly`): the app reads emails in that mailbox from the last 120 days. It looks for event listings in newsletters and alerts, and for ticket confirmations. From these it takes event details: title, date and time, venue, price and link. Emails from senders the owner has marked to ignore are not read for events.
- **Gmail, send** (`https://www.googleapis.com/auth/gmail.send`): the app sends the owner an email when an event source fails. It sends nothing else and writes to no one else.
- **Calendar free/busy** (`https://www.googleapis.com/auth/calendar.freebusy`): the app reads busy and free times from calendars the owner has shared with the events account, to show which events clash. It cannot see event titles, attendees or other details.

## How the data is stored

Everything the app keeps is stored on the owner's own server, which is not reachable from the public internet:

- the event details taken from emails;
- a copy of each email it has read, for up to 130 days, so it does not download the same email twice;
- a short log of which emails were read and how many events each gave;
- the newest email from each sender that gave no events, so a reader can be written for it;
- the Google sign-in token, in a file only the app can read.

Nothing is stored with any third party.

## Sharing

The app does not sell, share, transfer or disclose Google user data to anyone. It sends no data to advertising, analytics or AI services. Google user data is not used to train any model.

The app's use and transfer of information received from Google APIs adheres to the [Google API Services User Data Policy](https://developers.google.com/terms/api-services-user-data-policy), including the Limited Use requirements.

## Keeping and deleting data

Copies of emails are deleted after 130 days. Event details are replaced each day by that day's run. The owner can remove all stored data at any time by deleting the app's data folder, and can revoke the app's access to the Google account at any time at [myaccount.google.com/permissions](https://myaccount.google.com/permissions).

## Children

The app is not directed at children and has no users other than its owner.

## Changes

If this policy changes, the new version will be published here with a new date.

## Contact

Open an issue on [this repository](https://github.com/stephen7898-star/wherethepartyatpub/issues).
