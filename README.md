# Awesome-Oracle-Network

## Top Oracle Networks Ecosystem
**Curated List of Production Networks & Open-Source GitHub Projects**
*Focused on Blockchain Oracles, Price Feeds, Real-World Data, Decentralized Computation & Cross-Chain Data Delivery*
**Last updated: August 2026**

This repository tracks notable **production oracle networks** and **open-source projects** for **Blockchain Oracles**. These systems securely bring off-chain data (prices, events, randomness, reserves, custom APIs) on-chain so smart contracts can react to the real world.

**Examples** include Chainlink, Pyth Network, API3, RedStone, Supra, UMA Optimistic Oracle, Band Protocol, DIA, Tellor, and Witnet (the category leaders).

**Open-source emphasis**: Most major oracle networks publish substantial open-source code (node software, contracts, SDKs). In addition, pure open protocols and research implementations provide transparent alternatives and building blocks. This section is expanded with the core open repositories and related projects.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms
*(Production oracle networks and managed services — many with open-source components)*

- **[Chainlink](https://chain.link/)**  
  The most widely adopted decentralized oracle network, providing price feeds, Data Streams, VRF, CCIP cross-chain messaging, Functions, Proof of Reserve, and a broad services stack securing a large share of DeFi TVS.

- **[Pyth Network](https://pyth.network/)**  
  High-frequency, first-party price oracle using a pull model. Strong for low-latency market data across many chains, including equities, FX, and crypto.

- **[API3](https://api3.org/)**  
  First-party oracle solution (Airnode + dAPIs) that lets API providers run their own oracle nodes, with focus on reducing middlemen and OEV (oracle extractable value) recapture.

- **[RedStone](https://redstone.finance/)**  
  Modular, gas-efficient oracle with push and pull delivery models, particularly strong for emerging assets (LSTs, LRTs, yield-bearing collateral) and flexible integration patterns.

- **[Supra](https://supraoracles.com/)**  
  Multi-chain oracle network focused on speed, security, and broad data coverage for DeFi and other on-chain applications.

- **[UMA Optimistic Oracle](https://uma.xyz/)**  
  Optimistic oracle designed for arbitrary and subjective data (prediction markets, insurance, custom claims) resolved via economic dispute mechanisms.

- **[Band Protocol](https://bandprotocol.com/)**  
  Cross-chain data oracle platform that aggregates real-world data and APIs for smart contracts, operating with its own chain and validator set.

- **[DIA](https://www.diadata.org/)**  
  Open-source oracle platform providing transparent, customizable price feeds and market data with on-chain and off-chain delivery options.

- **[Tellor](https://tellor.io/)**  
  Permissionless, transparent oracle protocol where reporters stake and compete to provide data, secured by crypto-economic incentives and disputes.

- **[Witnet](https://witnet.io/)**  
  Decentralized, permissionless oracle network with strong crypto-economic guarantees for bringing real-world data and events on-chain.

## Open-Source GitHub Projects
- **[Chainlink core & node software](https://github.com/smartcontractkit/chainlink)**  
  Open-source node implementation, contracts, and tooling for the Chainlink decentralized oracle network (price feeds, VRF, CCIP, Functions, etc.).

- **[Pyth Network open repositories](https://github.com/pyth-network)**  
  Open-source components for Pyth’s price feeds, publishers, and on-chain consumers across multiple ecosystems.

- **[API3 / Airnode](https://github.com/api3dao)**  
  Open-source first-party oracle stack (Airnode) that allows API providers to run their own oracle nodes and publish dAPIs.

- **[RedStone protocol & connectors](https://github.com/redstone-finance)**  
  Open-source modular oracle implementation supporting flexible data delivery models and extensive asset coverage.

- **[UMA protocol & Optimistic Oracle](https://github.com/UMAprotocol)**  
  Open-source contracts and tooling for UMA’s optimistic oracle and related financial contracts.

- **[Band Protocol open components](https://github.com/bandprotocol)**  
  Open-source oracle node, contracts, and cross-chain data delivery tooling.

- **[DIA open oracle platform](https://github.com/diadata-org)**  
  Transparent, open-source oracle infrastructure for customizable price feeds and market data.

- **[Tellor core protocol](https://github.com/tellor-io)**  
  Fully open-source, permissionless oracle contracts and reporter tooling secured by staking and dispute mechanisms.

- **[Witnet (witnet-rust & ecosystem)](https://github.com/witnet)**  
  Open-source Rust implementation of the Witnet decentralized oracle protocol, including full node, bridges, and related libraries.

- **[Additional open oracle experiments & adapters](https://github.com/)**  
  Community and research projects implementing custom oracles, Chainlink-compatible interfaces, VRF libraries, and specialized data feeds (e.g., fee data, custom indices).

### Additional Strong Open-Source Options
- Running your own Chainlink, Tellor, or Witnet nodes to participate in decentralized data provision.
- Building custom first-party oracles with Airnode or similar open frameworks.
- Using open aggregation and medianizer contracts for multi-source price security.
- Integrating multiple open oracle sources (defense in depth) inside smart contracts.
- Research implementations of optimistic, Schelling-point, and commit-reveal oracle designs.
- Local development and testing tools (Hardhat/Foundry starter kits) published by major oracle projects.

**Frameworks for building custom systems**: For most production DeFi and RWA applications, integrate battle-tested open networks (Chainlink, Pyth, RedStone, etc.) via their open contracts and SDKs. For fully custom or highly specialized data, combine open first-party stacks (Airnode), permissionless protocols (Tellor, Witnet), or optimistic designs (UMA) with your own aggregation and dispute logic. Always prefer open, auditable contracts and multi-source designs where security is critical. Managed network services and enterprise support from the major providers remain valuable for operational reliability and broad asset coverage at scale.

## How to Contribute
1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's a production network or open-source project.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer
- This is a **community-curated** list — not exhaustive and not an endorsement.
- Oracles are critical infrastructure: incorrect or manipulated data can cause catastrophic smart-contract losses. Open-source code improves transparency and auditability but does not eliminate economic, operational, or governance risks. Always review security models, node decentralization, update frequency, dispute mechanisms, and audit reports before relying on any oracle for significant value.
- Smart-contract and blockchain development carries inherent risks. Use at your own risk and follow security best practices (multiple sources, circuit breakers, time-weighted averages, etc.).

---
**Made for smart-contract developers, DeFi protocols, and infrastructure teams connecting blockchains to real-world data.**
Let's keep oracle infrastructure transparent, decentralized, and community-auditable.
