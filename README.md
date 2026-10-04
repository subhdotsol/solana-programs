# Solana Programs

A collection of Solana programs exploring on-chain systems, program architecture, DeFi primitives, account models, cryptography, and low-level Solana development.

This repository is an index of my Solana work. Each program is maintained as an independent repository and included here as a Git submodule.

## Structure

The following programs are currently included:

| Directory | Program | Description | Implementation |
| --------- | ------- | ----------- | -------------- |
| `anchor-amm` | AMM Sandbox | Constant-product market maker with liquidity deposits, swaps, and withdrawals | Anchor |
| `pinochhio-amm` | Pinocchio AMM | Constant-product AMM written in Pinocchio, benchmarked against the Anchor implementation | Pinocchio |
| `encrypted-calculator` | Encrypted Calculator | Arithmetic over encrypted inputs via Arcium confidential computing | Anchor / Arcium |
| `anchor-escrow` | Escrow | Trustless token exchange between two parties via a PDA vault | Anchor |
| `pinochhio-escrow` | Pinocchio Escrow | Optimized token escrow with atomic swaps and safe refunds | Pinocchio |
| `anchor-multisig-vault` | Multi-Sig Vault | M-of-N signature treasury for proposals and withdrawals | Anchor |
| `pinocchio-vault` | SOL Vault | Deposit and withdraw native SOL from a PDA vault | Pinocchio |
| `anchor-vault` | Pre-Req Vault | Per-user SOL vault with external registration CPI | Anchor |
| `sbpf-time-locked-vault` | Time-Locked Vault | Slot-based time lock written directly in sBPF assembly | sBPF Assembly |
| `quasar-staking-contract` | Staking | Time-locked staking with linear rewards | Quasar |
| `guestbook-contract` | Guestbook | On-chain guestbook for creating, updating, and deleting messages | Anchor |
| `anchor-calc-contract` | Calculator | Initialize a number, then double or add to it on-chain | Anchor |
| `name-storage-contract` | Name Storage | Store and update a name string using Borsh, written natively without Anchor | Native |
| `nft-staking-contract` | NFT Staking | Stake NFTs to earn rewards with configurable lockup periods | Anchor |

## Program Directory

The full categorized repository index lives in [PROGRAMS.md](programs.md).

## Setup

Clone the repository with submodules:

```sh
git clone --recurse-submodules <repository-url>
```

Or, if already cloned without submodules:

```sh
git submodule update --init --recursive
```

## Contributing

This repository is primarily a personal index of separate program repositories. Bug reports and suggestions are welcome as issues.
