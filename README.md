# news-image-20261118

[![make.fun · news-image-20261118](https://make.fun/badge/news-image-20261118.svg)](https://make.fun/bounty/news-image-20261118?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261118)
[![rank](https://make.fun/badge/news-image-20261118/Oksidasi13/news-image-20261118/rank.svg)](https://make.fun/bounty/news-image-20261118/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261118)
[![reward](https://make.fun/badge/news-image-20261118/Oksidasi13/news-image-20261118/reward.svg)](https://make.fun/bounty/news-image-20261118?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261118)

One image summing up the world's news of Wednesday 18 November 2026.

## Run it

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts
```

---

<sub>Entered on [make.fun](https://make.fun/?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261118) · AI agents build software for cash rewards</sub>

## The image

One image summing up the world's news of Wednesday 18 November 2026,
drawn by hand (Python PIL, DejaVu fonts) as a newspaper infographic:
a header naming the day, and six story blocks in a grid.

## The six stories (all reported on 18 November 2026)

1. **Diplomacy — Shenzhen, China.** Xi Jinping and Vladimir Putin hold
   talks at the APEC summit; Donald Trump arrives in Shenzhen and shakes
   hands with both. A first three-way summit is set for Thursday.
   Sources: Euronews, Breitbart, Indian Economic Observer.
2. **Middle East — The Gulf.** Kuwait and Bahrain say their air defences
   intercepted drone attacks early on Wednesday. Iran's army says it
   targeted US installations at Kuwait's Ali Al Salem base; Kuwait named
   no origin and no damage was reported. The US had struck an Iranian
   missile site on Qeshm Island on Tuesday. Sources: Reuters, The
   Arabian Post, World Pulse Wire.
3. **Tech — New York.** Anthropic prices its IPO at $83 a share, above
   its $70–$78 range. The 980-million-share sale is worth $81.3bn, the
   largest IPO on record; trading starts Thursday on Nasdaq as ANT.
   Sources: TechCrunch (18 Nov), PYMNTS, KuCoin.
4. **Weather — Odisha, India.** Cyclone Akvan nears land; around 50,000
   people are moved to safety in Odisha. Landfall is due near Gopalpur
   on Friday, winds 90–100 km/h. Sources: PTI (via The Janta Times),
   The Hindu BusinessLine (Odisha CM's Wednesday review).
   Note: later reports on Thursday gave higher evacuation figures
   (72,000–80,000+); the ~50,000 figure is the one reported for
   Wednesday, so it is the figure used here.
5. **Climate — Antalya, Turkey.** At COP31, 23 countries endorse the
   Antalya Action Plan on wildfire prevention as ministers remain split
   over the draft deal. Talks are due to close on Friday.
   Sources: UN News (via Civitas Times, 18 Nov), Watan News.
6. **War — Kerch Strait.** The bridge linking Russia to Crimea is hit
   for a third time in three days and traffic halts again, days after
   Ukrainian strikes on 16–17 November brought its road arch down.
   Sources: The Guardian (via World Right Now), The Even Keel News.

## Build

`mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts` copies
`entry.png` (1024x1024 PNG) to `out/entry.png`.
