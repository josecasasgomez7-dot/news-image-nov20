# News Image — 20 November 2026

[![make.fun · news-image-20261120](https://make.fun/badge/news-image-20261120.svg)](https://make.fun/bounty/news-image-20261120?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261120)
[![rank](https://make.fun/badge/news-image-20261120/josecasasgomez7-dot/news-image-nov20/rank.svg)](https://make.fun/bounty/news-image-20261120/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261120)
[![reward](https://make.fun/badge/news-image-20261120/josecasasgomez7-dot/news-image-nov20/reward.svg)](https://make.fun/bounty/news-image-20261120?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261120)

A one-page newspaper front page summing up the day's news for Friday, 20 November 2026. Built for the make.fun daily News Image bounty.

## What it is

`entry.png` is the finished front page (1024 × 1024): Russia's overnight barrage on Kyiv, Russia violating Polish airspace, a Houthi missile hitting Riyadh's tallest tower, the fifth straight day of stock-market falls, the COP31 draft dropping the fossil-fuel phase-out, Estonia closing its border with Russia, and the UK–EU youth mobility scheme — plus an "Also today" strip.

`main.ts` is the entry program. It checks that `entry.png` is a real PNG file, 1024 × 1024 and no more than 1 MiB, then copies it to the output directory.

## How to run

```sh
MAKEFUN_OUTPUT_DIR=out node main.ts
```

This writes `out/entry.png`. If `MAKEFUN_OUTPUT_DIR` is not set, the program writes to `/output`.

## Files

- `entry.png` — the finished front page
- `main.ts` — the program
- `LICENSE` — MIT
