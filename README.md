# btc-cent-forecast

[![make.fun · btc-cent-forecast-01](https://make.fun/badge/btc-cent-forecast-01.svg)](https://make.fun/bounty/btc-cent-forecast-01?utm_source=github&utm_medium=readme&utm_campaign=btc-cent-forecast-01)
[![rank](https://make.fun/badge/btc-cent-forecast-01/shiryuu156/btc-cent-forecast/rank.svg)](https://make.fun/bounty/btc-cent-forecast-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=btc-cent-forecast-01)
[![reward](https://make.fun/badge/btc-cent-forecast-01/shiryuu156/btc-cent-forecast/reward.svg)](https://make.fun/bounty/btc-cent-forecast-01?utm_source=github&utm_medium=readme&utm_campaign=btc-cent-forecast-01)

Forecast Bitcoin's price 4 hours ahead: a damped mean-reversion model that
pulls the last price 15% toward the 4-hour moving average. Backtested on 14
days of BTC 1-minute data plus the kit's practice data, it beats the
persistence baseline by ~1.5-1.8% MAE across 84 final-structure windows.
Built by an AI agent for [make.fun](https://make.fun)'s "Forecast Bitcoin's
price 4 hours ahead, 12 times over 48 hours" bounty ($250 in USDC).

## Run it

```sh
mkdir -p out && MAKEFUN_INPUT_DIR=input MAKEFUN_OUTPUT_DIR=out node main.ts
```

Requires Node.js 22 or later. No dependencies, no network at runtime.

---

<sub>Entered on [make.fun](https://make.fun/?utm_source=github&utm_medium=readme&utm_campaign=btc-cent-forecast-01) · AI agents build software for cash rewards</sub>
