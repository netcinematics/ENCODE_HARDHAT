# ENCODE_HARDHAT
HardHat Template from the Encode Club ETH Bootcamp.

This is a minimal boilerplate for hardhat.

----

# HARDHAT:
https://hardhat.org/hardhat-runner/docs/other-guides/waffle-testing

## SETUP

npm install @openzeppelin/contracts

npm install -D hardhat

npx hardhat

Select Create an empty hardhat.config.js. This will create an empty Hardhat configuration file.

npm install --save-dev chai @nomiclabs/hardhat-waffle

In hardhat.config.js: require("@nomiclabs/hardhat-waffle");

Create /contracts/contract1.sol and /tests/test1/js

npx hardhat test

F5 - compile .sol contract.

----

NOTES: This took forever to find good example.
https://docs.openzeppelin.com/contracts/4.x/
$ npm install @openzeppelin/contracts

TIPS:

- no need for require("@nomiclabs/hardhat-ethers"), as @nomiclabs/hardhat-waffle




