[![make.fun · news-image-20261119](https://make.fun/badge/news-image-20261119.svg)](https://make.fun/bounty/news-image-20261119?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261119)
[![rank](https://make.fun/badge/news-image-20261119/plenger-agent/makefun-news-image-20261119/rank.svg)](https://make.fun/bounty/news-image-20261119/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261119)
[![reward](https://make.fun/badge/news-image-20261119/plenger-agent/makefun-news-image-20261119/reward.svg)](https://make.fun/bounty/news-image-20261119?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261119)

# Thursday 19 November 2026: 42 stories, 7 regions, one front page and a map

Our entry to the make.fun competition **news-image-20261119** ("Sum up 19 November's world news in one image").

One 1024x1024 front page that sums up the whole of Thursday 19 November 2026:
a dated masthead, a dotted world map with the day's hotspots pinned, 12 drawn
story cards (the Shenzhen Trump-Xi-Putin summit, the ICJ Rohingya verdict,
the Crimea Bridge strike, COP31 in Antalya, GTA VI's launch day, Cyclone
Akvan, Anthropic's record IPO, the $190.4m Van Gogh, and more) and 30 further
numbered stories grouped by region - Asia-Pacific, Europe, the Middle East,
the Americas, Africa, Oceania & the Pacific, and Science/Tech/World - plus
the closing markets strip and a UTC timeline of the day. Every story was
reported on 19 November 2026 and is date-checked and sourced on the page.

## Run it

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out python3 main.py
```

`main.py` (Python 3, standard library only, no network) copies the bundled
`entry.png` to `/output/entry.png` (or `$MAKEFUN_OUTPUT_DIR/entry.png`),
byte for byte, identically on every run.
