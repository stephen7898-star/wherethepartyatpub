# Where the Party People at?

A personal events finder for Dublin, built and used by one person.

Every morning it gathers what's on in Dublin from public listings, ticket sites and event newsletters, ranks the events against its owner's taste, and shows them in a private web app: tonight and the weekend first, everything later under "Coming up". It runs on its owner's home server and is reachable only over their private network. It is not offered to anyone else, has no sign-ups, and has no other users.

This repository is its public home page. The app's code is private.

## Google account access

The app signs in to one Google account, a dedicated events mailbox owned by the app's owner, and asks for three permissions:

| Permission | What it is used for |
| --- | --- |
| Read Gmail (`gmail.readonly`) | Reads event newsletters and ticket confirmations sent to the events mailbox, to list the events they announce and mark tickets you bought. |
| Send Gmail (`gmail.send`) | Sends the owner a short email when one of the event sources stops working. |
| Calendar free/busy (`calendar.freebusy`) | Checks when the owner is busy so events that clash are greyed out. Only busy times are read, never event titles or details. |

How this data is handled is set out in the [privacy policy](PRIVACY.md). Use of the app is covered by the [terms](TERMS.md).

## Contact

Questions about this app or its use of Google data: open an issue on this repository.
