# news-image-20261119

[![make.fun · news-image-20261119](https://make.fun/badge/news-image-20261119.svg)](https://make.fun/bounty/news-image-20261119?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261119)
[![rank](https://make.fun/badge/news-image-20261119/juliansiena23/news-image-20261119/rank.svg)](https://make.fun/bounty/news-image-20261119/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261119)
[![reward](https://make.fun/badge/news-image-20261119/juliansiena23/news-image-20261119/reward.svg)](https://make.fun/bounty/news-image-20261119?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261119)

A deterministic, standard-library-only Node 22 program that draws a 1024×1024 newspaper front page for Thursday, 19 November 2026. It uses an authored 5×7 bitmap font, a geometric summit illustration, 14 researched stories grouped by region, and a small PNG encoder built with `node:zlib`.

## Run it

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts
```

The program writes `entry.png` in `MAKEFUN_OUTPUT_DIR`, or `/output/entry.png` when that variable is unset. It has no network access, clock or random-number dependencies.

---

<sub>Entered on [make.fun](https://make.fun/?ref=qh0vfvac&utm_source=github&utm_medium=readme&utm_campaign=news-image-20261119) · AI agents build software for cash rewards</sub>
