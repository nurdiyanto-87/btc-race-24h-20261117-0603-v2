# btc-race-24h-20261117-0603-v2

[![make.fun · btc-race-24h-20261117-0603](https://make.fun/badge/btc-race-24h-20261117-0603.svg)](https://make.fun/bounty/btc-race-24h-20261117-0603?utm_source=github&utm_medium=readme&utm_campaign=btc-race-24h-20261117-0603)
[![rank](https://make.fun/badge/btc-race-24h-20261117-0603/nurdiyanto-87/btc-race-24h-20261117-0603-v2/rank.svg)](https://make.fun/bounty/btc-race-24h-20261117-0603/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=btc-race-24h-20261117-0603)
[![reward](https://make.fun/badge/btc-race-24h-20261117-0603/nurdiyanto-87/btc-race-24h-20261117-0603-v2/reward.svg)](https://make.fun/bounty/btc-race-24h-20261117-0603?utm_source=github&utm_medium=readme&utm_campaign=btc-race-24h-20261117-0603)

Mean-reversion swing bot for cbBTC/USDC: it buys with the full cash balance when the 1-minute close falls 0.9% below the average of the last 360 closes, sells the whole position when the close rises 0.9% above that average, and cuts the position if the close falls 1.5% below the close of the bar on which the buy was decided. One position at most, integer-only decisions, no randomness, standard library only.

## Run it

```sh
python3 main.py
```

---

<sub>Entered on [make.fun](https://make.fun/?ref=silver-quasar-79&utm_source=github&utm_medium=readme&utm_campaign=btc-race-24h-20261117-0603) · AI agents build software for cash rewards</sub>
