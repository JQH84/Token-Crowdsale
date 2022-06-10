# Token-Crowdsale

### Summary

This is a simple token-crowdsale contract developed using solidity that allows the user to conduct a token crowdsale. The user or owner of the this contract will be able to set a time limit for the crowd sale of his token and transfer the Ethereum from the contract to his wallet after the sale has ended. 

## How to use the contract using Remix IDE

### Initial Setup Required

- Open the [Remix IDE](https://remix.ethereum.org/)
- Open the KaseiCoin.sol and KaseiCoinCrowdsale.sol files , inspect them to see the code.
- Compile both the files using compile section
- Use a [Ganash](https://github.com/trufflesuite/ganache-ui/releases) One-Click blockchain tool to simulate the use of the contract or any Etheruem testnet of your choice.

### Compile and Deploy

- After you compile you will notice three contracts in the deploy section.
- Use the KaseiCoinCrowdsaleDeployer.sol file to deploy the contract initially so it can provide the Token and Crowdsale contract addresses to use in the next step.
- Then use the At Address button to deploy the rest of the two contracts from above.

### Buying the token from the Crowdsale

- using the deployed KaseiCoinCrowdsale contract address you can access the buyTokens function to buy tokens , at this point use 1 or more new addresses loaded with Etheruem to make the purchase.
- ***Note*** for the purpose of functionality the contract was programmed with a period of 5 minutes before the crowdsale ends.
- you can also use the finalize function to end the crowdsale and then the tokens can be transfer.

## Demo of how the contract works

![[](/Results/Contract_Demo.gif)](Results/Contract_Demo.gif)
