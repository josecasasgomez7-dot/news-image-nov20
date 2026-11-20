# News Image — 20 November 2026

[![make.fun · news-image-20261120](https://make.fun/badge/news-image-20261120.svg)](https://make.fun/bounty/news-image-20261120?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261120)
[![rank](https://make.fun/badge/news-image-20261120/josecasasgomez7-dot/news-image-nov20/rank.svg)](https://make.fun/bounty/news-image-20261120/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261120)
[![reward](https://make.fun/badge/news-image-20261120/josecasasgomez7-dot/news-image-nov20/reward.svg)](https://make.fun/bounty/news-image-20261120?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261120)

A one-page newspaper front page that sums up Friday, 20 November 2026, built for the make.fun News Image bounty ("Sum up 20 November's world news in one image", $250 in USDC). The page is plain HTML and CSS text rendered to a 1024 × 1024 PNG — no AI-generated image text, no borrowed photos.

## What's on the page

- **Lead:** Russia's overnight missile and drone barrage on Kyiv kills eight and damages bridges across the Dnipro.
- **Poland:** three Russian objects — probably two missiles and a drone — violate Polish airspace.
- **Riyadh:** a Houthi missile hits the PIF Tower, the Saudi sovereign wealth fund's headquarters.
- **Wall Street:** stocks slide for a fifth day while Japan's Nikkei drops 4.8%.
- **Climate:** the COP31 draft in Antalya drops any call to phase out fossil fuels.
- **Estonia:** the border with Russia closes for at least six months from 1 December.
- **Brussels:** the UK and EU agree a youth mobility scheme for up to 100,000 young people a year each way.
- **Also today:** GTA 6's $2.3bn launch-day sales, Voyager 1 reaching one light-day from Earth, Bukele registering for a third term, Denmark ratifying the Greenland security deal, and the Iran war follow-up.

Sources: Reuters, BBC, AP, Dawn, NASA and the UN, as reported on 20 November 2026.

## How to run

```sh
MAKEFUN_OUTPUT_DIR=out node main.ts
```

`main.ts` (Node 22 stdlib only) first checks that `entry.png` is a real PNG, 1024 × 1024 and no more than 1 MiB, then writes a copy to the output directory. Without `MAKEFUN_OUTPUT_DIR` it writes to `/output`.

## Files

- `entry.png` — the finished front page (1024 × 1024)
- `main.ts` — the entry program
- `LICENSE` — MIT
