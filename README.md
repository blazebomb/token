# Project Title

Simple overview of use/purpose.

## Description

This Solidity smart contract deploys an ERC20 token named "latin" with the symbol "LTN". Leveraging OpenZeppelin's `ERC20` and `Ownable` contracts, it establishes ownership control and standard token functionalities. Upon deployment, 10,000 tokens are minted to the deployer's address. The contract owner can mint additional tokens for any address, while all holders possess the ability to burn their tokens. 

## Getting Started
Requirements like ERC20 token, VSCode , NodeJS Should be staisfied

### Installing

* Clone the github repository and open it with Github
* Paste the contract code in the Remix IDE
* Compile the code
* Deploy the code

### Executing program

* Type npm install  in the terminal
* Then type npm install hardhat
* type npx hardhat compile
* type  npx hardhat run scripts/deploy.js --network goerli
* copy the deployed address
* open remix ide and paste the address at "At address"

## Authors

Ashish 

## License

This project is licensed under the [MIT] License - see the LICENSE.md file for details
