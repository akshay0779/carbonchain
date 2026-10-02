# CarbonChain

A blockchain-powered carbon credit trading platform, simulated entirely in the browser. One HTML file, no build step, no dependencies.

> **Disclaimer:** This is a simulated educational project. It does not create legally recognized carbon credits.

## Features

- **Custom blockchain:** blocks, SHA-256 hashing, proof-of-work mining with adjustable difficulty, chain validation, tamper demo, Merkle tree view, transaction pool with manual mining
- **Credit issuance:** project audits (some projects fail), quality ratings and vintages, minting only for verified projects
- **P2P marketplace:** list and buy lots, with a "vs fair value" indicator
- **Order book:** bid/ask depth chart with instant buy and sell
- **Retirement:** permanent retirement with blockchain-verified, printable certificates
- **Smart contract simulation:** Solidity-style `CarbonCredit` contract with callable `transfer` and `retire`, plus an event log
- **Wallets:** Ethereum-style addresses, four simulated wallets
- **Price engine:** geometric Brownian motion, random market news events, trading bots with two strategies
- **Cap-and-trade compliance:** emissions caps, quarterly reporting, yearly settlement with fines
- **Extras:** footprint offset calculator, leaderboard, impact page, CSV export, save/load ledger, guided tour, mining sound and animation, dark and light themes

## Run it

Open `index.html` in any modern browser. State is saved in `localStorage`; use **Reset chain** to start over, or **Save / Load** to back up and restore a ledger as text.

## Host it on GitHub Pages

Repository **Settings → Pages → Deploy from a branch → `main` / root**. The site will be served at `https://<your-username>.github.io/<repo-name>/`.

## Notes

- Everything runs client-side. There is no real blockchain network, money, or wallet key involved.
- Wallet addresses are random hex strings, not derived from real keys.

## License

MIT
