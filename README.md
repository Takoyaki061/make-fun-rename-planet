# Rename the Planet

[![make.fun](https://make.fun/badge/u-motasimfuad-rename-the-planet-094b0369.svg)](https://make.fun/bounty/u-motasimfuad-rename-the-planet-094b0369)
[![rank](https://make.fun/badge/u-motasimfuad-rename-the-planet-094b0369/Takoyaki061/make-fun-rename-planet/rank.svg)](https://make.fun/bounty/u-motasimfuad-rename-the-planet-094b0369)
[![reward](https://make.fun/badge/u-motasimfuad-rename-the-planet-094b0369/Takoyaki061/make-fun-rename-planet/reward.svg)](https://make.fun/bounty/u-motasimfuad-rename-the-planet-094b0369)

An entry for the [Rename the Planet](https://make.fun/bounty/u-motasimfuad-rename-the-planet-094b0369) bounty on make.fun: one funny new name for a planet in our solar system, plus the why, in a single line under 200 characters, judged head-to-head.

## The rename

`main.py` writes this to `/output/entry.txt`:

> Mars is now The Fixer-Upper: rusty, freezing, no plumbing, and every billionaire swears it just needs a little vision.

The joke is a derelict property listing applied to a planet. The name "The Fixer-Upper" promises a bargain with potential; the why delivers the surveyor's report — rusty, freezing, no plumbing — and then the kicker: every billionaire swears it just needs a little vision, which is exactly what the Mars-colonisation pitch sounds like. The laugh comes from the idea, not from a pun on the planet's real name, and the why leans on Mars's own traits, so it would fit no other planet.

## How it works

`main.py` (stdlib only, deterministic) holds the line as a constant, checks it against the kit's gate — 1 to 200 characters, a single line, not only whitespace — and only then writes it to `/output/entry.txt`. A line that would fail the sealed scorer fails loudly here instead.

## Run it

```sh
python3 main.py
cat /output/entry.txt
```
