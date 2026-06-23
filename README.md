# Solana Prettier config

> [!WARNING]
> **This package is deprecated.** It has been replaced by
> [`@solana-config/prettier`](https://github.com/solana-foundation/js-configs),
> part of the [`@solana-foundation/js-configs`](https://github.com/solana-foundation/js-configs)
> monorepo. Please migrate to the new package; this one will no longer receive updates.

Let's share this Prettier config across all of our projects, to keep things consistent.

## Installation

1. Install this package in the target project, along with the required peer dependencies
   ```bash
   pnpx install-peerdeps@2 --pnpm --dev @solana/prettier-config-solana
   ```
2. Add a reference to this module in your `package.json`
   ```json
   "prettier": "@solana/prettier-config-solana"
   ```
