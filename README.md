# 👋 Introduction

The following will help you get everything you need for your development environment to actually deploy the contracts to a tesnet

```dotenv
ALCHEMY_API_URL=the api url given to you by alchemy after you've created an app
RINKEBY_ACCOUNT_KEY=the exported private key of the wallet address which has faucet tokens on it
```

# 🚀 Deployment: Alchemy

So, when we want to perform an action that changes the blockchain we call it a transaction. For example, sending someone ETH is a transaction because we're changing account balances. Doing something that updates a variable in our contract is also considered a transaction because we're changing data. Minting an NFT is a transaction because we're saving data on the contract.

Deploying a smart contract is also a transaction.

Remember, the blockchain has no owner. It's just a bunch of computers around the world run by miners that have a copy of the blockchain.
When we deploy our contract, we need to tell all those miners, "hey, this is a new smart contract, please add my smart contract to the blockchain and then tell everyone else about it as well".

This is where [Alchemy](https://dashboard.alchemyapi.io) comes in.

Alchemy essentially helps us broadcast our contract creation transaction so that it can be picked up by miners as quickly as possible. Once the transaction is mined, it is then broadcasted to the blockchain as a legit transaction. From there, everyone updates their copy of the blockchain.

# 🔧 Misc

- Solidity
  - [solidity by example](https://solidity-by-example.org/)
- NFT Metadata Storage Tools
  - [intro](https://artynft.io/nft-granny/where-is-nft-art-stored/)
  - [nft storage](https://nft.storage/)
- [base64](https://www.utilities-online.info/base64)
- svgs
  - [svg-viewer](https://www.svgviewer.dev/)
  - [docs](https://developer.mozilla.org/en-US/docs/Web/SVG/Tutorial)
