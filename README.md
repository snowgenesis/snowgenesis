# SnowGenesis

Infrastructure and tooling for subnets on Avalanche

## Repositories

### sgs-contracts
`Registrar` contract for managing subnet creation from the Avalanche C-Chain. Also contains various tooling for monitoring subnet statuses and running simulations.

### sgs-frontend
UI for the subnet creator and the block explorer

### sgs-processor
Listens to Registrar contract events and processes the creation of subnets and blockchains. Adds our validators to the subnet validator set. Also monitors subnet validations that are about to expire and automatically re-validators.

## Code has not yet been open-sourced
