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

- [Scroll Documentation](https://docs.scroll.io/en/home/) - Official documentation to get you started with Scroll.
- [Scroll Developers](https://docs.scroll.io/en/developers/) - Dev docs

## Core Concepts

Explanation of fundamental concepts in the Scroll ecosystem:

- [Scroll Architecture](https://docs.scroll.io/en/technology/) - Scroll's Architecture.
- [EVM Differences](https://docs.scroll.io/en/technology/chain/differences/) - Explanation of how Scroll is different from Ethereum.

## Development Tools

Key tools and environments for Scroll:

- [Hardhat](https://docs.scroll.io/en/developers/developer-quickstart/#hardhat) - Hardhat configs for deploying and testing contracts on Scroll.

## Smart Contracts

How to write and deploy smart contracts on Scroll:

- [Smart Contracts](https://docs.scroll.io/en/developers/scroll-contracts/) - Guide to smart contracts on Scroll.

## Scroll Network

Going into the network level:

- [Scroll Explorer](https://scroll.io/rollupscan) - Rollup Explorer

## Ecosystem Projects

Cool projects built on Scroll:

- [Scroll Ecosystem](https://scroll.io/ecosystem) - Projects live on Scroll.

## Resources

Extra stuff:

- [Scroll Nodes](https://docs.scroll.io/en/developers/guides/running-a-scroll-node/) - How to run a node.

## Handy Code Snippets

Get a taste of Scroll development with these code snippets:

### Configuring Hardhat

```javascript
...
//
// Select the network you want to deploy to here:
//
const defaultNetwork = "scrollSepolia";
...
module.exports = {
...
  networks: {
...
          scrollSepolia: {
            url: "https://sepolia-rpc.scroll.io/",
            accounts: {
              mnemonic: mnemonic(),
            },
          },
  }
...
}
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
1. How to configure Hardhat.
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
