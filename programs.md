# Programs

This file is the complete index of programs in this repository. Browse by category or use the quick links below.

- [DeFi](#defi)
- [Core Concepts](#core-concepts)
- [NFTs and Tokens](#nfts-and-tokens)
- [Data Structures](#data-structures)
- [Games](#games)
- [Privacy and Security](#privacy-and-security)

## DeFi

| Program | Description | Implementations | Features |
| --- | --- | --- | --- |
| AMM | Constant-product market maker with liquidity deposits, swaps, and withdrawals | [Anchor](anchor-amm), [Pinocchio](pinochhio-amm) | `AMM` `Constant Product` `Liquidity` |
| Escrow | Trustless token exchange between two parties via a PDA vault | [Anchor](anchor-escrow), [Pinocchio](pinochhio-escrow) | `Escrow` `Atomic Swap` `PDA` `Refund` |
| SOL Vault | Deposit and withdraw native SOL from a PDA vault | [Pinocchio](pinocchio-vault), [Anchor](anchor-vault) | `Deposit` `Withdraw` `PDA` |
| Multi-Sig Vault | M-of-N signature treasury for proposals and withdrawals | [Anchor](anchor-multisig-vault) | `Multi-Sig` `Treasury` `Proposal` |
| Time-Locked Vault | Slot-based time lock written directly in sBPF assembly | [sBPF](sbpf-time-locked-vault) | `Time Lock` `Assembly` `PDA` |
| Staking | Time-locked staking with linear rewards | [Quasar](quasar-staking-contract) | `Staking` `Rewards` `Lockup` |

## Core Concepts

| Program | Description | Implementations | Features |
| --- | --- | --- | --- |
| Guestbook | On-chain guestbook for creating, updating, and deleting messages | [Anchor](guestbook-contract) | `CRUD` `PDA` `Messages` |
| Calculator | Initialize a number, then double or add to it on-chain | [Anchor](anchor-calc-contract) | `Calculator` `Arithmetic` `State` |
| Name Storage | Store and update a name string using Borsh, written natively without Anchor | [Native](name-storage-contract) | `Borsh` `Native` `State` |

## NFTs and Tokens

| Program | Description | Implementations | Features |
| --- | --- | --- | --- |
| NFT Staking | Stake NFTs to earn rewards with configurable lockup periods | [Anchor](nft-staking-contract) | `NFT` `Staking` `Rewards` `Lockup` |

## Data Structures

| Program | Description | Implementations | Features |
| --- | --- | --- | --- |

## Games

| Program | Description | Implementations | Features |
| --- | --- | --- | --- |

## Privacy and Security

| Program | Description | Implementations | Features |
| --- | --- | --- | --- |
| Encrypted Calculator | Arithmetic over encrypted inputs using Arcium MPC | [Anchor](encrypted-calculator) | `Arcium` `Confidential Computing` `MPC` `X25519` |
