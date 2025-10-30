---
title: Pinet - Cross-Chain DeFi for P2P Green Energy Trading
grant-application: true
---

# Pinet

## Team

**Contact Person**: Alireza Hajimohammadi(AR.H) (CTO)  
**Email**: pinetworkinton@outlook.com  
**Company/Legal Entity**: Pinet (Baku, Azerbaijan)  
**Team Members**: 
- Tyler Strom (CEO): MSc in AI-Based Energy Development; led Siemens Energy AI projects for grid optimization. 
- AR.H (CTO): Smart contract specialist; deployed DeFi protocols at ConsenSys . 
**Advisors**: 
- Francisco Benedito (Founder, ClimateTrade): Sustainability scaling.
- J. Christopher Giancarlo (Ex-CFTC Chairman): Regulatory guidance.
- Stijn Ponnet (Founder, Legion Network): Blockchain infra.
- Jay Kurahashi-Sofue (VP Marketing, Ava Labs): Ecosystem growth.
**Website**: https://pinetworkinton.free.nf  
**Twitter/X**: https://x.com/pinetworkinton  
**GitHub**: https://github.com/pinetworkinton (Private; open-source post-audit)

## Previous Applications

No previous applications to Web3 Foundation. Recent submissions: BNB Chain Grants ($25K, Oct 2025), Solana Foundation ($25K, Oct 2025), Arbitrum Audit Subsidy ($15K, Oct 2025).

## How did you hear about the Grants Program?

Web3 Foundation Website and crypto grants lists (e.g., var-meta.com/blog/50-web3-crypto-grants-2025); recommendations from Ethereum/Solana communities on X/Reddit.

## Referrer

N/A (Self-referred via ecosystem research)

## Motivation

The global energy market ($8.8T in 2024, projected $12T by 2030) faces inefficiencies: 30% transmission losses, opaque REC (Renewable Energy Certificate) trading, and centralized grids hindering small producers. Pinet builds a decentralized P2P marketplace to tokenize kWh/RECs, enabling direct trades with 70% cost reduction. Polkadot's cross-chain interoperability (via XCM/bridges) is ideal for our multi-chain architecture (Polygon/BNB/Solana + Polkadot parachains), fostering RWA tokenization and sustainability. This aligns with Web3F's public goods focus by open-sourcing energy DeFi tools, onboarding non-crypto users (solar producers), and boosting Polkadot TVL in green verticals. Traction: 2,500+ airdrop users, $1.15M presale raised.

## Technical Details

**Stack**: Solidity/Rust smart contracts (ERC-20 PNTE token compatible with Polkadot via bridges); IoT oracles (Chainlink-like for real-time energy data); IPFS for storage; AI (TensorFlow) for demand forecasting.  
**Architecture**: Multi-chain deployment (Polkadot parachain integration for cross-chain settlements); Escrow contracts for P2P trades (createShipment → approve → confirm → attest); Staking module (12-15% APR).  
**Security**: Third-party audit planned (Certik); Multi-sig treasury.  
**Demo**: Testnet video on Polygon: 
https://youtu.be/Px2K72O8RC4
(Successful execution of energy trading flow).  
**Tokenomics**: 1B PNTE total supply; 60% presale (600M, ongoing), 20% team (locked 24 months), 10% rewards/airdrop, 10% ecosystem. Utility: Payments, staking, governance.  
**Open Source**: Yes, full codebase post-grant (GitHub repo with Polkadot-specific bridge code).

## Roadmap & Milestones

| Milestone | Deliverable | Timeline | Budget Allocation |
|-----------|-------------|----------|-------------------|
| **1: Polkadot Bridge & Audit** | Deploy PNTE bridge to Polkadot parachain; Certik audit of escrow/staking contracts; 100 test XCM transactions. Metrics: GitHub repo public (50+ stars), on-chain verification via Subscan. | Q1 2026 (2 months) | $10,000 (Audit $7K, gas/dev $3K) |
| **2: P2P Trading Features** | Live escrow marketplace on Polkadot DEX (e.g., HydraDX LP for PNTE/DOT); IoT oracle integration for REC trades. Metrics: 3,000 users migrated, $100K TVL seeded. | Q2 2026 (2 months) | $10,000 (LP seed $6K, integration $4K) |
| **3: Staking & Community Adoption** | Staking/rewards live (12-15% APR); Zealy quests and Polkadot hackathon demo. Metrics: 5,000 total users, $500K TVL, 20% engagement (trades/votes). | Q3 2026 (2 months) | $5,000 (Marketing $3K, bounties $2K) |

Total: $25,000 USD (50% DOT vesting preferred; remainder USDC). Verification: On-chain metrics, GitHub commits, quarterly reports.

## Budget Justification

$25K covers audit/integration for Polkadot-specific features; self-funded presale ($1.15M treasury) handles core dev. No overlap with prior bootstrapping ($50K seed). All open-source.

## Additional Information

- **Risks/Mitigation**: Regulatory (KYC via advisors); Scalability (Polkadot sharding); Adoption (Community bounties with 2,500 existing users).
- **Sustainability**: Post-grant revenue from 1% trade fees to ecosystem fund.
- **Examples Alignment**: Similar to DeFi/RWA grants (e.g., Example 2: Cross-chain bridges; Example 4: Public goods tooling).

## Technical Details

**Stack**: Solidity/Rust smart contracts (ERC-20 PNTE token compatible with Polkadot via bridges); IoT oracles (Chainlink-like for real-time energy data); IPFS for storage; AI (TensorFlow) for demand forecasting.  
**Architecture**: Multi-chain deployment (Polkadot parachain integration for cross-chain settlements); Escrow contracts for P2P trades (createShipment → approve → confirm → attest); Staking module (12-15% APR).  
**Security**: Third-party audit planned (Certik); Multi-sig treasury.  
**Demo**: Successful testnet demonstration on Polygon Youtube:(https://youtu.be/Px2K72O8RC4). The video showcases full deployment and execution of Pinet's smart contracts, including PNTE token minting, P2P escrow transactions (e.g., shipment creation and confirmation), and staking setup – all with verified outputs, no errors, and on-chain logs confirming functionality (timestamps: 0:45 deploy, 2:30 test tx, 4:15 success verification). This proves robust testnet performance ready for Polkadot bridge.  
**Tokenomics**: 1B PNTE total supply; 60% presale (600M, ongoing), 20% team (locked 24 months), 10% rewards/airdrop, 10% ecosystem. Utility: Payments, staking, governance.  
**Open Source**: Yes, full codebase post-grant (GitHub repo with Polkadot-specific bridge code).
We commit to Web3F Terms & Conditions and open-source deliverables.
