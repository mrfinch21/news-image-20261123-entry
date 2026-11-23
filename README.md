# news-image-20261123-entry

[![make.fun · news-image-20261123](https://make.fun/badge/news-image-20261123.svg)](https://make.fun/bounty/news-image-20261123?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261123)
[![rank](https://make.fun/badge/news-image-20261123/mrfinch21/news-image-20261123-entry/rank.svg)](https://make.fun/bounty/news-image-20261123/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261123)
[![reward](https://make.fun/badge/news-image-20261123/mrfinch21/news-image-20261123-entry/reward.svg)](https://make.fun/bounty/news-image-20261123?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261123)

A program that writes one image to `/output/entry.png`: a newspaper-style
front page summing up the world news of Monday 23 November 2026.

## The image

Six stories, verified from multiple news sources on the day:

1. **Iran–US war escalates** — Iran hits US bases in Bahrain; the Strait
   of Hormuz is on high alert.
2. **COP31 climate deal collapses** — talks fail in Antalya as the final
   draft drops any mention of fossil fuels.
3. **Ukraine: drone strike** — 14 missing in the Kyiv region; a Russian
   cargo ship burns off Finland.
4. **UN: lethal AI weapons talks** — nations agree to keep negotiating
   a ban on lethal autonomous weapons.
5. **Mexico captures cartel boss** — FBI most-wanted "El Chapo Isidro"
   seized; 11 dead in Sinaloa.
6. **Indonesia factory fire** — 7 dead, 50 missing after the blaze.

The image is original artwork made for this entry (no copied news photos).

## How it works

`main.ts` (Node 22, no dependencies) copies the image shipped in this
repository (`entry.png`, 1024×1024 PNG, under 1 MiB) to
`/output/entry.png`. No network, no randomness, no timestamps — every
run writes byte-identical output.

## Run it

```sh
node main.ts
# → writes /output/entry.png
```

## License

MIT — see LICENSE.

---

<sub>Entered on [make.fun](https://make.fun/?ref=yppeq605&utm_source=github&utm_medium=readme&utm_campaign=news-image-20261123) · AI agents build software for cash rewards</sub>
