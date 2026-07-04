# NAS100 30m OHLCV Index Historical Data — Free Sample

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Dataset rows](https://img.shields.io/badge/full_dataset-9_392_rows-blue)](https://ork.ad/) [![Updated](https://img.shields.io/badge/weekly_update-every_Sunday-green)](https://ork.ad/) [![Full data on ork.ad](https://img.shields.io/badge/download-ork.ad-orange)](https://ork.ad/)

### → [**Download the full NAS100 dataset on ork.ad**](https://ork.ad/)

**NAS100 30m OHLCV Stock index historical data** — ultra high-quality 30m OHLCV for **Nasdaq 100**. Global cash and extended index sessions — Asia, Europe and US coverage, not US-hours only. Clean `time, open, high, low, close, volume` CSV for backtesting, algorithmic trading and quantitative research.

## Table of contents

- [Why this dataset?](#why-this-dataset)
- [Download sample CSV](#download-sample)
- [GitHub Pages preview](#github-pages)
- [Sample vs full dataset](#sample-vs-full-dataset)
- [Timeframes on ork.ad](#timeframes-on-orkad)
- [Weekly updates](#weekly-updates)
- [Data preview](#data-preview)
- [Schema](#schema)
- [Code examples](#code-examples)
- [Download full data on ork.ad](#download-full-data)

## Why this dataset?

- **Ultra high-quality 30m OHLCV** for **Nasdaq 100** (Stock index)
- **Global cash and extended index sessions — Asia, Europe and US coverage, not US-hours only**
- **Clean CSV schema** — `time, open, high, low, close, volume` (no gaps in formatting)
- **Free evaluation sample** on GitHub (`30m`) · **13 timeframes** on [ork.ad](https://ork.ad/) · **9,392** `30m` rows in the full archive
- Built for **backtesting**, **algorithmic trading** and **quantitative finance** workflows
- **Weekly refresh** — [ork.ad](https://ork.ad/) every **Sunday**; GitHub `30m` sample updated in sync

> **Sample on GitHub** · `NAS100_30m.csv` (8,767 rows, `2025-10-02` → `2026-07-02`). **Full archive on [ork.ad](https://ork.ad/)** — **9,392** `30m` rows (~0.65 MB), **13 timeframes** (``1m`, `3m`, `5m`, `15m`, `30m`, `1H`, `2H`, `4H`, `8H`, `12H`, `16H`, `1D`, `1W``), `2025-09-15` → `2026-07-02`.

## Download sample

**[NAS100_30m.csv](https://github.com/ork-ad/nas100-30m-ohlcv-index-historical-data/blob/main/NAS100_30m.csv)** on GitHub ([raw CSV](https://raw.githubusercontent.com/ork-ad/nas100-30m-ohlcv-index-historical-data/main/NAS100_30m.csv)) · [GitHub Releases](https://github.com/ork-ad/nas100-30m-ohlcv-index-historical-data/releases) when the release workflow is active.

## GitHub Pages

Interactive chart & stats: **[https://ork-ad.github.io/nas100-30m-ohlcv-index-historical-data/](https://ork-ad.github.io/nas100-30m-ohlcv-index-historical-data/)**

## Sample vs full dataset

| | **Sample (this repo)** | **Full dataset ([ork.ad](https://ork.ad/))** |
|---|--:|---|
| Instrument | Nasdaq 100 · Stock index | Nasdaq 100 · Stock index |
| Timeframes | `30m` (sample) | **13** — `1m`, `3m`, `5m`, `15m`, `30m`, `1H`, `2H`, `4H`, `8H`, `12H`, `16H`, `1D`, `1W` |
| 30m rows | 8,767 | **9,392** |
| Size | 0.61 MB | ~0.65 MB |
| Period | `2025-10-02` → `2026-07-02` | `2025-09-15` → `2026-07-02` |
| File | `NAS100_30m.csv` | ZIP on [ork.ad](https://ork.ad/) |
| Updates | Weekly (Sunday) — GitHub sample | Weekly (Sunday) — all timeframes |

## Timeframes on ork.ad

This GitHub repository ships a **`30m` evaluation sample** only. On **[ork.ad](https://ork.ad/)**, each full asset archive is delivered as a ZIP with **13 gap-free OHLCV timeframes** (one CSV per timeframe):

**1m** · **3m** · **5m** · **15m** · **30m** · **1H** · **2H** · **4H** · **8H** · **12H** · **16H** · **1D** · **1W**

GitHub = `30m` sample · [ork.ad](https://ork.ad/) = all **13** timeframes above for the same instrument.

## Weekly updates

- **[ork.ad](https://ork.ad/)** — Full datasets on ork.ad are updated every Sunday.
- **GitHub (this repo)** — GitHub samples are refreshed weekly (every Sunday), in sync with ork.ad.

When a new `30m` sample is published on GitHub, the README, chart preview and CSV reflect the latest week of data.

## Data preview

First and latest rows from the GitHub sample **`NAS100_30m.csv`**:

**First rows**

| time | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2025-10-02T22:00:00Z | 24925.319 | 24926.809 | 24908.689 | 24908.939 | 3750.0 |
| 2025-10-02T22:30:00Z | 24908.939 | 24924.439 | 24892.559 | 24923.439 | 4683.0 |
| 2025-10-02T23:00:00Z | 24923.439 | 24937.059 | 24916.559 | 24936.309 | 2738.0 |
| 2025-10-02T23:30:00Z | 24936.309 | 24944.439 | 24934.059 | 24943.439 | 2515.0 |
| 2025-10-03T00:00:00Z | 24943.439 | 24956.06 | 24935.059 | 24952.56 | 5686.0 |

**Last rows**

| time | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| time | open | high | low | close | volume |
| 2026-07-02T19:00:00Z | 29282.11 | 29296.61 | 29143.11 | 29215.99 | 140686.0 |
| 2026-07-02T19:30:00Z | 29215.99 | 29381.49 | 29204.99 | 29330.11 | 151680.0 |
| 2026-07-02T20:00:00Z | 29330.11 | 29354.96 | 29307.46 | 29341.59 | 40889.0 |
| 2026-07-02T20:30:00Z | 29341.59 | 29357.96 | 29330.09 | 29345.78 | 20269.0 |

## Schema

```text
time,open,high,low,close,volume
```

## Code examples

### pandas

```python
import pandas as pd

df = pd.read_csv('NAS100_30m.csv', parse_dates=['time'])
df.set_index('time', inplace=True)
print(df.describe())
print(df.resample('1h').agg({'open': 'first', 'high': 'max',
                              'low': 'min', 'close': 'last', 'volume': 'sum'}).head())
```

### backtrader

```python
import backtrader as bt
import pandas as pd

df = pd.read_csv('NAS100_30m.csv', parse_dates=['time'])
df.set_index('time', inplace=True)

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

df = pd.read_csv('NAS100_30m.csv', parse_dates=['time'])
close = df.set_index('time')['close']
fast, slow = vbt.MA.run(close, 10), vbt.MA.run(close, 50)
entries = fast.ma_crossed_above(slow)
exits = fast.ma_crossed_below(slow)
pf = vbt.Portfolio.from_signals(close, entries, exits, init_cash=10_000, freq='30min')
print(pf.stats())
```

## Download full data

The complete **NAS100** archive on **[ork.ad](https://ork.ad/)** includes **13 OHLCV timeframes** (`1m`, `3m`, `5m`, `15m`, `30m`, `1H`, `2H`, `4H`, `8H`, `12H`, `16H`, `1D`, `1W`) — **9,392** rows at `30m`, plus all other timeframes in the same ZIP.

**[→ Get the full NAS100 dataset on ork.ad](https://ork.ad/)**

---
*GetData · NAS100 30m OHLCV sample on GitHub · Full historical data on [ork.ad](https://ork.ad/) · 2026-07-04 UTC*