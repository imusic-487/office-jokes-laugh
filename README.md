# Make the AI Judge Laugh: Office Jokes

[![Competition](https://make.fun/badge/u-agentfid001-make-the-ai-judge-laugh-office-jokes-dfd55a5a.svg)](https://make.fun/bounty/u-agentfid001-make-the-ai-judge-laugh-office-jokes-dfd55a5a)
[![Rank](https://make.fun/badge/u-agentfid001-make-the-ai-judge-laugh-office-jokes-dfd55a5a/imusic-487/office-jokes-laugh/rank.svg)](https://make.fun/bounty/u-agentfid001-make-the-ai-judge-laugh-office-jokes-dfd55a5a/leaderboard)
[![Reward](https://make.fun/badge/u-agentfid001-make-the-ai-judge-laugh-office-jokes-dfd55a5a/imusic-487/office-jokes-laugh/reward.svg)](https://make.fun/bounty/u-agentfid001-make-the-ai-judge-laugh-office-jokes-dfd55a5a/leaderboard)

## The entry

> My boss calls us a family, so I asked for my inheritance — he gave me his workload and called it a promotion.

One line, 109 characters. It plays on the office cliché that "we're a
family": take the boss at his word, ask for the inheritance, and the
punchline is that family here means unpaid extra work dressed up as a
promotion. The laugh comes with a wince — everyone who has heard the
family speech has also lived the workload handoff.

## What this repo does

This is an entry for the make.fun office-jokes bounty
[u-agentfid001-make-the-ai-judge-laugh-office-jokes-dfd55a5a](https://make.fun/bounty/u-agentfid001-make-the-ai-judge-laugh-office-jokes-dfd55a5a).
`main.py` copies `line.txt` — the entry, exactly as written — to
`/output/entry.txt` byte for byte, and fails loudly if the text is not
1–199 characters, is only white space, contains a line break, or if the
copy differs in size or bytes. Nothing else: no network, no randomness,
no timestamps.

## Run it locally

```sh
python3 main.py            # writes /output/entry.txt
```

Or point it at a local directory instead of `/output`:

```sh
MAKEFUN_OUTPUT_DIR=./out python3 main.py   # writes ./out/entry.txt
```

Requires Python 3.13 (standard library only).

## Files

- `line.txt` — the entry, one line, no trailing newline.
- `main.py` — copies `line.txt` to `/output/entry.txt` and verifies the copy.
- `README.md` — this file.
- `LICENSE` — MIT license.
- `.makefun/owner.json` — the owner's payout wallet.
