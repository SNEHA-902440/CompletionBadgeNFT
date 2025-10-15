# 🎓 Completion Badge NFT on Flow Testnet

This project implements a **Completion Badge NFT** on the **Flow Testnet** to recognize course or task completion using non-fungible tokens (NFTs).

---

## 📍 Contract Address

- **Contract name**: 'CompletionBadgeNFT'
- **Flow Testnet Address**: `0x84e4C3010A0394465c58A973838CCA9c327A7027`  
- **Network**: [Flow Testnet](https://testnet.flowscan.org/)

---

## 🔧 Overview

This contract issues **unique badge NFTs** to represent task or course completion.

### Key Features:

- Written in **Cadence** (Flow’s smart contract language)
- NFTs follow **Flow NFT Standard**
- Only the contract account (admin) can mint badges
- Each badge is a unique NFT with its own ID and optional metadata

---

## 🧪 Flow Testnet Setup

### 📦 Prerequisites

- [Flow CLI](https://docs.onflow.org/flow-cli/install/)
- A Flow Testnet account with deployed contract
- [Testnet faucet](https://testnet-faucet.onflow.org/) to get tokens

### 🔗 Connect to Flow Testnet

```bash
flow networks add testnet "access.devnet.nodes.onflow.org:9000"
