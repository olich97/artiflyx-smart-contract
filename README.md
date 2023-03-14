# Sample Hardhat Project

This project demonstrates a basic Hardhat use case. It comes with a sample contract, a test for that contract, and a script that deploys that contract.

Try running some of the following tasks:

```shell
npx hardhat help
npx hardhat test
REPORT_GAS=true npx hardhat test
npx hardhat node
npx hardhat run scripts/deploy.ts
```

# Getting started
- Install dependencies:
```shell
yarn
```
- Run tests:
```shell
yarn run test
```
- Run linting:
```shell
# checks
yarn run lint
# fix
yarn run lint:fix
```
- Run local chain:
```shell
yarn run chain
```
- Compile smart contract:
```shell
yarn run compile
```
- Deploy smart contract:
```shell
# local chain
npm run deploy:local
# goerli
npm run deploy:goerli
```
- Verify smart contract:
```shell
# local chain
npx hardhat verify "<CONTRACT ADDRESS>" --network goerli
```