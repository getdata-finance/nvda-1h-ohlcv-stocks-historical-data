# NVDA 1h OHLCV US stocks Historical Data — Free Sample

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Dataset rows](https://img.shields.io/badge/full_dataset-10_763_rows-blue)](https://getdata.finance/datasets/nvda) [![Updated](https://img.shields.io/badge/weekly_update-every_Saturday_8am_UTC-green)](https://getdata.finance) [![Full data on getdata.finance](https://img.shields.io/badge/download-getdata.finance-orange)](https://getdata.finance/datasets/nvda)

### -> [**Download the full NVDA dataset on getdata.finance**](https://getdata.finance/datasets/nvda)

**NVDA 1h OHLCV stocks historical data** — ultra high-quality 1h OHLCV for **NVIDIA**. Clean `datetime, open, high, low, close, volume` CSV for backtesting, algorithmic trading and quantitative research.

## Table of contents

- [Why this dataset?](#why-this-dataset)
- [Download sample CSV](#download-sample)
- [GitHub Pages preview](#github-pages)
- [Sample vs full dataset](#sample-vs-full-dataset)
- [Timeframes on GetData](#timeframes-on-getdata)
- [Weekly updates](#weekly-updates)
- [Data preview](#data-preview)
- [Schema](#schema)
- [Code examples](#code-examples)
- [Download full data on getdata.finance](#download-full-data-on-getdata)

## Why this dataset?

- **Ultra high-quality 1h OHLCV** for **NVIDIA** (US stocks)
- **Clean CSV schema** — `datetime, open, high, low, close, volume` (no gaps in formatting)
- **Free evaluation sample** on GitHub (`1h`) · **11 timeframes** on [getdata.finance](https://getdata.finance/datasets/nvda) · **10,763** `1h` rows in the full archive
- Built for **backtesting**, **algorithmic trading** and **quantitative finance** workflows
- **Weekly refresh** — [getdata.finance](https://getdata.finance) every **Saturday, 8am UTC+0**; GitHub `1h` sample updated in sync

> **Sample on GitHub** · `NVDA_1h.csv` (995 rows, `2026-02-06` -> `2026-09-01`, 100.59 KB). **Full archive on [getdata.finance](https://getdata.finance/datasets/nvda)** — **10,763** `1h` rows (full `1m`: 599,253), **11 timeframes**, `2020-07-14` -> `2026-09-01`.

## Download sample

**[NVDA_1h.csv](https://github.com/getdata-finance/nvda-1h-ohlcv-stocks-historical-data/blob/main/NVDA_1h.csv)** on GitHub ([raw CSV](https://raw.githubusercontent.com/getdata-finance/nvda-1h-ohlcv-stocks-historical-data/main/NVDA_1h.csv)) · [GitHub Releases](https://github.com/getdata-finance/nvda-1h-ohlcv-stocks-historical-data/releases)

## GitHub Pages

Interactive chart & stats: **[https://getdata-finance.github.io/nvda-1h-ohlcv-stocks-historical-data/](https://getdata-finance.github.io/nvda-1h-ohlcv-stocks-historical-data/)**

Full archive & live chart on getdata.finance: **[https://getdata.finance/datasets/nvda](https://getdata.finance/datasets/nvda)**

## Sample vs full dataset

| | **Sample (this repo)** | **Full dataset ([getdata.finance](https://getdata.finance/datasets/nvda))** |
|---|--:|---|
| Instrument | NVIDIA · US stocks | NVIDIA · US stocks |
| Timeframes | `1h` (sample) | **11** — 1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W |
| 1h rows | 995 | **10,763** |
| Size | 100.59 KB | full ZIP on [getdata.finance](https://getdata.finance/datasets/nvda) |
| Period | `2026-02-06` -> `2026-09-01` | `2020-07-14` -> `2026-09-01` |
| File | `NVDA_1h.csv` | ZIP on [getdata.finance](https://getdata.finance/datasets/nvda) |
| Coverage report | — | [NVDA coverage](https://getdata.finance/coverage/nvda) |
| Updates | Weekly (Saturday, 8am UTC+0) — GitHub sample | Weekly (Saturday, 8am UTC+0) — all timeframes |

## Timeframes on GetData

This GitHub repository ships a **`1h` evaluation sample** only. On **[getdata.finance](https://getdata.finance/datasets/nvda)**, each full asset archive is delivered as a ZIP with **11 gap-free OHLCV timeframes** (one CSV per timeframe):

**1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W**

GitHub = `1h` sample · [getdata.finance](https://getdata.finance/datasets/nvda) = all **11** timeframes above for the same instrument.

## Weekly updates

- **[getdata.finance](https://getdata.finance)** — Full datasets are updated every Saturday, 8am UTC+0.
- **GitHub (this repo)** — GitHub samples are refreshed weekly (every Saturday, 8am UTC+0), in sync with getdata.finance.

When a new `1h` sample is published on GitHub, the README, chart preview and CSV reflect the latest week of data.

## Data preview

First and latest rows from the GitHub sample **`NVDA_1h.csv`**:

**First rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-02-06T20:00:00+00:00 | 182.68 | 184.65 | 182.37 | 183 | 16084 |
| 2026-02-09T14:00:00+00:00 | 183 | 191.36 | 181.69 | 188.84 | 32086 |
| 2026-02-09T15:00:00+00:00 | 188.84 | 190.13 | 188.28 | 189.66 | 38536 |
| 2026-02-09T16:00:00+00:00 | 189.66 | 189.86 | 189.1 | 189.19 | 21301 |
| 2026-02-09T17:00:00+00:00 | 189.19 | 190.23 | 189 | 189.13 | 16029 |

**Last rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-09-01T15:00:00+00:00 | 214.49 | 216.85 | 214.14 | 216.7 | 13781 |
| 2026-09-01T16:00:00+00:00 | 216.7 | 216.74 | 215.39 | 216.1 | 13419 |
| 2026-09-01T17:00:00+00:00 | 216.1 | 216.13 | 214.24 | 214.47 | 11102 |
| 2026-09-01T18:00:00+00:00 | 214.47 | 214.62 | 212.79 | 213.76 | 12126 |
| 2026-09-01T19:00:00+00:00 | 213.76 | 214.36 | 213.1 | 213.99 | 14467 |

## Schema

| Column | Description |
| --- | --- |
| `datetime` | Bar open timestamp (UTC, ISO-8601). |
| `open` | Opening price of the candlestick bar. |
| `high` | Highest price during the bar. |
| `low` | Lowest price during the bar. |
| `close` | Closing price of the candlestick bar. |
| `volume` | Tick volume (number of price updates) during the bar. |

```text
datetime,open,high,low,close,volume
```

## Code examples

### pandas

```python
import pandas as pd

df = pd.read_csv('NVDA_1h.csv', parse_dates=['datetime'])
df.set_index('datetime', inplace=True)
print(df.describe())
```

### backtrader

```python
import backtrader as bt
import pandas as pd

df = pd.read_csv('NVDA_1h.csv', parse_dates=['datetime'])
df.set_index('datetime', inplace=True)

class PandasData(bt.feeds.PandasData):
    params = (('datetime', None), ('open', 'open'), ('high', 'high'),
              ('low', 'low'), ('close', 'close'), ('volume', 'volume'))

cerebro = bt.Cerebro()
cerebro.adddata(PandasData(dataname=df))
# cerebro.addstrategy(YourStrategy)
# cerebro.run()
```

### vectorbt

```python
import pandas as pd
import vectorbt as vbt

df = pd.read_csv('NVDA_1h.csv', parse_dates=['datetime'])
close = df.set_index('datetime')['close']
fast, slow = vbt.MA.run(close, 10), vbt.MA.run(close, 50)
entries = fast.ma_crossed_above(slow)
exits = fast.ma_crossed_below(slow)
pf = vbt.Portfolio.from_signals(close, entries, exits, init_cash=10_000, freq='1h')
print(pf.stats())
```

## Download full data

The complete **NVDA** archive on **[getdata.finance](https://getdata.finance/datasets/nvda)** includes **11 OHLCV timeframes** (1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W) — **10,763** rows at `1h`, plus all other timeframes in the same ZIP.

**[-> Get the full NVDA dataset on getdata.finance](https://getdata.finance/datasets/nvda)**

---
*GetData · NVDA 1h OHLCV sample on GitHub · Full historical data on [getdata.finance](https://getdata.finance/datasets/nvda)*
