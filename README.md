![Open Source at Simplio](https://raw.githubusercontent.com/SimplioOfficial/.github/master/github-logo-chest.png) 

## Overview

Simplio is a friendly multichain mobile app that lets players instantly start playing Web3 games, purchase tokens & NFT’s for FIAT and provide easy swaps among gaming assets & blockchains.

## Project integration

If you are looking for project integration, please apply [here](https://simplio.io/apply) .

## Supported chains

`Ethereum`, `Binance Smart Chain`, `Polygon`, `Avalanche` (WIP: Solana, Cosmos, Polkadot, Near)

## How to integrate with Simplio

To interact with your dApp, Simplio is using standard Wallet Connect extension. For succesfull integration, your dApp needs to follow these instructions: 

### dApp integration instructions - Wallet Connect v1

1. Integrate Wallet Connect v1 with your dApp: https://docs.walletconnect.com/quick-start/dapps/client
2. Be sure your dApp supports these methods: https://docs.walletconnect.com/client-api
3. Don´t forget to fill all `clientMeta` informations such as `name` or `icons` of your project.
4. Always send `chainId` parameter in session request.
5. Be sure you are sending `eth_sign` (Sign Message) with correct parameters, otherwise we are not able to decode it on our end.

### dApp integration instructions - Wallet Connect v2

Under development :rocket:
