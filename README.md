# ERC20 Staking App ----> StakeWise
using ERC20Conracts 

EVM blockchain

Next.js Framework

Typescript Language

Chakra-react ui

Local wallet is used to create contracts //attaching that localwallet backup to import for testcase...

PS:Ignore the runtime of that local wallet...

file name:wallet.json Passwor:Ts08#11@2001*

# Must have folders to run the App

install node modules

![Screenshot from 2023-05-31 00-55-36](https://github.com/raaammm08/StakeWise_ERC20_Webapp/assets/69867867/ad198e4a-c8e8-49d9-85d4-f9a44229cbd2)
-------------------------------------------------

contracts also need node mudules

![Screenshot from 2023-05-31 00-59-17](https://github.com/raaammm08/StakeWise_ERC20_Webapp/assets/69867867/101d5132-5ae1-41aa-94e6-0d417fb7b899)
-------------------------------------------------
# APP INTERFACE PICS

# interface

![Screenshot from 2023-05-31 00-17-30](https://github.com/raaammm08/StakeWise_ERC20_Webapp/assets/69867867/55fc1a7e-68ab-47b1-98ad-1f1e3c6db64f)
----------------------------------------------------------------------
# after login

![Screenshot from 2023-05-31 00-17-11](https://github.com/raaammm08/StakeWise_ERC20_Webapp/assets/69867867/48f173d4-01a0-4c80-ac5b-595eefce629f)
----------------------------------------------------------------------
# wallet for backup 

![Screenshot from 2023-05-31 00-35-18](https://github.com/raaammm08/StakeWise_ERC20_Webapp/assets/69867867/5248db5a-209c-41d8-8da4-8df8fdbfb4f5)
----------------------------------------------------------------------

Allow users to stake their ERC20 tokens in return for more/other ERC20 tokens!

In this repo, we are using [thirdweb ContractKit](https://thirdweb.com/contractkit) and writing a custom ERC-20 staking contract.

You can read [the guide associated to this repo](https://blog.thirdweb.com/build-an-erc20-staking-smart-contract-web-application/).

## How to use

Clone this repo to have this repo locally.

The `staking-contract` directory holds the contracts the contract that we are using in this guide. You can navigate to the folder and run the following command to install the dependencies

```bash
yarn install
```

The root directory holds the frontend code. You run the following command to install the dependencies

```bash
yarn install
```

### Deploying the contract

You can deploy the contract using the following command

```bash
npx thirdweb@latest deploy
```

This will upload the contract metadata to IPFS and will open browser to deploy the contract using the connected wallet.

### Deploying the frontend

You can use the following command to quickly deploy the frontend to IPFS:

```bash
yarn deploy
```
