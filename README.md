# Solana JITO Swap

This project is dedicated to protecting Solana transactions from MEV bots.

We're building advanced DEX bots for the community to support our mission at Cortex in advancing stem cell therapies and seizure prediction technologies for epilepsy treatment. By participating in our presale, you'll gain early access to these bots and receive full setup support. Join us in revolutionizing epilepsy treatment and be part of our journey!

For more details, join our Discord at [Core Dex Community](https://discord.gg/AWDgU4WCwV)

## Setup

1. Download raydium's liqudity file:

```sh
mkdir markets
curl https://api.raydium.io/v2/sdk/liquidity/mainnet.json -o ./markets/raydium.json
```

2. Create .env file

- `PRIVATE_KEY` - Your wallet's private key.

## Run

```sh
pnpm run start
```
