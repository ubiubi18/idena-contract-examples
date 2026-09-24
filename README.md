# idena-contract-examples [WIP]

## Research disclaimer

This is experimental research software. I cannot guarantee its security, correctness, or fitness for any purpose. Use it at your own risk, take responsibility for your decisions, independently verify changes, and stay vigilant.

## Note: Contract examples are not ready for production use. Code may be bugged. The purpose of this repo is to show how to write and test contracts with idena-sdk-as.


## How to build

Choose example, install dependencies  and build wasm file
```sh
cd hello-world
yarn install
yarn asb
```

## How to test

Run node [simulator](https://github.com/idena-network/idena-contract-runner)
```sh
./idena-contract-runner-linux-0.0.2
```
Execute tests

```sh
yarn test
```
