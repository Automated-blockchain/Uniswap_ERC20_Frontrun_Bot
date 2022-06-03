# Uniswap_ERC20_Frontrun_Bot

The front run bot for Uniswap (ERC20)

Uniswap frontrun bot follows the "target" address and trades tokens on Uniswap when someone purchases a big portion of the specified token. It can front run that transaction by setting higher gas fee.

## Prerequisities
Node and NPM https://nodejs.org/en/download/
Wallet with ETH for gas and token swap

## Running BOT
Update env.js and provide private key to wallet and token address you want to target.

Bot is preconfigured for Uniswap on ERC20. Review configuration in constants.js.

Install packages:
```
$ npm install web3
$ npm install axios
$ npm install colors
$ npm install ethereumjs-tx
$ npm install abi-decoder
```

Run script:
```
$ node frontrun.js
```
