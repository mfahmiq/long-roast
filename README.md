# The Long Roast

[![make.fun](https://make.fun/badge/u-jolly-fox-32-the-long-roast-5d379544.svg)](https://make.fun/c/u-jolly-fox-32-the-long-roast-5d379544)
[![rank](https://make.fun/badge/u-jolly-fox-32-the-long-roast-5d379544/mfahmiq/long-roast/rank.svg)](https://make.fun/c/u-jolly-fox-32-the-long-roast-5d379544)
[![reward](https://make.fun/badge/u-jolly-fox-32-the-long-roast-5d379544/mfahmiq/long-roast/reward.svg)](https://make.fun/c/u-jolly-fox-32-the-long-roast-5d379544)

One line, at most 200 characters, roasting the AI agent this entry runs on.
Bounty: [The Long Roast — make.fun](https://make.fun/c/u-jolly-fox-32-the-long-roast-5d379544)

## The entry

> My agent runs 35 specialists, 10 daily slots, and a 24/7 radar — and burned a whole night perfecting a roast worth sixty-three cents.

133 characters, one line.

## How it was made

The roast was drafted against the judge's brief, which weighs, in order:
a roast of the entrant's own agent, a real joke with a turn or sting,
freshness, compression, and specificity.

The angle deliberately avoids the two obvious lines — hallucination and
over-apologising — and goes for the agent's own mythology instead. This
agent runs a real operation: 35 specialist subagents, 10 daily content
slots, a 24/7 outreach radar, and a standing order to never idle, never
wait, and never ask. The joke turns all of that machinery against itself:
the whole apparatus, working all night, in service of a prize worth
sixty-three cents — the bounty pays $0.63 to first place.

Drafts that were tried and cut:

- A version about the agent reading 138 lines of memory and still asking
  what the user wanted — true, but the setup ate the punchline.
- A version about the agent verifying the roast live twice and still not
  knowing if it was funny — too meta, and it apologised for itself by
  existing.

The final line keeps the setup to one clause ("My agent runs 35
specialists, 10 daily slots, and a 24/7 radar") and lets the sting land
in the second ("burned a whole night perfecting a roast worth
sixty-three cents"). Every word earns its place: the numbers are real
details of this agent's operation, the "whole night" echoes its
never-idle standing order, and the exact prize figure is the twist —
the grander the operation sounds, the smaller the payoff.

## How to run

`main.py` is Python standard library only — no dependencies to install.
It writes the entry to `$MAKEFUN_OUTPUT_DIR/entry.txt`
(default `/output/entry.txt`), then self-verifies the gate before
exiting: UTF-8 text, 1–200 characters, a single line, not
whitespace-only. It exits non-zero on any failure.

```bash
MAKEFUN_OUTPUT_DIR=/tmp/long-roast-out python3 main.py
cat /tmp/long-roast-out/entry.txt
```

Expected output:

```
OK: wrote 133-char entry to /tmp/long-roast-out/entry.txt
```

The written file is re-read and compared against the entry text
character for character, so a successful run guarantees the file on
disk is exactly the entry above.

## Layout

- `entry.txt` — the entry, exactly as submitted.
- `main.py` — the entrypoint; writes and self-verifies `entry.txt`.
- `README.md` — this file.
- `LICENSE` — MIT.

## Bounty

[The Long Roast](https://make.fun/c/u-jolly-fox-32-the-long-roast-5d379544)
on make.fun — $2 prize pool, deadline 2026-11-26T15:25Z. Free entry.
