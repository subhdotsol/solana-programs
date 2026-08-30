# Solana Programs

A collection of Solana programs exploring on-chain systems, program architecture, DeFi primitives, account models, cryptography, and low-level Solana development.

This repository is an index of my Solana work. Each program is maintained as an independent repository and included here as a Git submodule.

## Structure

| Directory | Program | Description | Language |
| --------- | ------- | ----------- | -------- |
| `anchor-amm` | AMM Sandbox | Constant-product automated market maker with liquidity deposits, swaps, and withdrawals | Anchor / Rust |

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
