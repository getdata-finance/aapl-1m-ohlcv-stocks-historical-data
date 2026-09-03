# AAPL 1m OHLCV US stocks Historical Data — Free Sample

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Dataset rows](https://img.shields.io/badge/full_dataset-55_440_rows-blue)](https://getdata.finance/datasets/aapl) [![Updated](https://img.shields.io/badge/weekly_update-every_Saturday_8am_UTC-green)](https://getdata.finance) [![Full data on getdata.finance](https://img.shields.io/badge/download-getdata.finance-orange)](https://getdata.finance/datasets/aapl)

### -> [**Download the full AAPL dataset on getdata.finance**](https://getdata.finance/datasets/aapl)

**AAPL 1m OHLCV stocks historical data** — ultra high-quality 1m OHLCV for **Apple**. Clean `time, open, high, low, close, volume` CSV for backtesting, algorithmic trading and quantitative research.

## Table of contents

- [Why this dataset?](#why-this-dataset)
- [Download sample CSV](#download-sample)
- [Sample vs full dataset](#sample-vs-full-dataset)
- [Timeframes on GetData](#timeframes-on-getdata)
- [Weekly updates](#weekly-updates)
- [Data preview](#data-preview)
- [Schema](#schema)
- [Download full data on getdata.finance](#download-full-data-on-getdata)

## Why this dataset?

- **Ultra high-quality 1m OHLCV** for **Apple** (US stocks)
- **Clean CSV schema** — `time, open, high, low, close, volume` (no gaps in formatting)
- **Free evaluation sample** on GitHub (`1m`) · **11 timeframes** on [getdata.finance](https://getdata.finance/datasets/aapl) · **55,440** `1m` rows in the full archive
- Built for **backtesting**, **algorithmic trading** and **quantitative finance** workflows
- **Weekly refresh** — [getdata.finance](https://getdata.finance) every **Saturday, 8am UTC+0**; GitHub `1m` sample updated in sync

> **Sample on GitHub** · `AAPL_1M.csv` (55,440 rows, `2026-02-06` -> `2026-09-01`). **Full archive on [getdata.finance](https://getdata.finance/datasets/aapl)** — **55,440** `1m` rows, **11 timeframes**, updated weekly.

## Download sample

**[AAPL_1M.csv](https://github.com/getdata-finance/aapl-1m-ohlcv-stocks-historical-data/blob/main/AAPL_1M.csv)** on GitHub ([raw CSV](https://raw.githubusercontent.com/getdata-finance/aapl-1m-ohlcv-stocks-historical-data/main/AAPL_1M.csv))

## Sample vs full dataset

| | **Sample (this repo)** | **Full dataset ([getdata.finance](https://getdata.finance/datasets/aapl))** |
|---|--:|---|
| Instrument | Apple · US stocks | Apple · US stocks |
| Timeframes | `1m` (sample) | **11** — 1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W |
| 1m rows | 55,440 | **55,440** |
| Period | `2026-02-06` -> `2026-09-01` | full archive |
| File | `AAPL_1M.csv` | ZIP on [getdata.finance](https://getdata.finance/datasets/aapl) |
| Coverage report | — | [AAPL coverage](https://getdata.finance/coverage/aapl) |
| Updates | Weekly (Saturday, 8am UTC+0) — GitHub sample | Weekly (Saturday, 8am UTC+0) — all timeframes |

## Timeframes on GetData

This GitHub repository ships a **`1m` evaluation sample** only. On **[getdata.finance](https://getdata.finance/datasets/aapl)**, each full asset archive is delivered as a ZIP with **11 gap-free OHLCV timeframes**:

**1m** · **3m** · **5m** · **15m** · **30m** · **1H** · **4H** · **12H** · **1D** · **3D** · **1W**

## Weekly updates

- **[getdata.finance](https://getdata.finance)** — Full datasets updated every Saturday, 8am UTC+0.
- **GitHub (this repo)** — GitHub samples refreshed weekly, in sync with getdata.finance.

## Data preview

First and latest rows from the GitHub sample **`AAPL_1M.csv`**:

**First rows**

| time | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-02-06T20:00:00+00:00 | 276.69 | 276.75 | 276.59 | 276.69 | 348 |
| 2026-02-06T20:01:00+00:00 | 276.69 | 276.71 | 276.59 | 276.68 | 203 |
| 2026-02-06T20:02:00+00:00 | 276.68 | 276.84 | 276.64 | 276.81 | 196 |
| 2026-02-06T20:03:00+00:00 | 276.81 | 276.86 | 276.7 | 276.84 | 242 |
| 2026-02-06T20:04:00+00:00 | 276.84 | 276.86 | 276.68 | 276.81 | 227 |

**Last rows**

| time | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-09-01T19:55:00+00:00 | 324.45 | 324.6 | 323.86 | 324.05 | 332 |
| 2026-09-01T19:56:00+00:00 | 324.05 | 324.13 | 323.68 | 324.12 | 335 |
| 2026-09-01T19:57:00+00:00 | 324.12 | 324.41 | 323.95 | 324.36 | 393 |
| 2026-09-01T19:58:00+00:00 | 324.36 | 324.66 | 324.17 | 324.62 | 378 |
| 2026-09-01T19:59:00+00:00 | 324.62 | 324.88 | 324.42 | 324.79 | 529 |

## Schema

| Column | Description |
| --- | --- |
| `time` | Bar open timestamp (UTC, ISO-8601). |
| `open` | Opening price of the candlestick bar. |
| `high` | Highest price during the bar. |
| `low` | Lowest price during the bar. |
| `close` | Closing price of the candlestick bar. |
| `volume` | Tick volume (number of price updates) during the bar. |

```text
time,open,high,low,close,volume
```

## Download full data

Full AAPL archive — 11 timeframes, gap-free, updated weekly:

**[-> Get the full AAPL dataset on getdata.finance](https://getdata.finance/datasets/aapl)**
