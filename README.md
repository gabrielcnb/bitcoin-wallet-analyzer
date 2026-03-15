# Bitcoin Wallet Analyzer

Fetches transaction history for a Bitcoin wallet and calculates return in EUR using historical prices at the time of each transaction.

## Features

- Full transaction history from blockchain.info
- EUR value at time of each transaction (CoinDesk historical API)
- Current wallet balance and value
- Net return calculation

## Setup

```bash
pip install requests
export BITCOIN_ADDRESS=your_bc1q_address_here
python retorno.py
```

## APIs used

- [blockchain.info](https://blockchain.info) — transaction data (free, no key)
- [CoinDesk API](https://api.coindesk.com) — historical BTC/EUR prices (free, no key)
- [blockchain.com](https://blockchain.com) — current BTC price (free, no key)
