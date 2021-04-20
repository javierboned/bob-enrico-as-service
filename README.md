# Bob as Service
NuCypher Bob character implementation as external HTTP Service.

## Description
NuCypher is a decentralized cryptological network offering accessible, intuitive, and extensible runtimes and interfaces for secrets management and dynamic access control.

<a href="https://ibb.co/WzHg0p7"><img src="https://i.ibb.co/n1wzB84/Captura-de-pantalla-2021-04-20-a-las-9-37-20.png" alt="Captura-de-pantalla-2021-04-20-a-las-9-37-20" border="0"></a>

This project implements an HTTP API in Python using Flask framework that aims to simulate the Bob character in the NuCypher network eliminating data persistence and trying to simulate as best as possible a client-side implementation of NuCypher (JavaScript).

## API Routes

## Documentation
NuCypher project documentation available at: https://docs.nucypher.com/en/latest/

## Setup
First, replace <YOUR PROVIDER URI> with a valid node web3 node provider string, for example:
  - ipc:///home/<username>/.ethereum/geth.ipc - IPC Socket-based JSON-RPC server
  - https://<host> - HTTP(S)-based JSON-RPC server
  -wss://<host>:8080 - Websocket(Secure)-based JSON-RPC server

```Python
provider_uri = <YOUR PROVIDER URI>
```

