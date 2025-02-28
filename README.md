# Wallet-Analysis-Bot

## Introduction
The **Anti-Sweeper Bot** is designed to detect and prevent sweeper bot attacks on hacked wallets. It checks balances across multiple chains, detects incoming funds, and ensures assets are secured by automatically transferring them to a safe wallet.

## Features
- **Multi-Chain Balance Check**: Scans all available chains for wallet balances.
- **Incoming Funds Detection**: Monitors wallets for incoming transactions and moves funds instantly.
- **Auto-Retry for Stuck Transactions**: Retries failed transactions without looping across multiple chains.

## Installation
### Prerequisites
Ensure you have the following installed:
- Python 3.8+
- Git
- Pip

### Steps
1. **Clone the Repository**
   ```sh
   git clone https://github.com/xmmitro/Wallet-Analysis-Bot.git
   cd Wallet-Analysis-Bot
   ```
2. **Install Dependencies**
   ```sh
   pip install -r requirements.txt
   ```
3. **Set Up Environment Variables**
   - Create a `.env` file in the root directory.
   - Add the following details:
     ```ini
     PRIVATE_KEY=your_wallet_private_key
     SAFE_WALLET=your_safe_wallet_address
     RPC_URL=https://your_rpc_endpoint
     ```

## Usage
Run the bot with:
```sh
python wallet.py
```

## Contribution
1. Fork the repository.
2. Create a new branch (`feature-branch`).
3. Make your changes and commit them.
4. Push to your fork and create a pull request.

## License
This project is licensed under the MIT License.

