# POLYCUB-CONTRACTS

#### Before you set up

<!-- Change `claim()` to add second param `limit`, can be set to 0 by default: `claim(bool, uint256)` -->
You'll need to install `yarn` and `nodejs` onto your computer, via the command line. 

Yarn Install Guide: https://classic.yarnpkg.com/en/docs/install

NodeJS install guide: https://nodejs.org/en/download/

#### *Set-up Locally*
In your terminal, navigate to where you would like this site to live, then run 
```
#clone the repo
git clone https://github.com/CubFinance/polycub-contracts.git

#navigate to the directory
cd polycub-frontends

# Install the dependencies
yarn install or npm install

```
# This project demonstrates an advanced Hardhat use case, integrating other tools commonly used alongside Hardhat in the ecosystem.


<!-- When user calls `deposit()` or `withdraw()`, pending tokens are stored to array together with unlock block. When `claim()` is called,
it calculates how many tokens are already past `unlock block` and sends them to the user. if tokens are not unlocked yet (and user specified to claim them too using `true` as first param), 50% of locked tokens is sent to `penaltyAddress`, 50% to the user. -->
```shell
## To run locally
`npx hardhat compile` to compile the contract

`npx hardhat node` to start a local node

Open another terminal

`npx hardhat run --network localhost scripts/deploy.js` to deploy

`npx hardhat test test/test.js` to test contract
```



# Deployed Contract
# polycub
https://polygonscan.com/address/0x7cc15fef543f205bf21018f038f591c6bada941c

# MasterChef 
https://polygonscan.com/address/0xef79881df640b42bda6a84ac9435611ec6bb51a4

# xStaker
https://polygonscan.com/address/0x905e21f6c4cb1ad789ced61cd0734590a4542346
