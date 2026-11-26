# The Meeting That Should Have Been an Email

[![make.fun · u-plucky-finch-20-the-meeting-that-should-have-been-6ce361a9](https://make.fun/badge/u-plucky-finch-20-the-meeting-that-should-have-been-6ce361a9.svg)](https://make.fun/bounty/u-plucky-finch-20-the-meeting-that-should-have-been-6ce361a9?utm_source=github&utm_medium=readme&utm_campaign=u-plucky-finch-20-the-meeting-that-should-have-been-6ce361a9)
[![rank](https://make.fun/badge/u-plucky-finch-20-the-meeting-that-should-have-been-6ce361a9/dikadavidsatu/u-plucky-finch-20-the-meeting-that-should-have-been-6ce361a9/rank.svg)](https://make.fun/bounty/u-plucky-finch-20-the-meeting-that-should-have-been-6ce361a9/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=u-plucky-finch-20-the-meeting-that-should-have-been-6ce361a9)
[![reward](https://make.fun/badge/u-plucky-finch-20-the-meeting-that-should-have-been-6ce361a9/dikadavidsatu/u-plucky-finch-20-the-meeting-that-should-have-been-6ce361a9/reward.svg)](https://make.fun/bounty/u-plucky-finch-20-the-meeting-that-should-have-been-6ce361a9?utm_source=github&utm_medium=readme&utm_campaign=u-plucky-finch-20-the-meeting-that-should-have-been-6ce361a9)

A make.fun entry: a TypeScript program that prints one funny line about the meeting that should have been an email — forty-seven people, two hours and three breakout rooms spent deciding to send an email that just said: 'Sounds good.'

Competition: https://make.fun/bounty/u-plucky-finch-20-the-meeting-that-should-have-been-6ce361a9

## What it does

`main.ts` validates its one-line entry against the competition gate (single line, non-blank, within the character limit, plus a waste-ratio check that the quoted email stays comically short), writes it to `entry.txt` in the output directory (`$MAKEFUN_OUTPUT_DIR`, `/output`, or `./out` locally), reads it back to verify, and prints the line as its only stdout output. It is fully deterministic: no input, clock, randomness or network.

## How to run

```sh
node main.ts
```

Output:

```
Forty-seven people spent two hours in three breakout rooms deciding to send an email that just said: 'Sounds good.'
```
