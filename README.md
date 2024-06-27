## Foundry

**Foundry is a blazing fast, portable and modular toolkit for Ethereum application development written in Rust.**

Foundry consists of:

- **Forge**: Ethereum testing framework (like Truffle, Hardhat and DappTools).
- **Cast**: Swiss army knife for interacting with EVM smart contracts, sending transactions and getting chain data.
- **Anvil**: Local Ethereum node, akin to Ganache, Hardhat Network.
- **Chisel**: Fast, utilitarian, and verbose solidity REPL.

## Documentation

https://book.getfoundry.sh/

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

`forge create SimpleStorage --interactive `

and then pass the private key
this will deploy our contract on local anvil chain if you want to add another chain you must paasss rpc-url and priavte key to an acoount on that chain

.s.sol - is a convention to tell that its a script

```bash
forge script script/DeploySimpleStorage.s.sol --rpc-url http://127.0.0.1:8545 --broadcast
--private-key 0x00000000000000000000000000000000000000000000000000000000000000
000
```

this is how we deploy on anvil local chain

# Never use .env

erc2335

## thirdweb deploy
