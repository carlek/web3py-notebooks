# web3py-notebooks

This repository contains examples based on the [documentation](https://web3py.readthedocs.io/) to interact with Ethereum using the Web3.py library. 
These notebooks are a cookbook of small entrees of code as well as large recipes with brief explanations.  The goal is a better experience with the documentation for someome to get started with Ethereum development.

*TODO*:
1. add some setup for Infura and Geth.
1. examine the notebooks for perhaps a more usable organization 

## Table of Contents

- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Quickstart](#quickstart)
- [Examples Primo](#examples-primo)
  - [1. Looking up Blocks](#1-looking-up-blocks)
  - [2. Retrieve Block Info](#2-retrieve-block-info)
  - [3. Check the balance of an account](#3-check-the-balance-of-an-account)
  - [4. Currency Conversion](#4-currency-conversion)
  - [5. Sending Transactions](#5-sending-transactions)
  - [6. Retrieving Receipts](#6-retrieving-receipts)
  - [7. Deploying New Contracts](#7-deploying-new-contracts)
- [Contributing](#contributing)
- [License](#license)

## Prerequisites

Before running the examples, make sure you have the following prerequisites installed:

- Python 3.x
- Web3.py library
- geth

## Installation

1. Clone this repository to your local machine:

   ```bash
   git clone https://github.com/your_username/web3py-notebooks.git
   ```

2. Create .venv and install Python packages:

   ```bash
   python -m venv .venv
   source .venv/bin/activate
   pip install -r requirements.txt
   ```
3. Create a `.env` file containing your Infura Project ID (API)
```
INFURA_PROJECT_ID=<your API key>
```

## Quickstart

Connections to Providers and Block Info from geth

## Examples Primo

### 1. Looking up Blocks
Example code to find a block.

### 2. Retrieve block info
Get the latest block and extract various details.

### 3. Check the balance of an account
Find the amount of ether owned by an account

### 4. Currency Conversion
Convert to and from various currency denominations

### 5. Sending Transactions
Use eth-tester (via EthereumTesterProvider) to send transactions

### 6. Retrieving Receipts
Retrieve details after a transaction was send.

### 7. Deploying New Contracts
Compile and deploy a simple contract
* Compiles the contract from the .sol file.
* Estimates gas costs of the transaction.
* Transacts with the contract's function.
* Waits for the transaction receipt to be mined


## Contributing

If you'd like to contribute to this repository, please follow these steps:

1. Fork the repository
2. Create a new branch (`git checkout -b feature/your-feature`)
3. Make your changes and commit them (`git commit -m 'Add your feature'`)
4. Push to the branch (`git push origin feature/your-feature`)
5. Create a new pull request

## License

This project is licensed under the [MIT License](LICENSE). Feel free to use, modify, and distribute the code for your own projects.

---

Happy Ethereum development! If you have any questions or suggestions, please feel free to open an issue or reach out to me.
