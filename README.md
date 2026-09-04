# CHN50 3d OHLCV Index Historical Data — Free Sample

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Dataset rows](https://img.shields.io/badge/full_dataset-1_104_rows-blue)](https://getdata.finance/datasets/chn50) [![Updated](https://img.shields.io/badge/weekly_update-every_Saturday_8am_UTC-green)](https://getdata.finance) [![Full data on getdata.finance](https://img.shields.io/badge/download-getdata.finance-orange)](https://getdata.finance/datasets/chn50)

### -> [**Download the full CHN50 dataset on getdata.finance**](https://getdata.finance/datasets/chn50)

**CHN50 3d OHLCV index historical data** — ultra high-quality 3d OHLCV for **FTSE China A50**. Clean `datetime, open, high, low, close, volume` CSV for backtesting, algorithmic trading and quantitative research.

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

- **Ultra high-quality 3d OHLCV** for **FTSE China A50** (Index)
- **Clean CSV schema** — `datetime, open, high, low, close, volume` (no gaps in formatting)
- **Free evaluation sample** on GitHub (`3d`) · **11 timeframes** on [getdata.finance](https://getdata.finance/datasets/chn50) · **1,104** `3d` rows in the full archive
- Built for **backtesting**, **algorithmic trading** and **quantitative finance** workflows
- **Weekly refresh** — [getdata.finance](https://getdata.finance) every **Saturday, 8am UTC+0**; GitHub `3d` sample updated in sync

> **Sample on GitHub** · `CHN50_3d.csv` (244 rows, `2024-09-02` -> `2026-09-01`, 21.91 KB). **Full archive on [getdata.finance](https://getdata.finance/datasets/chn50)** — **1,104** `3d` rows (full `1m`: 2,664,006), **11 timeframes**, `2017-07-17` -> `2026-09-01`.

## Download sample

**[CHN50_3d.csv](https://github.com/getdata-finance/chn50-3d-ohlcv-index-historical-data/blob/main/CHN50_3d.csv)** on GitHub ([raw CSV](https://raw.githubusercontent.com/getdata-finance/chn50-3d-ohlcv-index-historical-data/main/CHN50_3d.csv)) · [GitHub Releases](https://github.com/getdata-finance/chn50-3d-ohlcv-index-historical-data/releases)

## GitHub Pages

Interactive chart & stats: **[https://getdata-finance.github.io/chn50-3d-ohlcv-index-historical-data/](https://getdata-finance.github.io/chn50-3d-ohlcv-index-historical-data/)**

Full archive & live chart on getdata.finance: **[https://getdata.finance/datasets/chn50](https://getdata.finance/datasets/chn50)**

## Sample vs full dataset

| | **Sample (this repo)** | **Full dataset ([getdata.finance](https://getdata.finance/datasets/chn50))** |
|---|--:|---|
| Instrument | FTSE China A50 · Index | FTSE China A50 · Index |
| Timeframes | `3d` (sample) | **11** — 1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W |
| 3d rows | 244 | **1,104** |
| Size | 21.91 KB | full ZIP on [getdata.finance](https://getdata.finance/datasets/chn50) |
| Period | `2024-09-02` -> `2026-09-01` | `2017-07-17` -> `2026-09-01` |
| File | `CHN50_3d.csv` | ZIP on [getdata.finance](https://getdata.finance/datasets/chn50) |
| Coverage report | — | [CHN50 coverage](https://getdata.finance/coverage/chn50) |
| Updates | Weekly (Saturday, 8am UTC+0) — GitHub sample | Weekly (Saturday, 8am UTC+0) — all timeframes |

## Timeframes on GetData

This GitHub repository ships a **`3d` evaluation sample** only. On **[getdata.finance](https://getdata.finance/datasets/chn50)**, each full asset archive is delivered as a ZIP with **11 gap-free OHLCV timeframes** (one CSV per timeframe):

**1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W**

GitHub = `3d` sample · [getdata.finance](https://getdata.finance/datasets/chn50) = all **11** timeframes above for the same instrument.

## Weekly updates

- **[getdata.finance](https://getdata.finance)** — Full datasets are updated every Saturday, 8am UTC+0.
- **GitHub (this repo)** — GitHub samples are refreshed weekly (every Saturday, 8am UTC+0), in sync with getdata.finance.

When a new `3d` sample is published on GitHub, the README, chart preview and CSV reflect the latest week of data.

## Data preview

First and latest rows from the GitHub sample **`CHN50_3d.csv`**:

**First rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2024-09-02T00:00:00+00:00 | 11693.93 | 11702.06 | 11427.53 | 11474.05 | 110111.8756 |
| 2024-09-05T00:00:00+00:00 | 11474.05 | 11562.66 | 11350.16 | 11355.67 | 53281 |
| 2024-09-08T00:00:00+00:00 | 11355.67 | 11392.18 | 11227.16 | 11260.87 | 65640.98852 |
| 2024-09-11T00:00:00+00:00 | 11260.87 | 11276.32 | 11115.57 | 11140.05 | 86368.5009 |
| 2024-09-14T00:00:00+00:00 | 11140.05 | 11190.49 | 11117.48 | 11174.99 | 9629.7107 |

**Last rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-08-20T00:00:00+00:00 | 14795.53 | 14866.88 | 14620.18 | 14812.86 | 135589.81992 |
| 2026-08-23T00:00:00+00:00 | 14815.3 | 14854.33 | 14538.32 | 14653.54 | 154971 |
| 2026-08-26T00:00:00+00:00 | 14653.54 | 14859.66 | 14579.73 | 14724.01 | 190412 |
| 2026-08-29T00:00:00+00:00 | 14724.01 | 14769.01 | 14518.99 | 14733.49 | 60624 |
| 2026-09-01T00:00:00+00:00 | 14733.49 | 14872.51 | 14542.99 | 14543.99 | 80979 |

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

df = pd.read_csv('CHN50_3d.csv', parse_dates=['datetime'])
df.set_index('datetime', inplace=True)
print(df.describe())
```

### backtrader

```python
import backtrader as bt
import pandas as pd

df = pd.read_csv('CHN50_3d.csv', parse_dates=['datetime'])
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

df = pd.read_csv('CHN50_3d.csv', parse_dates=['datetime'])
close = df.set_index('datetime')['close']
fast, slow = vbt.MA.run(close, 10), vbt.MA.run(close, 50)
entries = fast.ma_crossed_above(slow)
exits = fast.ma_crossed_below(slow)
pf = vbt.Portfolio.from_signals(close, entries, exits, init_cash=10_000, freq='3d')
print(pf.stats())
```

## Download full data

The complete **CHN50** archive on **[getdata.finance](https://getdata.finance/datasets/chn50)** includes **11 OHLCV timeframes** (1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W) — **1,104** rows at `3d`, plus all other timeframes in the same ZIP.

**[-> Get the full CHN50 dataset on getdata.finance](https://getdata.finance/datasets/chn50)**

---
*GetData · CHN50 3d OHLCV sample on GitHub · Full historical data on [getdata.finance](https://getdata.finance/datasets/chn50)*
