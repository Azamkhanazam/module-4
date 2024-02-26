### Overview

This repository contains a Solidity smart contract named `BlanketSubscription` designed to facilitate a blanket subscription service utilizing blockchain technology. Users can redeem blankets of various types using a custom ERC20 token called "Blanket Token" (BLK). Additionally, users are rewarded with tokens when they redeem blankets.

### Features

- **Subscription**: Users can redeem blankets of different types using BLK tokens.
- **Reward System**: Users receive rewards in BLK tokens when they redeem blankets.
- **Token Management**: Ability to mint, burn, and transfer BLK tokens.
- **Ownership Control**: The contract owner has exclusive control over token management functions.

### Smart Contract Details

- **Token**: ERC20 standard token named "Blanket Token" with symbol "BLK".
- **Blanket Types**: Five types of blankets available for redemption: Cotton, Wool, Fleece, Silk, Cashmere.
- **Cost**: Each blanket type has a predefined cost in BLK tokens.
- **Rewards**: Users receive rewards equivalent to half the cost of the redeemed blanket.
- **Ownership**: The contract owner has privileges to manage token supply and transfers.

### Deployment and Usage

1. Deploy the `BlanketSubscription` smart contract to a compatible blockchain network (e.g., Ethereum).
2. Mint a sufficient amount of BLK tokens and transfer ownership to the desired address.
3. Users interact with the contract to redeem blankets by spending BLK tokens.
4. Users receive rewards in BLK tokens upon redeeming blankets.
5. The contract owner manages token supply and transfers using provided functions.


### Contributors

## Roshan Khan

### License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
