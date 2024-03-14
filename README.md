# Count DRACULA How to Deploy Solana Token in 5 min!

In this project, you will learn how to create and deploy your own token on the Solana blockchain. The steps include obtaining a Solana devnet API key, creating a wallet, uploading token information to IPFS, and deploying your token.

## Getting Started

### Prerequisites

- Node.js and npm must be installed. You can download the latest version from the [Node.js download page](https://nodejs.org/).
- If TypeScript and ts-node are not installed, use the following commands to install them globally:

```javascript
  npm install -g typescript
  npm install -g ts-node
```


### Obtain a Solana Devnet API Key

1. Go to QuickNode and obtain a Solana devnet API key. This is necessary for performing blockchain transactions in your project.

### Project Setup

1. Clone or download this guide.
2. Go to the project directory and install dependencies:

```javascript
  npm install
```


## Creating a Wallet and Uploading Token Information to IPFS

1. Open the `wallet.ts` file and enter your Solana devnet API key obtained from QuickNode.
2. Visit [NFT.Storage](https://nft.storage/) and upload your token information and image to IPFS. This will be used to store the metadata of your token.
3. Run `ts-node wallet.ts` to create a new wallet. You will receive an output:


```javascript
  Wallet PrivateKey: <Your_Wallet's_Private_Key>
  Wrote secret key to guideSecret.json.
```


This output indicates that your wallet's private key has been generated and written to the `guideSecret.json` file.

## Deploying the Token

1. Open the `mint.ts` file and enter your token information and token supply value between lines 13 and 23.
2. Run `ts-node mint.ts` to deploy your token. You will receive an output indicating a successful deployment:

```javascript
Successfully Deployed and Minted Token! (Your_Token_ID)
```

This output confirms that your token has been successfully deployed and minted. You can use your Token ID to check the transaction on [Solscan](https://solscan.io/) in the Solana devnet.

## Social Links

- **Website:** [Dracula Project](https://www.dracula.wtf/)
- **Twitter:** [Follow us on Twitter](https://twitter.com/countdraculasol)
- **Telegram:** [Join our Telegram](https://t.me/countdraculasol)


