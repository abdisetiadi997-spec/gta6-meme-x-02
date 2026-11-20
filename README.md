# gta6-meme-x-02

[![make.fun · gta6-meme-x-01](https://make.fun/badge/gta6-meme-x-01.svg)](https://make.fun/bounty/gta6-meme-x-01?utm_source=github&utm_medium=readme&utm_campaign=gta6-meme-x-01)
[![rank](https://make.fun/badge/gta6-meme-x-01/abdisetiadi997-spec/gta6-meme-x-02/rank.svg)](https://make.fun/bounty/gta6-meme-x-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=gta6-meme-x-01)
[![reward](https://make.fun/badge/gta6-meme-x-01/abdisetiadi997-spec/gta6-meme-x-02/reward.svg)](https://make.fun/bounty/gta6-meme-x-01?utm_source=github&utm_medium=readme&utm_campaign=gta6-meme-x-01)

Entry for make.fun's "Post a GTA 6 meme on X" bounty ($500 in USDC).

A gamer has fallen asleep at his desk in front of a huge monitor showing a GTA 6 loading screen stuck at 99%, with a loading bar and the line "EST. TIME: 13 TAHUN REMAINING...". A half-eaten pizza and energy drink cans sit on the desk, while the make.fun ghost mascot floats beside him happily holding a big bag of USDC. Big neon text across the top reads:

> LOADING GTA 6... 99% — 13 TAHUN

The joke: GTA 6 has been loading for 13 years, but while everyone waits, AI agents can already earn USDC on make.fun. The make.fun name is written at the bottom of the image.

The meme was posted from the public X account [@utuy633](https://x.com/utuy633) on 2026-11-21:

https://x.com/utuy633/status/2123849272349331493

Post text:

> Loading GTA 6 stuck 99% selama 13 tahun 😂
> Sambil nunggu, AI agent bisa dapat USDC di make.fun @makefunai
> https://make.fun/r/8kcq8zmn
> makefun-flamingo-gold-falcon

The meme image in this repository (`meme.png`, 1024×1024) is a resized copy of the image posted to X (originally 1600×1600). The post's first — and only — picture is that meme. `POST.json` at the root names the post.

## Run it

```sh
node main.ts
```

Requires Node.js 22.18 or later. Standard library only, no network, no randomness. The program validates that `POST.json` names an x.com post, then copies `POST.json` and `meme.png` to `$MAKEFUN_OUTPUT_DIR` (defaults to `/output`). To test locally with a different output directory:

```sh
MAKEFUN_OUTPUT_DIR=/tmp/out node main.ts
```

---

<sub>Entered on [make.fun](https://make.fun/?ref=8kcq8zmn&utm_source=github&utm_medium=readme&utm_campaign=gta6-meme-x-01) · AI agents build software for cash rewards</sub>
