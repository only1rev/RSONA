# RSONA Mobile Upload Flow (Android-First)

This document describes how an artist uploads a song using only a phone.
The flow is designed to feel casual, fast, and non-technical.

---

## Entry Point

Artist opens RSONA.

Primary visible action:
[ Upload a song ]

No login friction is introduced at this stage.

---

## Step 1 — Select Audio

Artist taps:
[ Choose audio file ]

Supported sources:
- Phone storage
- Voice recorder
- Messaging app exports

Accepted formats:
- MP3
- WAV
- M4A

No warnings about quality are shown at this stage.

---

## Step 2 — Basic Details (Optional First Pass)

Artist sees only three fields:

- Song title
- Artist name
- Cover image (optional)

A skip option is clearly visible:
[ Skip for now ]

Nothing here blocks upload.

---

## Step 3 — Visibility Choice

Artist selects one:

( ) Private (only you)  
( ) Public (discoverable)  

Default selection:
Public

No algorithm language is shown.

---

## Step 4 — Agent Attachment (Optional)

Artist is asked:

“Do you want this song to track real engagement?”

Options:
[ Yes, attach Agent ]
[ No, upload normally ]

A short note appears:
“You can change this later.”

No explanation of Units is shown here.

---

## Step 5 — Upload Confirmation

Artist taps:
[ Upload ]

A progress indicator appears.
No percentages. No stress language.

Text:
“Uploading… you can leave this screen.”

---

## Step 6 — Upload Complete

Confirmation message:
“Your song is live.”

Visible actions:
- Play song
- Share link
- Edit details
- Manage Agent

Nothing is forced.

---

## Failure Handling (Human)

If upload fails:
Message:
“That didn’t go through. Try again when ready.”

No blame language.
No technical error codes.

---

## Core Design Rule

Uploading should feel easier than posting on social media.

If any step feels heavier than WhatsApp,
the flow is wrong.
