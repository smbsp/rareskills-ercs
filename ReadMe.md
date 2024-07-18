# Experimenting with ERC Standards

Welcome to the ERC Standards repository! This repository contains my experiments and coding implementations with various Ethereum Request for Comments (ERC) standards. These implementations are part of my learning journey through RareSkills blogs and coursework.

## Table of Contents

- [Experimenting with ERC Standards](#experimenting-with-erc-standards)
  - [Table of Contents](#table-of-contents)
  - [Introduction](#introduction)
  - [Setup and Installation](#setup-and-installation)
  - [ERC Implementations](#erc-implementations)
    - [ERC-20](#erc-20)
    - [ERC-721](#erc-721)
    - [ERC-1155](#erc-1155)
    - [ERC-777](#erc-777)
  - [Learning Resources](#learning-resources)
  - [Contributing](#contributing)
  - [License](#license)

## Introduction

This repository showcases my work on implementing various ERC standards, which are crucial for Ethereum smart contract development. These standards define common interfaces and functionalities for tokens and other smart contract interactions on the Ethereum blockchain. The implementations here are based on my learning from RareSkills blogs and coursework.

## Setup and Installation

To get started with this repository, follow these steps:

1. **Clone the repository**:
    ```sh
    git clone https://github.com/smbsp/rareskills-ercs.git
    cd rareskills-ercs
    ```

2. **Install dependencies**:
    Ensure you have [Node.js](https://nodejs.org/) and [npm](https://www.npmjs.com/) installed, then run:
    ```sh
    npm install
    ```

3. **Compile the contracts**:
    Use Hardhat to compile the smart contracts:
    ```sh
    npx hardhat compile
    ```

4. **Run tests**:
    Execute the tests to verify the implementations:
    ```sh
    npx hardhat test
    ```

## ERC Implementations

### ERC-20

ERC-20 is a standard for fungible tokens, which are identical and can be exchanged one-to-one.

- **Implementation File**: [ERC20.sol](./contracts/ERC20.sol)
- **Test File**: [ERC20.test.js](./test/ERC20.test.js)

### ERC-721

ERC-721 is a standard for non-fungible tokens (NFTs), which are unique and distinguishable from each other.

- **Implementation File**: [ERC721.sol](./contracts/ERC721.sol)
- **Test File**: [ERC721.test.js](./test/ERC721.test.js)

### ERC-1155

ERC-1155 is a multi-token standard that allows for both fungible and non-fungible tokens in a single contract.

- **Implementation File**: [ERC1155.sol](./contracts/ERC1155.sol)
- **Test File**: [ERC1155.test.js](./test/ERC1155.test.js)

### ERC-777

ERC-777 is an advanced token standard that includes features like hooks and more complex interactions.

- **Implementation File**: [ERC777.sol](./contracts/ERC777.sol)
- **Test File**: [ERC777.test.js](./test/ERC777.test.js)

## Learning Resources

- [RareSkills Blog](https://rareskills.io/blog)
- [RareSkills Coursework](https://rareskills.io/course)
- [OpenZeppelin Contracts](https://docs.openzeppelin.com/contracts/4.x/)

## Contributing

Contributions are welcome! If you have improvements or additional implementations to add, please submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
