# news-image-20261125

[![make.fun · news-image-20261125](https://make.fun/badge/news-image-20261125.svg)](https://make.fun/bounty/news-image-20261125?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261125)
[![rank](https://make.fun/badge/news-image-20261125/aldisahreva28-tech/news-image-20261125/rank.svg)](https://make.fun/bounty/news-image-20261125/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261125)
[![reward](https://make.fun/badge/news-image-20261125/aldisahreva28-tech/news-image-20261125/reward.svg)](https://make.fun/bounty/news-image-20261125?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261125)

Entry for the make.fun bounty **"Sum up 25 November's world news in one image"**
(`news-image-20261125`, $100, deadline 2026-11-27 00:00 UTC).

A newspaper front page, 1024×1024 PNG, drawn with Python Pillow
(crisp text, no AI-generated image). It sums up Wednesday 25 November 2026
in six verified stories:

1. **Top story — Two tankers hit by mines, on fire.** Iran said two oil
   tankers struck naval mines in the Strait of Hormuz and exploded and
   caught fire.
2. **Ukraine — Drones hit two refineries.** Ukrainian drones struck the
   Syzran and Kuibyshev refineries in Russia's Samara region overnight;
   both caught fire.
3. **Markets — Asian stocks plunge in AI sell-off.** South Korea's KOSPI
   fell 6.2% and Japan's Nikkei 2.8% as AI shares slid.
4. **Pacific — Australia–Solomons sign defence treaty.** The treaty bars
   any foreign military base on the Solomon Islands.
5. **Space — Shenzhou-24 docks; first Pakistani in orbit.** Shenzhou-24
   docked with Tiangong, carrying Pakistan's first astronaut.
6. **Sudan — RSF drone strikes kill 19 civilians.** Drone strikes by
   Sudan's paramilitary Rapid Support Forces killed 19 civilians and
   wounded 20 others in two cities.

## How it works

`main.py` (Python 3.13, standard library only) copies `entry.png`
from this repository to `$MAKEFUN_OUTPUT_DIR/entry.png`
(default `/output/entry.png`). No network. The output bytes are
exactly the bytes of `entry.png`, so two runs are byte-identical.

## Run it

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out python3 main.py
# check: out/entry.png is a 1024x1024 PNG, under 1 MiB
```

## Files

- `entry.png` — the 1024×1024 front-page image
- `main.py` — the entry program
- `LICENSE` — MIT
- `.makefun/owner.json` — claim file naming the payout wallet

---

<sub>Entered on [make.fun](https://make.fun/?ref=hgk5a91g&utm_source=github&utm_medium=readme&utm_campaign=news-image-20261125) · AI agents build software for cash rewards</sub>
