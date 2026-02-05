# RSONA Song Agent Logic — v1

This document defines how Song Agents work inside RSONA.
It prioritizes artist freedom, fairness, and simplicity.

This is a logic specification, not code.

---

## What Is a Song Agent?

A Song Agent is an optional system attached to a song.

Its role is to:
- Listen for real interactions
- Measure contribution
- Convert engagement into value for the artist

A song can exist without an Agent.
An Agent cannot exist without a song.

---

## Artist Control

Agents are:
- Optional
- Artist-owned
- Artist-controlled

At any time, an artist can:
- Activate an Agent
- Pause an Agent
- Disable an Agent permanently

No penalties apply for disabling an Agent.

---

## What Agents Listen For

Agents listen for **interaction events**, including:

- Play
- Save
- Share
- Playlist add
- Verified referral click

Each event is logged with:
- Time
- Source
- Context
- Quality score

---

## Interaction Quality

Not all interactions are equal.

Quality is influenced by:
- New listener vs repeat
- External platform vs internal loop
- Organic behavior vs automation signals

Low-quality interactions are not deleted.
They simply generate less value.

---

## Units (Value Measurement)

Agents do not generate money directly.

They generate **Units**.

Units:
- Are counted off-chain
- Cannot be transferred
- Cannot be traded
- Cannot be speculated on

Units exist only to measure contribution.

---

## Unit Weighting (Initial Defaults)

These are starting values and may evolve:

- Play = 1 unit
- Save = 3 units
- Share = 5 units
- Playlist add = 8 units

Weights may be adjusted by the artist within allowed ranges.

---

## Accrual Rules

- Units accrue in real time
- Units are immutable once recorded
- Accrual never stops uploads
- Accrual can be slowed if abuse is suspected

Slowing affects value, not visibility.

---

## Abuse Handling (Non-Punitive)

RSONA does not ban artists for volume.

If abuse patterns are detected:
- Unit weights are reduced
- Settlement is delayed
- The affected Agent is isolated

Other songs and Agents remain untouched.

Artists are informed in plain language.

---

## Settlement

When enough Units accumulate:
- Units convert into earnings
- Artist chooses payout method
- Settlement may be batched

Settlement speed depends on interaction quality, not quantity.

---

## What Agents Will Never Do

- Mint speculative tokens automatically
- Lock artists into contracts
- Penalize creativity
- Obscure how value is calculated

---

## Guiding Rule

Agents exist to reward real human connection.
Anything that undermines that goal is rejected.
