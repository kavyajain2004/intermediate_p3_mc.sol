# Creating an ERC20 Token

This is a Solidity smart contract written for a token implementation based on the ERC20 standard. The contract provides functionalities for minting and burning tokens, with the ability to specify an owner who has exclusive access to these functions.


## Description

The Token contract inherits from the OpenZeppelin ERC20 implementation, providing standard token functionalities. Additionally, it introduces a mechanism to restrict certain operations to the contract owner.

## Getting Started

### Deployment
1. Deploy the contract to an Ethereum-compatible network using tools like Remix, Truffle, or Hardhat.
2. Provide the desired name and symbol for your token during deployment.

### Interacting with the Contract
- **Minting Tokens**: The `mint` function allows the owner to create new tokens and assign them to a specified address.
- **Burning Tokens**: The `burn` function allows the owner to destroy tokens held by a specified address.

## Installation
To use this contract in your project, you can import it as a dependency:
import "@openzeppelin/contracts/token/ERC20/ERC20.sol";


## License

This project is licensed under the MIT License.
