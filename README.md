# The Scroll Handbook

Welcome. This is EasyA's legendary handbook. If you want to learn Scroll like a legend, then you're in the right place.

# Purpose

This handbook serves as a guide to the Scroll ecosystem, geared towards those just joining for the first time. It isn't just a beginners' handbook; it's a legendary handbook. Even if you've already immersed yourself in the ecosystem, you'll find tons of helpful tidbits around here!

# The EasyA App

Of course, the best place to start is always the [EasyA](https://www.easya.io) app! Download it here for the fastest and most fun way to learn about Scroll. Download it directly right [here](https://links.easya.io/links/gotoapp)!

## Table of Contents

- [Introduction](#introduction)
- [Getting Started](#getting-started)
- [Core Concepts](#core-concepts)
- [Development Tools](#development-tools)
- [Smart Contracts](#smart-contracts)
- [Scroll Network](#scroll-network)
- [Ecosystem Projects](#ecosystem-projects)
- [Resources](#resources)
- [Handy Code Snippets](#handy-code-snippets)
- [Contributing](#contributing)

## Introduction

What is Scroll:

- [Scroll Website](https://scroll.io) - The official website for Scroll, a Layer 2 scaling solution for Ethereum using zero-knowledge proofs.

## Getting Started

The no-fluff starter:

- [Scroll Documentation](https://scroll.io/docs) - Official documentation to get you started with Scroll.
- [Scroll Bridge](https://scroll.io/bridge) - Tool for moving assets between Ethereum and Scroll.
- [Scroll Explorer](https://scroll.io/explorer) - Block explorer for the Scroll network.

## Core Concepts

Explanation of fundamental concepts in the Scroll ecosystem:

- [Zero-Knowledge Rollups](https://scroll.io/blog/zkrollup) - An overview of the technology powering Scroll's scaling solution.
- [EVM Equivalence](https://scroll.io/blog/evm-equivalence) - Explanation of how Scroll maintains compatibility with Ethereum.

## Development Tools

Key tools and environments for Scroll:

- [Scroll SDK](https://scroll.io/docs/sdk) - Development kit for building on Scroll.
- [Hardhat Plugin](https://scroll.io/docs/hardhat-plugin) - Hardhat plugin for deploying and testing contracts on Scroll.

## Smart Contracts

How to write and deploy smart contracts on Scroll:

- [Deploying Smart Contracts](https://scroll.io/docs/deploy) - Guide to deploying Ethereum smart contracts on Scroll.
- [Scroll Contract Examples](https://scroll.io/docs/examples) - Example contracts demonstrating Scroll's features.

## Scroll Network

Going into the network level:

- [Scroll Mainnet](https://scroll.io/mainnet) - Information on Scroll's mainnet and how to participate.
- [Scroll Testnet](https://scroll.io/testnet) - Details on Scroll's testnet for development and testing.

## Ecosystem Projects

Cool projects built on Scroll:



...and of course many more - check them out in the EasyA app!

## Resources

Extra stuff:

- [Scroll Blog](https://scroll.io/blog) - Official blog with updates and insights into Scroll development.
- [Scroll GitHub](https://github.com/scroll-tech) - The main repository for Scroll's development.

## Handy Code Snippets

Get a taste of Scroll development with these code snippets:

### Connecting to Scroll

```javascript
const { ethers } = require("ethers");

const provider = new ethers.providers.JsonRpcProvider("https://rpc.scroll.io");
console.log("Connected to Scroll");
```

### Creating a simple fungible token

```solidity
// SPDX-License-Identifier: MIT
pragma solidity ^0.8.0;

import "@openzeppelin/contracts/token/ERC20/ERC20.sol";

contract MyToken is ERC20 {
    constructor(uint256 initialSupply) ERC20("MyToken", "MTK") {
        _mint(msg.sender, initialSupply);
    }
}
```

These examples showcase:
1. How to connect to the Scroll network using ethers.js.
2. A simple ERC20 fungible token contract that can be deployed on Scroll.

## Contributing

We welcome contributions to make this handbook even more legendary! Here's how you can contribute:

1. Fork the repository
2. Create a new branch (`git checkout -b feature/amazing-addition`)
3. Make your changes
4. Commit your changes (`git commit -am 'Add some amazing feature'`)
5. Push to the branch (`git push origin feature/amazing-addition`)
6. Create a new Pull Request

Please ensure your contributions align with our code of conduct and contribution guidelines.

## Credit/Inspiration

This handbook was inspired by the famous awesome lists by sindresorhus. We need awesome lists for Web3 ecosystems, with more of a hacker's guide to how they work. This is the answer to that need.
