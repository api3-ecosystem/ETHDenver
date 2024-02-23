# API3 x ETH Denver :hammer:
Hackers, we hope you are excited for the ETH Denver Hackathon! We are looking forward to seeing what you build.

[![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](https://choosealicense.com/licenses/mit/)

## API3 Bounties

### 🥇 Build a modification on a borrow/lending dapp to reallocate liquidation profits using API3’s OEV network - $5000

Modify an existing dapp to distribute profits using your logic.  Currently, liquidation profits get lost to MEV bots.  Using the OEV network (Oracle Extractable Value), create a way to redistribute the profits. [API3 Market](https://market.api3.org/dapis?utm_source=Eth+Istanbul&utm_medium=Github&utm_campaign=Eth+Istanbul).

Project Ideas:
- Fund publics goods by auto distributing through a smart contract. MEV for good, share of a portion of the profits to support open source projects
- Reward current stakers of the dapp with a bonus.  Give an increase of percentage of return to attract users to your dapp. 
- Lower the penalty of the liquidation. Attract more borrowers to your dapp by having a smaller penalty on liquidations

Example Repo: [How to bid in the auction to update a price feed](https://github.com/api3-ecosystem/oev_priceupdate_example) 

### 🥇 Maximize your profit of the OEV (Oracle Extractable Value) share - $6000

API3 will be hosting a liquidable position with a controlled dAPI price feed that will be lowering value over time to increase the profit position of the liquidation.  Maximize your strategy to win the price update auction and execute the liquidation with the most profit.

Example Repo: [How to bid in the auction to update a price feed](https://github.com/api3-ecosystem/oev_priceupdate_example) 


## Important information

You will need ETH on both ETH Sepolia and the OEV Network for full functionality.

Only a small amount of ETH is needed for bids and transactions costs on the OEV Network. 

You can request OEV Network ETH in the [API3 discord](https://discord.gg/api3dao) within the `ECOSYSTEM TALK =>  OEV Section` [API3 Discord](https://discord.gg/api3dao):

To add the OEV Network to you metamask, please add the following network details:
```
- Network Name: OEV Sepolia Testnet

- RPC URL: https://oev-network-sepolia-testnet-rpc.eu-north-2.gateway.fm

- Chain ID: 736160594

- Currency symbol: ETH

- Block explorer URL: https://oev-network-sepolia-testnet-blockscout.eu-north-2.gateway.fm
```

Once the API3 has sent the OEV ETH, you can check your wallet to verify that you have some ETH on the OEV network.


### Lending Dapp to monitor:  
- https://api3-oev-playground.vercel.app/markets

#### ETH Sepolia Network:
```
- OEVT Proxy: 0xFc345f8D73cA316D8f05BD7E4B42Ddd1e28dDfEc (Price Oracle to update)
- OEVT Token address: 0x5Df761cB11aEd75618a716e252789Cdc9280f5A6
- USDC Token Address - 0x3D5ebDbF134eAf86373c24F77CAA290B7A578D7d  *Faucet
- Lending Pool: 0xEeEed4f0cE2B9fe4597b6c99eD34D202b4C03052 (read userAccountData)
- AaveOracle: 0x97F4B0E84A589e0b4581d74734e3B2Cc7741D093 (check Oracle Price)
```
In order to pay back loans, you will need to pay in this USDC token.  This faucet requires 0.01 Sepolia ETH to claim 10,000 USDC [Tokens Faucet]("https://sepolia.etherscan.io/address/0x3D5ebDbF134eAf86373c24F77CAA290B7A578D7d#writeContract")

#### OEV network:
```
Auctioneer Address: 0x34f13A5C0AD750d212267bcBc230c87AEFD35CC5
```

## Introduction to API3

First-party oracles provide a more secure and reliable oracle, whilst enabling dApps to verify the data source. API3's first-party oracles are powered by Airnode, a serverless oracle node that enables API providers to run their own oracle nodes.
You can [learn more about first-party oracles](https://docs.api3.org/guides/airnode/calling-an-airnode/?utm_source=Eth+Istanbul&utm_medium=Github&utm_campaign=Eth+Istanbul) within the API3 Documentation.


##  Oracle Extractable Value - The OEV Network
The OEV network allows external users to bid to update price feeds for potential gain in profit.  Bids are done on the OEV network and updates to price feeds are done on the requested chain.

Example Repo: [How to bid in the auction to update a price feed](https://github.com/api3-ecosystem/oev_priceupdate_example) 

## Tutorials: 

Example Repo: [How to bid in the auction to update a price feed](https://github.com/api3-ecosystem/oev_priceupdate_example) 


## Community link

Looking for help or just want to hang with industry-leading developers? Head to the API3 Discord and drop questions in the #dev-support channel: https://discord.gg/api3dao

## Submission Requirements

All hackathon participants who are competing for the API3 bounties are required to submit a project that meets the following requirements:

- The project should be submitted to ETH Denver Hackathon 2024 by the deadline.
- Use of API3’s OEV Network that facilitates a proper use-case.
- The project should be live with a working frontend deployed.
- The project should be open-source with a public Github repository with the codebase. 
- The repo must be licenced with one of the following open source licences: GPL-3.0, or MIT.

## Judging criteria

Participants may submit a maximum of 1 project by the hackathon deadline. After submission, projects will be judged by the following criteria:

- **Real-world Functionality**: How well does the project work? Does it meet the minimum requirements?

- **Technical Difficulty**: How technically challenging was it to build the project?

- **Originality**: How original is the idea? How much does it differ from other existing solutions?

- **Design**: How well-designed is the project? Is it easy to use? Is it visually appealing?


## Questions? Support from API3 developers

Looking for help? Head to the API3 Discord and drop questions in the #dev-support channel: https://discord.gg/api3dao -- Or look out for API3 team members at ETHIstanbul. 
