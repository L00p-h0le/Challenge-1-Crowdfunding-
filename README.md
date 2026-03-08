# 🏗 Speedrun Ethereum Challenge 1: Crowdfunding

This repository contains my solution to the **Crowdfunding** challenge from [Speedrun Ethereum](https://speedrunethereum.com/).

## 🌟 Overview

The goal of this challenge is to build a decentralized crowdfunding application using Solidity and Scaffold-ETH 2. The contract allows users to:
- Contribute ETH to a fund.
- Execute the funding if a specific threshold is met before a deadline.
- Withdraw their contributions if the funding goal is not achieved by the deadline.

## 🚀 Purpose

This project is for **personal learning purposes** as part of my journey in smart contract development and Ethereum security.

## 🛠 Features

- **Smart Contract Coordination**: Trustless coordination for group funding.
- **State Machine Logic**: Manages contribution, success (execution), and failure (withdrawal) states.
- **Frontend Integration**: A dynamic UI built with Next.js and DaisyUI to interact with the contracts.

## ⚙️ Local Development

1. **Clone the repo**:
   ```sh
   git clone https://github.com/L00p-h0le/Challenge-1-Crowdfunding-
   cd Challenge-1-Crowdfunding-
   ```

2. **Install dependencies**:
   ```sh
   yarn install
   ```

3. **Start the local chain**:
   ```sh
   yarn chain
   ```

4. **Deploy the contract**:
   ```sh
   yarn deploy
   ```

5. **Start the frontend**:
   ```sh
   yarn start
   ```

---
Built with [Scaffold-ETH 2](https://github.com/scaffold-eth/scaffold-eth-2).