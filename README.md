# Bob as Service
NuCypher Bob character implementation as external HTTP Service.

## Description
NuCypher is a decentralized cryptological network offering accessible, intuitive, and extensible runtimes and interfaces for secrets management and dynamic access control.
[![Product Name Screen Shot][product-screenshot]](https://github.com/nucypher/nucypher/raw/main/docs/source/.static/img/nucypher_overview.png)

## Documentation
NuCypher project documentation available at: https://docs.nucypher.com/en/latest/

## Setup
Replace <YOUR PROVIDER URI> with a valid node web3 node provider string, for example:
  - ipc:///home/<username>/.ethereum/geth.ipc - IPC Socket-based JSON-RPC server
  - https://<host> - HTTP(S)-based JSON-RPC server
  -wss://<host>:8080 - Websocket(Secure)-based JSON-RPC server
  
```
provider_uri = <YOUR PROVIDER URI>
```
