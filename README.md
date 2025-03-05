# Blockchain-Based Transparent Charity Platform 🌐

A decentralized platform built with **Solidity** and **React/TypeScript** to ensure transparency in charitable donations. All transactions are recorded on the blockchain for public auditing.

![Demo Screenshot](./public/screenshot.png) <!-- Add a screenshot later -->

## Features ✨
- **Donate ETH** to the charity with a single click.
- **Withdraw funds** (admin-only) with full transaction history.
- **View all transactions** (donations/withdrawals) in real-time.
- **Immutable records** stored on the Ethereum blockchain.
- **MetaMask integration** for secure wallet interactions.

## Tech Stack 🛠️
- **Smart Contracts**: Solidity, Truffle, Ganache
- **Frontend**: React, TypeScript, Web3.js
- **Testing**: Truffle (Mocha/Chai), React Testing Library
- **Deployment**: Ethereum Testnet (Goerli), Vercel/Netlify

## Prerequisites 📋
- MetaMask browser extension
- Node.js ≥ v16
- Truffle Suite: `npm install -g truffle`
- Ganache (local blockchain)

## Installation 🚀

### 1. Clone the Repository
```bash
git clone https://github.com/your-username/blockchain-charity-platform.git
cd blockchain-charity-platform
```
### 2. Start Local Blockchain
- Open Ganache and create a new workspace.
- Update truffle-config.js to match Ganache's RPC server (port 7545).

