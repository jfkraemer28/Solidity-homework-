# Homework 20 - Solidity

John-Francis Kraemer

## Contract 1
The solidity smart contract for AssociateProfitSplitter.sol will allow the deposit of 10 ETH to each of the 3 employeees and will sweep any remaining amounts back to the withdrawing account.

![remix_1](Images/remix1.PNG)


The smart contract amount in addresses that represent employee_one, employee_two, and employee_three for AssociateProfitSplitter.sol before the smart contract is activated.  The address ending in ...67eBa serves as the withdrawing account with the subsequent 3 address presenting the depositing accounts of the 3 employees.  All 4 addresses have a starting balance of 100 ETH

![ganache_1](Images/ganache1.PNG)


The smart contract AssociateProfitSplitter.sol is compiled.

![remix_2](Images/remix2.PNG)

The smart contract AssociateProfitSplitter.sol activated by hitting the "Transact" button and is also connected to the Custom 5777 network (MetaMask account).

![remix_3](Images/remix3.PNG)

The activated smart contract is reflected within MetaMask.

![metamask_1](Images/metamask1.PNG)

The smart contract makes a deposit of 10 ETH that is reflected within MetaMask and Ganache.

![remix_4](Images/remix4.PNG)
![metamask_2](Images/metamask2.PNG)

The ending balances of the withdrawing account ending in ...67eBa is deducted 10 ETH (plus gas fees) with an ending balance of 89.99 ETH and the subsequent addresses of the 3 employees received 3.33 ETH with an ending balance of 103.33 ETH.
![ganache_2](Images/ganache2.PNG)