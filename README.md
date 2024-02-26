### Overview

This repository contains a Solidity smart contract named `HatToken`, which represents a tokenized system for purchasing and redeeming hats on the blockchain. Users can acquire "HatToken" (HAT) tokens, purchase hats with these tokens, and burn hats when needed. Additionally, the contract owner can manage the hat inventory by adjusting quantities.

### Features

- **Tokenization**: Hats are represented as ERC20 tokens named "HatToken" (HAT).
- **Purchase Hats**: Users can purchase different types of hats using HAT tokens.
- **Inventory Management**: The contract owner can adjust the quantity of each hat type.
- **Token Burning**: Users can burn hats when they no longer need them.
- **Events**: Emit log messages for important contract actions.

### Smart Contract Details

- **Hat Types**: Four types of hats available for purchase: BaseballCap, Beanie, TopHat, CowboyHat.
- **Hat Structure**: Each hat has a name, price (in HAT tokens), and quantity available.
- **Minting**: The contract owner can mint new HAT tokens.
- **Burning**: Users can burn hats to reduce the quantity in circulation.
- **Transfer**: Users can transfer hats to other addresses.
- **Redeeming Hats**: Users can redeem hats by sending the required amount of HAT tokens.
- **Change Hat Quantity**: The contract owner can adjust the quantity of each hat type available for purchase.

### Deployment and Usage

1. Deploy the `HatToken` smart contract to a compatible blockchain network (e.g., Ethereum).
2. Users acquire HAT tokens either through minting (if they are the contract owner) or by purchasing them from others.
3. Users interact with the contract to purchase hats using their HAT tokens.
4. The contract owner can manage the hat inventory by adjusting quantities as needed.
5. Users can burn hats if they no longer need them.

### License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contributions

Azam Khan

**Note:** Customize the README according to your project's specifics and include appropriate links and information.
