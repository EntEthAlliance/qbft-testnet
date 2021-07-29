# Disclaimer

WARNING: THIS IS A DEVELOPMENT AND DEMONSTRATION PROJECT.

PLEASE DO NOT USE ANY OF THE MATERIAL, ESPECIALLY KEYS, IN PRODUCTION.

# Services

## Blockchain clients
The network will consist of 7 Enterprise Ethereum clients. Please consult the EEA Client Spec for more information (TODO link).

This example runs 3 GoQuorum nodes and 4 Besu nodes, working together using the QBFT consensus algorithm.

Each node is assigned its own identifier and will work with all other nodes on the network.

Nodes will expose their JSON-RPC API in full. One of the Besu nodes will map port 8545 to the host port.

## Private enclaves

Each blockchain node will be complemented with a private enclave.

Please refer to the private enclave specification for more information (TODO link)

We use the Tessera private enclave in this example.

## Additional services

### Block explorer

### Faucet

### Remix with Quorum addon
