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
- [SaaS/Hosted Platforms](#saashosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms
*(Production oracle networks and managed services — many with open-source components)*

| Platform | Description | Starting Pricing | Free Tier Limits |
| :--- | :--- | :--- | :--- |
| **[Chainlink](https://chain.link/)** | Decentralized oracle network providing price feeds, Data Streams, VRF, CCIP cross-chain messaging, Functions, and Proof of Reserve. | From ~$0.005–$0.20 per request (LINK token subscription for VRF/Functions) or gas-only for standard on-chain feeds; Data Streams from $500/month | Free forever reading of public sponsored price feeds (protocol-subsidized, user pays network gas only); 5 LINK/day testnet faucet allocation |
| **[Pyth Network](https://pyth.network/)** | High-frequency, first-party price oracle using a pull model for low-latency market data across equities, FX, commodities, and crypto. | From ~$0.0001 per on-chain price update (target chain fee) / Dedicated Hermes node endpoints from $50/month | Free forever public Hermes API tier limited to 10 requests every 10 seconds per IP (90 req / 10s for TradingView endpoint); unlimited testnet usage |
| **[API3](https://api3.org/)** | First-party oracle solution (Airnode + dAPIs) connecting data providers directly to smart contracts with OEV recapture. | From ~$299/feed/year for managed dAPIs or self-funded proxy gas (~$0.01–$0.05 per update) | Free forever open-source Airnode (self-hosted with 0 protocol fees); unlimited read access to sponsored public dAPIs & testnet feeds |
| **[RedStone](https://redstone.finance/)** | Modular, gas-efficient oracle supporting Core (pull calldata injection), Classic (push cache), and X (front-running prevention) models. | From ~$0.001–$0.05 gas overhead per pull request (calldata injection); enterprise bespoke feeds from $500/month | Free forever for RedStone Core pull data packages via decentralized cache nodes / Showroom; unlimited access on testnets |
| **[Supra](https://supraoracles.com/)** | Multi-chain decentralized oracle network and dVRF platform with cross-chain communication and fast finality. | From ~$0.01 per request (credits pegged in USDC via $SUPRA staking from 1,000 SUPRA minimum) | 6-month free trial via SNAP (Supra Network Activate Program) offering 100% subsidized oracle & dVRF calls for eligible projects; unlimited testnet faucet |
| **[UMA Optimistic Oracle](https://uma.xyz/)** | Optimistic oracle for subjective and arbitrary data (prediction markets, insurance, custom claims) resolved via economic dispute mechanisms. | Minimum assertion bond / `finalFee` starting at ~0.0001 ETH (~$0.25–$1.00 in collateral) refunded upon finalization | Free forever to query resolved assertions; 100% bond refund for correct assertions without disputes + testnet faucet with unlimited test assertions |
| **[Band Protocol](https://bandprotocol.com/)** | Cross-chain decentralized data oracle platform aggregating real-world data and APIs via BandChain validators. | From ~$0.005–$0.01 per query (paid in BAND tokens to validators for data fetching/relaying) | Free forever reading of Band Standard Dataset price feeds cached on supported chains; unlimited BandChain Laozi testnet queries |
| **[DIA](https://www.diadata.org/)** | Multi-chain open-source oracle platform providing transparent, customizable price feeds and market data. | From ~$99/month for standalone REST API / $250/month for custom on-chain production feeds | Free forever evaluation REST API (limited to specific test asset endpoints for evaluation); free access to testnet oracles |
| **[Tellor](https://tellor.io/)** | Permissionless, transparent oracle protocol where reporters stake TRB and compete to provide data on-demand. | From ~0.001 TRB (~$0.05) minimum tip per on-demand data request + transaction gas | Free forever reading of existing Enshrined Feeds (e.g., ETH/USD, BTC/USD) without tipping; unlimited reporter requests on testnets |
| **[Witnet](https://witnet.io/)** | Decentralized, permissionless oracle network with strong crypto-economic guarantees for bringing real-world data and events on-chain. | From ~$0.005–$0.02 (1 WIT / bridge gas equivalent) per custom RAD (Retrieve-Attest-Deliver) request | Free forever reading of sponsored public price feeds via Witnet Price Feeds Router; unlimited testnet requests |

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
