# 📊 Crypto Market Data

[![GitHub Stars](https://img.shields.io/github/stars/ErcinDedeoglu/crypto-market-data?style=social)](https://github.com/ErcinDedeoglu/crypto-market-data/stargazers)
[![GitHub Watchers](https://img.shields.io/github/watchers/ErcinDedeoglu/crypto-market-data?style=social)](https://github.com/ErcinDedeoglu/crypto-market-data/watchers)
[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](LICENSE)

> **🚨 Free Crypto Data for ML & Research** — High-quality on-chain and derivatives market data that typically costs **$500-2000+/month** from commercial providers. Help us keep this free!

Automated cryptocurrency on-chain and derivatives market data collection for ML model training and trading signal analysis.

---

## 💝 Support This Project

<table>
<tr>
<td align="center">

### ⭐ Star This Repo

The easiest way to support us! Stars help others discover this project.

[![Star](https://img.shields.io/badge/⭐_Star_This_Repo-yellow?style=for-the-badge)](https://github.com/ErcinDedeoglu/crypto-market-data)

</td>
<td align="center">

### 👁️ Watch for Updates

Get notified about new datasets and features.

[![Watch](https://img.shields.io/badge/👁️_Watch_Repo-blue?style=for-the-badge)](https://github.com/ErcinDedeoglu/crypto-market-data/subscription)

</td>
</tr>
</table>

### 📢 Share on Social Media

Help spread the word! Every share helps keep this project alive.

[![Twitter](https://img.shields.io/badge/Share_on_Twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white)](https://twitter.com/intent/tweet?text=🚀%20Free%20crypto%20on-chain%20data%20for%20ML%20research!%20High-quality%20BTC%20derivatives%2C%20whale%20activity%2C%20and%20more.&url=https://github.com/ErcinDedeoglu/crypto-market-data&hashtags=crypto,bitcoin,machinelearning,data)
[![LinkedIn](https://img.shields.io/badge/Share_on_LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/sharing/share-offsite/?url=https://github.com/ErcinDedeoglu/crypto-market-data)
[![Reddit](https://img.shields.io/badge/Share_on_Reddit-FF4500?style=for-the-badge&logo=reddit&logoColor=white)](https://www.reddit.com/submit?url=https://github.com/ErcinDedeoglu/crypto-market-data&title=Free%20Crypto%20On-Chain%20Data%20for%20ML%20Research)

---

## 📁 Data Structure

Data is organized by granularity (time frequency):

```
data/
└── daily/      # Daily aggregated data (1 data point per day)
```

## 📊 Available Datasets

Browse the [`data/daily/`](data/daily/) folder for all available datasets.

### Supply/Demand (Whales)

| Dataset | File |
|---------|------|
| BTC Exchange Netflow | [`data/daily/btc_exchange_netflow.json`](data/daily/btc_exchange_netflow.json) |
| BTC Exchange Reserve | [`data/daily/btc_exchange_reserve.json`](data/daily/btc_exchange_reserve.json) |
| BTC Exchange Reserve USD | [`data/daily/btc_exchange_reserve_usd.json`](data/daily/btc_exchange_reserve_usd.json) |
| BTC Exchange Inflow Total | [`data/daily/btc_exchange_inflow_total.json`](data/daily/btc_exchange_inflow_total.json) |
| BTC Exchange Outflow Total | [`data/daily/btc_exchange_outflow_total.json`](data/daily/btc_exchange_outflow_total.json) |
| BTC Exchange Whale Ratio | [`data/daily/btc_exchange_whale_ratio.json`](data/daily/btc_exchange_whale_ratio.json) |
| BTC Exchange Stablecoins Ratio | [`data/daily/btc_exchange_stablecoins_ratio.json`](data/daily/btc_exchange_stablecoins_ratio.json) |
| BTC Exchange Stablecoins Ratio USD | [`data/daily/btc_exchange_stablecoins_ratio_usd.json`](data/daily/btc_exchange_stablecoins_ratio_usd.json) |
| Stablecoin Exchange Netflow | [`data/daily/stablecoin_exchange_netflow.json`](data/daily/stablecoin_exchange_netflow.json) |
| Stablecoin Exchange Reserve | [`data/daily/stablecoin_exchange_reserve.json`](data/daily/stablecoin_exchange_reserve.json) |
| Stablecoin Exchange Inflow Total | [`data/daily/stablecoin_exchange_inflow_total.json`](data/daily/stablecoin_exchange_inflow_total.json) |
| Stablecoin Exchange Outflow Total | [`data/daily/stablecoin_exchange_outflow_total.json`](data/daily/stablecoin_exchange_outflow_total.json) |

### Miners

| Dataset | File |
|---------|------|
| BTC Miners Position Index | [`data/daily/btc_miners_position_index.json`](data/daily/btc_miners_position_index.json) |
| BTC Miner Netflow Total | [`data/daily/btc_miner_netflow_total.json`](data/daily/btc_miner_netflow_total.json) |
| BTC Puell Multiple | [`data/daily/btc_puell_multiple.json`](data/daily/btc_puell_multiple.json) |

### Derivatives/Sentiment

| Dataset | File |
|---------|------|
| BTC Funding Rates | [`data/daily/btc_funding_rates.json`](data/daily/btc_funding_rates.json) |
| BTC Open Interest | [`data/daily/btc_open_interest.json`](data/daily/btc_open_interest.json) |
| BTC Taker Buy Sell Ratio | [`data/daily/btc_taker_buy_sell_ratio.json`](data/daily/btc_taker_buy_sell_ratio.json) |
| BTC Long Liquidations | [`data/daily/btc_long_liquidations.json`](data/daily/btc_long_liquidations.json) |
| BTC Long Liquidations USD | [`data/daily/btc_long_liquidations_usd.json`](data/daily/btc_long_liquidations_usd.json) |
| BTC Short Liquidations | [`data/daily/btc_short_liquidations.json`](data/daily/btc_short_liquidations.json) |
| BTC Short Liquidations USD | [`data/daily/btc_short_liquidations_usd.json`](data/daily/btc_short_liquidations_usd.json) |

### Valuation

| Dataset | File |
|---------|------|
| BTC MVRV Ratio | [`data/daily/btc_mvrv_ratio.json`](data/daily/btc_mvrv_ratio.json) |

### Liquidity/Context

| Dataset | File |
|---------|------|
| BTC Exchange Supply Ratio | [`data/daily/btc_exchange_supply_ratio.json`](data/daily/btc_exchange_supply_ratio.json) |
| BTC Fund Flow Ratio | [`data/daily/btc_fund_flow_ratio.json`](data/daily/btc_fund_flow_ratio.json) |
| Stablecoin Exchange Supply Ratio | [`data/daily/stablecoin_exchange_supply_ratio.json`](data/daily/stablecoin_exchange_supply_ratio.json) |

### Institutional vs Retail

| Dataset | File |
|---------|------|
| BTC Coinbase Premium Index | [`data/daily/btc_coinbase_premium_index.json`](data/daily/btc_coinbase_premium_index.json) |
| BTC Coinbase Premium Gap | [`data/daily/btc_coinbase_premium_gap.json`](data/daily/btc_coinbase_premium_gap.json) |
| BTC Korea Premium Index | [`data/daily/btc_korea_premium_index.json`](data/daily/btc_korea_premium_index.json) |

---

## 📄 Data Format

Each JSON file contains:

```json
{
  "name": "Metric Name",
  "description": "What this metric measures and why it matters",
  "data_type": "Decimal (BTC/USD/%)",
  "update_frequency": "Daily/Hourly/Real-time",
  "category": "Category Name",
  "trading_signal": "How to interpret for trading decisions",
  "granularity": "daily/hourly/minute",
  "first_data_date": 1231006505000,
  "last_data_date": 1733184000000,
  "last_added_date": 1733184000,
  "last_modified_date": 1733184000,
  "data": [
    {"timestamp": 1609459200000, "value": 123.45, "last_modified": 1733184000},
    {"timestamp": 1609545600000, "value": 234.56, "last_modified": 1733184000}
  ],
  "updated_at": 1733184000
}
```

### Field Descriptions

| Field | Description |
|-------|-------------|
| `name` | Human-readable metric name |
| `description` | Detailed explanation of what the metric measures |
| `data_type` | Unit of measurement (BTC, USD, %, ratio) |
| `update_frequency` | How often the source data updates |
| `category` | Metric category for grouping |
| `trading_signal` | Interpretation guide for trading decisions |
| `granularity` | Time granularity: daily, hourly, or minute |
| `first_data_date` | Unix timestamp in milliseconds (UTC) of earliest data point |
| `last_data_date` | Unix timestamp in milliseconds (UTC) of latest data point |
| `last_added_date` | Unix timestamp in milliseconds (UTC) when new data was last added |
| `last_modified_date` | Unix timestamp in milliseconds (UTC) when any value was last modified |
| `data` | Array of data points with `timestamp`, `value`, and `last_modified` (all timestamps in ms UTC) |
| `updated_at` | Unix timestamp in milliseconds (UTC) when this file was last updated |

---

## 🤖 Usage for ML Models

This data is structured for easy consumption by ML models:

1. **Time Series**: Each dataset is sorted by timestamp ascending
2. **Consistent Format**: All datasets follow the same JSON schema
3. **Rich Metadata**: Description and trading signal fields provide context
4. **Granularity Support**: Choose the appropriate time resolution for your model
5. **Change Tracking**: `last_modified` fields help identify data revisions

### 💰 Value Proposition

| What You Get | Commercial Alternative | Annual Savings |
|--------------|----------------------|----------------|
| On-chain metrics | Premium API ($99+/mo) | **$1,188+** |
| Derivatives data | Professional API ($199+/mo) | **$2,388+** |
| Historical data | Enterprise API ($500+/mo) | **$6,000+** |
| **Total Potential Savings** | | **$9,500+/year** |

> 💡 **Remember:** If you find this valuable, [star the repo](#-support-this-project) and [add attribution](#-license--attribution) to your project!

---

## ⚠️ Disclaimer

**No Warranty or Guarantee of Service**

This data is provided **"AS IS"** without any warranty or guarantee of any kind. 

- ❌ **No guarantee** of continued availability or updates
- ❌ **No guarantee** of data accuracy or completeness  
- ❌ **No guarantee** of uptime or service continuity
- ❌ **Not financial advice** — for educational and research purposes only

**This is a community-funded project.** Without sufficient community support (stars, sponsorships, contributions), this free service may be discontinued at any time without notice. If you rely on this data, please consider [supporting the project](#-support-this-project).

---

## 📜 License & Attribution

### ⚠️ **Attribution is MANDATORY**

This project provides **free access to expensive crypto market data**. In return, **proper attribution is required** when using this data in any project, research, publication, or application.

#### Required Attribution

If you use this data, you **MUST** include the following:

**For README/Documentation:**
```markdown
## Data Source
Crypto market data provided by [Crypto Market Data](https://github.com/ErcinDedeoglu/crypto-market-data) by Ercin Dedeoglu.
```

**For Academic Papers/Research:**
```bibtex
@misc{dedeoglu_crypto_market_data,
  author = {Dedeoglu, Ercin},
  title = {Crypto Market Data: On-chain and Derivatives Market Data},
  year = {2025},
  publisher = {GitHub},
  url = {https://github.com/ErcinDedeoglu/crypto-market-data}
}
```

**For Applications/Websites:**
Display a visible attribution link: `Data: Ercin Dedeoglu - Crypto Market Data`

### Why Attribution Matters

| Cost | Commercial Providers | This Project |
|------|---------------------|--------------|
| Monthly API Access | $500 - $2,000+ | **FREE** |
| Historical Data | $1,000 - $5,000+ | **FREE** |
| Real-time Updates | $200 - $500/month | **FREE** |

**Collecting and serving this data is expensive.** Your attribution helps:
- 🌟 **Increase visibility** so more developers can benefit
- 💪 **Encourage contributions** from the community
- 🚀 **Attract sponsors** to keep the project running
- 📈 **Justify continued maintenance** and new feature development

### License Terms

This data is provided under [CC BY 4.0](LICENSE):

✅ **You CAN:**
- Use the data for personal projects
- Use the data for commercial applications
- Modify and adapt the data
- Redistribute the data (with attribution)

❌ **You CANNOT:**
- Use the data without proper attribution
- Remove or hide attribution from redistributed data
- Claim the data as your own original work

---

## 🤝 How to Contribute

We welcome contributions! Here's how you can help:

### Ways to Help
- 🐛 **Report bugs** and data issues
- 💡 **Suggest new metrics** or data sources
- 📢 **Share** with your network
- ⭐ **Star** this repository

### Sponsor This Project

If this data saves you money, consider supporting the project:

[![GitHub Sponsors](https://img.shields.io/badge/Sponsor-GitHub%20Sponsors-ea4aaa?style=for-the-badge&logo=github-sponsors)](https://github.com/sponsors/ErcinDedeoglu)
[![Buy Me a Coffee](https://img.shields.io/badge/Buy%20Me%20a%20Coffee-ffdd00?style=for-the-badge&logo=buy-me-a-coffee&logoColor=black)](https://buymeacoffee.com/ercin)

---

## 📬 Contact & Community

- 🐛 **Issues:** [GitHub Issues](https://github.com/ErcinDedeoglu/crypto-market-data/issues)
- 🐦 **Twitter/X:** [@ErcinDedeoglu](https://x.com/ErcinDedeoglu)
- 🔗 **LinkedIn:** [Ercin Dedeoglu](https://linkedin.com/in/ercindedeoglu)

---

<p align="center">
  <b>If this project helps you, please ⭐ star this repository!</b><br>
  <sub>Made with ❤️ by <a href="https://github.com/ErcinDedeoglu">Ercin Dedeoglu</a></sub>
</p>
