# Useful random contracts
Collection of CosmWasm smart contracts that may be useful for someone someday


## Transaction Size

Tests the block capacity and gas fee of the chain:

```bash
# Deploy
terrain deploy transaction-size --network testnet

# Execute store data
terrain task:run do-large-transaction --network testnet
```