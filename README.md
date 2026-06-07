# Pine Premarket Planner

Pine Script v5 indicator for **TradingView**.
Draws rectangle zones for QQQ premarket **upside** and **downside** key levels,
with sticky labels and call/put bias logic.

## Features

- Two colored zones (green = upside, red = downside) that extend across all candles
- Sticky labels that update each bar so they always appear at the right edge
- **Call bias** label shown when `close >= upside_level`
- **Put bias** label shown when `close <= downside_level`

## Inputs

| Input | Description | Default |
|---|---|---|
| `upside_level` | Price level for the upside zone center | 0.0 |
| `downside_level` | Price level for the downside zone center | 0.0 |
| `zone_height` | Height of each zone in points | 0.5 |

## Installation

1. Open TradingView → Pine Editor
2. Paste `premarket_planner.pine`
3. Click **Add to chart**
4. Set your premarket levels in the indicator settings
