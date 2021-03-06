
# DeFis Network: an open financial network connecting DeFi protocols

v1.0 Jun 24 2020
Translations: [中文](https://github.com/defis-network/white-paper/blob/master/whitepaper_cn.md)

## Abstract

DeFis Network’s mission is to build an open financial network based on blockchain technology. 
It enables people worldwide to enjoy safe and equal financial services.

Legacy financial infrastructures are fragmented and isolated from each other due to political influences and technology limits.
An open financial network based on blockchain technology will bring revolutions to traditional financial infrastructures. 

It will break down international financial barriers, improve global liquidity, create network effects, and create currency and financial programmability.

Based on the blockchain, we can build better currencies, better banks, safer lending platforms, and a better future, 
so that everyone in the world can enjoy the safety and convenience of digital currencies anytime, anywhere.

Our goal is to become the first global scale and integrated entrance of open financial network.

## Features Overview

### Common settlement currency issuance protocol: DeFis Bank

DeFis Bank allows users to pledge cryptoassets to issue a common settlement currency JIN, which is anchored by the cryptoassets. JIN is a store of value with stable price that completely exists on the blockchain, it provides a risk-return structure different from the underlying collateral.
It is a decentralized central bank that issues currency with cryptoassets as the anchor, and uses smart contracts to ensure that the anchor will not be detached, its mintage rights are opened, and mintage are fairly distributed. 
Compared with DAI's "borrowing and lending paradigm", it can be called "saving paradigm" or "coin hoarding paradigm". It is designed to allow miners' collateral to be 100% safe while enjoying the pledge benefits.

### Liquidity protocol: DeFis Swap

In Swap, users can freely create trading pairs between any two currencies and inject liquidity to build an effective exchange market.
According to their proportion of the injected liquidity funds, liquidity providers share the transaction fee revenues generated by the transactions fairly.
All these processes are transparent and decentralized. It is a decentralized exchange where everyone can create a market and can become a market maker.
Loan Agreement: DeFis Lend
In this digital asset lending platform, users can choose to deposit tokens for interest, or over-collateralize their token to lend another token. Interest rates are determined by algorithms to increase the utility rate of token. The platform will ensure the safety of user funds, and make sure that users with insufficient collateral are liquidated in time via a real-time liquidation interface.

### Lending protocol: DeFis Lend
In this digital asset lending platform, users can choose to deposit tokens for interest, or over-collateralize their token to lend another token. Interest rates are determined by algorithms to increase the utility rate of token. The platform will ensure the safety of user funds, and make sure that users with insufficient collateral are liquidated in time via a real-time liquidation interface.

### Asset Synthesis protocol: DeFis Synthetix

By staking platform token DFS, users can synthesize a variety of high-quality real world assets. They can short and long these synthetic asset on the platform.
Synthetic assets are minted and can be held for a long time or traded on the platform. It is worth noting that the transaction does not require a counter party. During the transaction, the synthetic assets you sell will be converted into a short version of that synthetic asset automatically, which means an almost unlimited liquidity.
Through asset synthesis agreements, off-chain assets such as high-quality stocks and public goods can be bought and sold anonymously on the blockchain.

### Platform token: DFS

DFS is the platform token of DeFis Network, which is similar to MKR on MakerDAO and COMP on Compound, but its functions are not limited to governance and interest payment. DFS is mainly used for:

* Transactions
* Governance voting
* Liquidity incentives
* Transaction mining
* Operation cooperation
* Staking dividends
* Creating synthetic assets, etc.

Through the integration of a series of DeFi protocols, DeFis Network will generate a powerful network effect in the field of decentralized finance in the future.
The platform token DFS will continue to capture the value generated by these DeFi protocols. DFS holders will continue to receive dividends from protocol fee revenues.
Dividend distributions are executed by smart contracts automatically, so that each DFS holder can share the benefits of DeFis Network development fairly.
As a DFS holder you can join the DeFis Network community and participate in its key governance.

## Token distribution plan


DFS distribution mechanism : fair mining like Bitcoin, without any private placement or pre-mining.
Release rules: in the initial stage, 50 coins are released every second, 45 out of which are accumulated for mining rewards, and 5 are sent to the foundation reserve account as reserve fund. The proportion of miner rewards and reserve funds is 90% and 10% respectively.
Mining rules: for each transaction amount >= 1 EOS, you can participate in one mining opportunity, each mining can get 0.01% of the accumulated tokens in the current contract. The larger the transaction amount, the more the mining reward.
Mining reward reduction rules: the reduction happens every 7 days, and the reward is reduced by 10% each time. When the reward per second being reduced to 5, reward reduction will be ceased. When the total DFS supply reaches 1 billion, there will be no more mining reward.
The eventual DFS supply is 1 billion and its release takes 5 years.
If the development team launches a new DeFi protocol, the above mining plan may migrate from the liquidity agreement to the new DeFi agreement to generate incentives for the new DeFi protocol to help the new agreement bootstrapping.


## Foundation Instructions

DeFis Network uses a decentralized approach to cold start, and there is no private placement or pre-mining in token distribution. Instead, it utilizes the same fair competitive mining method as the original Bitcoin.
To ensure the sustainable development of DeFis Network, 10% of the block rewards will be reserved and supervised via a foundation.
The foundation's token reserve is only used for: setting up insurance funds, maintaining research and development expenses, auditing expenses, operating cooperation, etc., and these tokens do not participate in the staking rewards.

## Staking Rewards

DFS is positioned as a functional token that can drive the development and decentralization of the project. We have designed a staking system to distribute dividends to DFS holders, which will reduce the liquidity of tokens while distinguishing real investors from speculators.
Staking mechanism: to participate in the staking, you need to send DFS tokens to the staking contract so that these tokens can enter the lock-up state. The user who locks their tokens gets the dividend right.
Dividends are conducted once a week. The current source of dividends is 50% of fee revenues from the Swap agreement.
The dividend is distributed to the user's account, but users have to make a claim to actually own them.
It takes 15 days to redeem the tokens if users want to unstake, and no dividend will be paid during the redemption period.


## Development Roadmap

* Stablecoin protocol: the DeFis Bank (developed), an over-collateralized stablecoin issuance system with no liquidation mechanism but funded by the foundation, who is also responsible for the system pledge rate maintenance. It makes sure that every JIN is backed by collateral with value more than $1. DFS holders can receive dividends from the system's mintage .
* Asset Liquidity protocol: the DeFis Swap (developed), an algorithmic Dex similar to Uniswap. DFS holders can receive dividends on the agreement fee.
* Asset Lending protocol: the DeFis Lend (similar to compound, under development)
* Asset Synthesis protocol: the DeFis Synthetix (asset synthesis platform, under development)

Other types of DeFi protocols will continue to be developed and added to the DeFis Network to continue to grow this open financial network.

## Launch Plan 

The source code of DeFis Network is contributed and maintained by DeFi enthusiasts for free.
The project is started and operated by community enthusiasts.
The token distribution method adopts the fair competition distribution method most similar to Bitcoin.
Moreover, the proceeds generated by the agreement are distributed fairly to token holders via smart contracts.
Therefore, we can say that all users who participate in mining or hold project token DFS are the owners of this project.


## Code Copyright Notice


All codes under the DeFis Network adopt the GPL open source protocol.
Allow any individual or organization ("licensee") to research, review and analyze the software in private. The licensee may quote and modify this software under the constraints of the GPL open source agreement. In any case, the copyright owner is not responsible for any damage or other liability arising from or related to the software due to incorrect use, modification, or contract, infringement or other aspects.

## Summary

DeFis Network aims to build the underlying foundation and entrance of a decentralized financial network, and become a bridge between users and decentralized finance.
We are committed to accelerate the arrival of decentralized finance. By unleashing the power of blockchain, the transformation of finance by blockchain can be realized.
We promote this vision in a decentralized way.
Better future. Respects.







