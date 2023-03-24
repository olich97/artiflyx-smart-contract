# Sample Hardhat Project

This project aims to demonstrates a basic Hardhat use case with complete CI/CD flows using Open Zeppelin for smart contracts upgrades, admin actions and contract monitoring. 

# Roadmap

Step 1: 
- [x] CI with slither and GitHub Actions 
- [ ] Add Open Zeppelin Defender proposal for deployment and upgrades

Step 2: 
- [ ] Add smart contract monitoring with Open Zeppelin Sentinel
- [ ] Add notifications/warinings of critical smart contract events
- [ ] Automatically pause/unpause contract with Autotasks, in case of weird events
- [ ] Build smart contracts metrics overview dashboard: events numbers, gas used, upgrades, token created etc.

Step 3: 
- [ ] Securing minting functionalities with Open Zeppelin Relayer and Autotask

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
