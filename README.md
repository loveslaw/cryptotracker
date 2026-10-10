# 🤖 CryptoTracker - Discord Blockchain Confirmation Bot

[![Discord Bot](https://img.shields.io/badge/Discord-Bot-5865F2?logo=discord&logoColor=white)](https://github.com/loveslaw/cryptotracker)
[![Python](https://img.shields.io/badge/Python-3.10+-blue?logo=python&logoColor=white)](https://python.org)

An asynchronous Discord bot that tracks cryptocurrency transactions on the blockchain and pings users when their transaction reaches the desired number of network confirmations.

## ✨ Features
- **Multi-Currency Support**: Tracks Bitcoin (`BTC`), Ethereum (`ETH`), and Litecoin (`LTC`).
- **Confirmation Alerts**: User-defined confirmation thresholds (e.g., notify at 1, 3, or 6 confirmations).
- **Discord Slash Commands**: Built entirely with Discord Application Commands for modern UI interaction.
- **Fast Block Explorer API**: Asynchronous polling with exponential backoff to minimize latency.

## 🚀 Getting Started

### 1. Prerequisites
- Python 3.10 or higher
- Discord Bot Application with Bot Token

### 2. Setup
```bash
git clone https://github.com/loveslaw/cryptotracker.git
cd cryptotracker
pip install -r requirements.txt
```

### 3. Environment Variables
Create a `.env` file in the root directory:
```env
DISCORD_TOKEN=your_bot_token_here
```

### 4. Run
```bash
python main.py
```
