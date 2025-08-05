# Taiko Auto Swapper Bot for TRAILBLAZERS SEASON 5

This is an automated token swapping bot built with Node.js, designed to simulate daily, randomized on-chain activity on the Taiko network. It wraps ETH to WETH, swaps to USDC, and back to ETH in an automated loop, mimicking organic wallet behavior.

<img width="953" height="553" alt="image" src="https://github.com/user-attachments/assets/5e5d4c99-2a3e-45be-9675-e8a98d8a62a9" />

## 🚀 Features
- Daily automated transactions with randomized frequency and timing

- ETH ↔ WETH ↔ USDC swaps using on-chain in DEX IceCreamSwap

- Dynamic delay and transaction range per day (configured via .env)

## 📦 Installation
Clone the repository and install dependencies:

```bash
git clone https://github.com/Kurisaitou/Auto-Swap-Bot-for-TRAILBLAZERS-SEASON-5.git
```
```bash
cd Auto-Swap-Bot-for-TRAILBLAZERS-SEASON-5
```
```bash
npm install
```

## ⚙️ Environment Setup
Create a .env file in the project root:
```bash
nano .env
```
Fill in your wallet details and configure your preferred settings:
```bash
PRIVATE_KEY=
TAIKO_RPC=https://rpc.taiko.xyz

# you can change
MIN_TX_PER_DAY=20
MAX_TX_PER_DAY=50

# you can change
MIN_DELAY_MINUTES=1
MAX_DELAY_MINUTES=9

# you can change
MIN_ETH_AMOUNT=0.001
MAX_ETH_AMOUNT=0.009
```

## ▶️ Running the Bot
To start the bot:
```bash
node index.js
```

## 🎯 Goal
Maximize your engagement with the Taiko ecosystem and boost your chances of earning more rewards from trailblazers Season 5 — automatically.

## 🔖 Tags
#trailblazers #airdrop #swap #bot #crypto #web3 #automation #trading #taiko #dex #stake 
