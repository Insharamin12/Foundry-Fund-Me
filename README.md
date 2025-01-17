# FundMe Smart Contract


## Overview

The FundMe smart contract enables individuals to fund a contract with Eth, ensuring that the contribution meets a minimum value of 5 USD. It uses the Chainlink price feed to convert the Ether amount into USD, making the platform transparent and globally accessible. 

### Key Features:
- Contributors must send at least 5 USD worth of Ether.
- The contract tracks how much each contributor has funded.
- The contract owner has the exclusive ability to withdraw the funds.

### Tech Stack:
- **Solidity:** Smart contract language used to build the contract.
- **Chainlink:** Provides a decentralized price feed to convert ETH to USD.
- **Foundry:** Used for contract deployment and testing.

## Installation

To get started with the FundMe project, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/fundme.git
   cd fundme

## Usage

### Build

```shell
$ forge build
```

### Test

```shell
$ forge test
```

### Format

```shell
$ forge fmt
```

### Gas Snapshots

```shell
$ forge snapshot
```

### Anvil

```shell
$ anvil
```

### Deploy

```shell
$ forge script script/Counter.s.sol:CounterScript --rpc-url <your_rpc_url> --private-key <your_private_key>
```

### Cast

```shell
$ cast <subcommand>
```

### Help

```shell
$ forge --help
$ anvil --help
$ cast --help
```
## Documentation

https://book.getfoundry.sh/
