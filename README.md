<img src="https://fovo.pages.dev/fovo_1080_black_bg.png" alt="FOVO" width="60">


**FOVO** is a decentralized engagement and advertising platform that enables brands, advertisers, and individuals to create incentivized engagement campaigns. Users earn rewards for completing verified tasks, such as social media interactions and content creation.

| [![Platform](https://img.shields.io/badge/Platform-XION-blue?style=flat-square&logo=ethereum)]([https://](https://ethereum.org/en/developers/docs/evm/))  | [![License](https://img.shields.io/github/license/mtcxdev/AbstraNet?style=flat-square)](LICENSE)  | [![Contributors](https://img.shields.io/github/contributors/vyro-xyz/vyro?style=flat-square)](https://github.com/vyro-xyz/vyro/graphs/contributors) |
|---|---|---|

## Features
- **FOVO Engage** – Earn rewards for completing social media tasks.
- **FOVO Ads** – Transparent and efficient advertising for brands.
- **Non-Custodial Wallets** – Users retain full control over their funds.
- **Smart Contract-Based Rewards** – Automated and transparent payouts.
- **On-Chain Verification** – Ensures immutable task completion tracking.

## Roadmap
-  **->** MVP Development & Smart Contract Deployment
-  Frontend & User Dashboard
-  Testnet Launch & Security Audits
-  Mainnet Launch & Marketing Push
-  Ecosystem Expansion & Partnerships

## Workflow
```mermaid
graph TD;
    %% Advertiser Flow
    A[Advertiser UI - Create Ad] --> B[Campaign Manager - Funds Contract]
    B --> C[Blockchain SC - Escrow & Funds]
    C --> D[Campaign CA - Holds Rewards]
    A --> E

    %% User Engagement Flow
    E[User Engagement - Twitter, IG, YouTube, TikTok] --> F[Event Listener - Twitter, Reddit, Websites, APIs]
    F --> G[Oracle Service - Verifies Data & Sends TX]
    G --> H[Blockchain SC - Logs & Pays Users/Creators]

    %% Connecting Advertiser Flow to User Engagement Flow
    D -->|Funds Rewards| H

```

## Tokenomics

**FOVO** utilizes the XION token as its native utility token. It will be used to fund ad campaigns and as payment for rewards


## Links
- [FOVO Whitepaper ->](https://fovo.pages.dev/whitepaper.pdf)
- [Website ->](https://fovo.mtcx.dev)
- [Collaborate ->](https://discord.com/users/mtcxdev)
- [Inquire ->](mailto:toogun@mtcx.dev)

## License
Vyro is licensed under the MIT License. See [LICENSE](LICENSE) for details.
