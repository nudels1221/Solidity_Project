## MyToken Solidity Contract

This Solidity contract implements a basic token on the Ethereum blockchain.


## Purpose

The MyToken Solidity contract is designed to create a custom ERC20-like token on the Ethereum blockchain. This token, named MetaToken with the abbreviation MTA, can be used for various purposes including, but not limited to, reward systems within decentralized applications (DApps), token sales, and more.


### Functionality

The MyToken contract includes the following functionalities:

* Token Details: Stores the token's name, abbreviation, and total supply.
* Balances: Maintains a mapping of addresses to their respective token balances.
* Minting: Allows new tokens to be created and assigned to a specified address, increasing both the total supply and the recipient's balance.
* Burning: Allows tokens to be destroyed, reducing both the total supply and the sender's balance, with a check to ensure the sender has sufficient balance.

### Usage

*  Deployment: Deploy the contract to the Ethereum network. Upon deployment, the contract initializes with the specified token name, abbreviation, and a total supply of zero.
*  Minting Tokens: The mint function can be called to create new tokens. This function takes an address and an amount as parameters, increases the total supply by the specified amount, and credits the specified address with the new tokens.
*  Burning Tokens: The burn function can be called to destroy tokens. This function takes an address and an amount as parameters, checks if the address has enough tokens to burn, then decreases the total supply and the address's balance by the specified amount.
License


## License

This project is licensed under the [NAME HERE] License - see the LICENSE.md file for details

This contract is licensed under the MIT License.