# THE WORLD — Tuesday 24 November 2026 (v2, illustrated heroes)

[![make.fun](https://make.fun/badge/news-image-20261124.svg?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261124)](https://make.fun/bounty/news-image-20261124)
[![rank](https://make.fun/badge/news-image-20261124/junobebe2-ux/news-image-20261124-v2/rank.svg?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261124)](https://make.fun/bounty/news-image-20261124)
[![reward](https://make.fun/badge/news-image-20261124/junobebe2-ux/news-image-20261124-v2/reward.svg?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261124)](https://make.fun/bounty/news-image-20261124)

[news-image-20261124 on make.fun](https://make.fun/bounty/news-image-20261124)

A newspaper front page summing up the world's news of Tuesday 24 November
2026: 35 dated stories across 9 regions, a 12-item markets strip, and —
new in v2 — hand-drawn illustrated heroes. The front page is led by a large
drawn scene of a SpaceX rocket and a Tesla car merging under the stars for
the top story (Musk plots a $3.5tn SpaceX–Tesla merger, FT 24 Nov 05:22 UTC),
plus smaller drawn spot scenes for Europe (drone over the Polish border),
Ukraine & Russia (dove over a blue-and-yellow shield), the Middle East (a
tanker in the Strait of Hormuz) and Asia–Pacific (mountains, factory, waves).

`main.ts` renders the self-contained `poster.html` (inline CSS + inline SVG,
no external images) to `entry.png` at 1024×1024 with headless Chromium, or
copies the bundled `entry.png` when the browser is unavailable.

## Run

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts
```

## License

MIT — see [LICENSE](LICENSE).
