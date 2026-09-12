# AAPL 1m OHLCV US stocks Historical Data — Free Sample

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Dataset rows](https://img.shields.io/badge/full_dataset-1_218_462_rows-blue)](https://getdata.finance/datasets/aapl) [![Updated](https://img.shields.io/badge/weekly_update-every_Saturday_8am_UTC-green)](https://getdata.finance) [![Full data on getdata.finance](https://img.shields.io/badge/download-getdata.finance-orange)](https://getdata.finance/datasets/aapl)

### -> [**Download the full AAPL dataset on getdata.finance**](https://getdata.finance/datasets/aapl)

**AAPL 1m OHLCV stocks historical data** — ultra high-quality 1m OHLCV for **Apple**. Clean `datetime, open, high, low, close, volume` CSV for backtesting, algorithmic trading and quantitative research.

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

- **Ultra high-quality 1m OHLCV** for **Apple** (US stocks)
- **Clean CSV schema** — `datetime, open, high, low, close, volume` (no gaps in formatting)
- **Free evaluation sample** on GitHub (`1m`) · **11 timeframes** on [getdata.finance](https://getdata.finance/datasets/aapl) · **1,218,462** `1m` rows in the full archive
- Built for **backtesting**, **algorithmic trading** and **quantitative finance** workflows
- **Weekly refresh** — [getdata.finance](https://getdata.finance) every **Saturday, 8am UTC+0**; GitHub `1m` sample updated in sync

> **Sample on GitHub** · `AAPL_1m.csv` (49,528 rows, `2026-03-12` -> `2026-09-11`, 4.59 MB). **Full archive on [getdata.finance](https://getdata.finance/datasets/aapl)** — **1,218,462** `1m` rows (full `1m`: 636,557), **11 timeframes**, `2011-05-09` -> `2026-09-11`.

## Download sample

**[AAPL_1m.csv](https://github.com/getdata-finance/aapl-1m-ohlcv-stocks-historical-data/blob/main/AAPL_1m.csv)** on GitHub ([raw CSV](https://raw.githubusercontent.com/getdata-finance/aapl-1m-ohlcv-stocks-historical-data/main/AAPL_1m.csv)) · [GitHub Releases](https://github.com/getdata-finance/aapl-1m-ohlcv-stocks-historical-data/releases)

## GitHub Pages

Interactive chart & stats: **[https://getdata-finance.github.io/aapl-1m-ohlcv-stocks-historical-data/](https://getdata-finance.github.io/aapl-1m-ohlcv-stocks-historical-data/)**

Full archive & live chart on getdata.finance: **[https://getdata.finance/datasets/aapl](https://getdata.finance/datasets/aapl)**

## Sample vs full dataset

| | **Sample (this repo)** | **Full dataset ([getdata.finance](https://getdata.finance/datasets/aapl))** |
|---|--:|---|
| Instrument | Apple · US stocks | Apple · US stocks |
| Timeframes | `1m` (sample) | **11** — 1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W |
| 1m rows | 49,528 | **1,218,462** |
| Size | 4.59 MB | full ZIP on [getdata.finance](https://getdata.finance/datasets/aapl) |
| Period | `2026-03-12` -> `2026-09-11` | `2011-05-09` -> `2026-09-11` |
| File | `AAPL_1m.csv` | ZIP on [getdata.finance](https://getdata.finance/datasets/aapl) |
| Coverage report | — | [AAPL coverage](https://getdata.finance/coverage/aapl) |
| Updates | Weekly (Saturday, 8am UTC+0) — GitHub sample | Weekly (Saturday, 8am UTC+0) — all timeframes |

## Timeframes on GetData

This GitHub repository ships a **`1m` evaluation sample** only. On **[getdata.finance](https://getdata.finance/datasets/aapl)**, each full asset archive is delivered as a ZIP with **11 gap-free OHLCV timeframes** (one CSV per timeframe):

**1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W**

GitHub = `1m` sample · [getdata.finance](https://getdata.finance/datasets/aapl) = all **11** timeframes above for the same instrument.

## Weekly updates

- **[getdata.finance](https://getdata.finance)** — Full datasets are updated every Saturday, 8am UTC+0.
- **GitHub (this repo)** — GitHub samples are refreshed weekly (every Saturday, 8am UTC+0), in sync with getdata.finance.

When a new `1m` sample is published on GitHub, the README, chart preview and CSV reflect the latest week of data.

## Data preview

First and latest rows from the GitHub sample **`AAPL_1m.csv`**:

**First rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-03-12T13:30:00+00:00 | 260.51 | 260.51 | 257.04 | 257.37 | 149 |
| 2026-03-12T13:31:00+00:00 | 257.37 | 257.78 | 257.16 | 257.57 | 248 |
| 2026-03-12T13:32:00+00:00 | 257.57 | 257.8 | 257.37 | 257.67 | 192 |
| 2026-03-12T13:33:00+00:00 | 257.67 | 257.91 | 257.43 | 257.51 | 268 |
| 2026-03-12T13:34:00+00:00 | 257.51 | 257.99 | 257.47 | 257.76 | 206 |

**Last rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-09-11T19:55:00+00:00 | 332.26 | 332.77 | 332.26 | 332.65 | 168 |
| 2026-09-11T19:56:00+00:00 | 332.65 | 332.7 | 332.36 | 332.36 | 157 |
| 2026-09-11T19:57:00+00:00 | 332.36 | 332.51 | 332.36 | 332.44 | 176 |
| 2026-09-11T19:58:00+00:00 | 332.44 | 332.53 | 332.36 | 332.43 | 231 |
| 2026-09-11T19:59:00+00:00 | 332.43 | 332.54 | 331.89 | 332.23 | 508 |

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

df = pd.read_csv('AAPL_1m.csv', parse_dates=['datetime'])
df.set_index('datetime', inplace=True)
print(df.describe())
```

### backtrader

```python
import backtrader as bt
import pandas as pd

df = pd.read_csv('AAPL_1m.csv', parse_dates=['datetime'])
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

df = pd.read_csv('AAPL_1m.csv', parse_dates=['datetime'])
close = df.set_index('datetime')['close']
fast, slow = vbt.MA.run(close, 10), vbt.MA.run(close, 50)
entries = fast.ma_crossed_above(slow)
exits = fast.ma_crossed_below(slow)
pf = vbt.Portfolio.from_signals(close, entries, exits, init_cash=10_000, freq='1min')
print(pf.stats())
```

## Download full data

The complete **AAPL** archive on **[getdata.finance](https://getdata.finance/datasets/aapl)** includes **11 OHLCV timeframes** (1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W) — **1,218,462** rows at `1m`, plus all other timeframes in the same ZIP.

**[-> Get the full AAPL dataset on getdata.finance](https://getdata.finance/datasets/aapl)**

---
*GetData · AAPL 1m OHLCV sample on GitHub · Full historical data on [getdata.finance](https://getdata.finance/datasets/aapl)*
