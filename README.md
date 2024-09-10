# Autonomous Crypto Trader

## Overview

Autonomous Crypto Trader is a cryptocurrency trading bot that operates on the Kraken exchange. This bot is capable of automating trades based on predefined strategies and uses Freqtrade to execute trades efficiently. The bot is designed to provide flexibility and ease of use for both beginners and advanced traders.

## Features

- **Automated Trading**: Executes buy and sell orders based on strategies.
- **Dry-run Mode**: Test strategies in a simulated environment without real money.
- **Configurable Settings**: Easily adjust settings like stake amount, trading pairs, and strategy timeframe.
- **Telegram Notifications**: Receive live trade updates and bot notifications directly on Telegram.
- **Kraken Integration**: Seamlessly connects to the Kraken cryptocurrency exchange.

## Requirements

- Python 3.8 or higher
- Freqtrade (installed via virtual environment)
- Kraken API keys (for live trading)

## Installation

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/nayers17/autonomous-crypto-trader.git
   cd autonomous-crypto-trader

   Set Up Virtual Environment:

bash
Copy code
python3 -m venv .venv
source .venv/bin/activate
Install Freqtrade:

bash
Copy code
./setup.sh --install
Configure the Bot: Generate the configuration file:

bash
Copy code
freqtrade new-config -c user_data/config.json
Add API Keys: Add your Kraken API keys to config.json.

Usage
Activate the Virtual Environment:

bash
Copy code
source .venv/bin/activate
Run the Bot in Dry-Run Mode:

bash
Copy code
freqtrade trade --config user_data/config.json --dry-run
Run the Bot for Live Trading:

bash
Copy code
freqtrade trade --config user_data/config.json
Configuration
config.json: The main configuration file where you set trading parameters, exchange details, and strategy settings.
api_keys.txt: Store your Kraken API key and secret here. Ensure this file is ignored in .gitignore.
License
This project is licensed under the MIT License.

Disclaimer
This bot is for educational purposes only. Cryptocurrency trading is highly volatile, and the use of an automated bot does not guarantee profits. Please trade responsibly.

markdown
Copy code

### How to Use It:
1. Create a `README.md` file in the root directory of your project.
2. Copy the content above and paste it into the `README.md` file.
3. Save the file, and you’re all set!

Let me know if you need any further modifications or additions to the README!