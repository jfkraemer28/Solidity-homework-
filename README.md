# Homework 20 - Solidity

John-Francis Kraemer

## Contract 1
The solidity smart contract for AssociateProfitSplitter.sol will allow the deposit of 10 ETH to each of the 3 employeees and will sweep any remaining amounts back to the withdrawing account.

![Remix Screen Shot 1](images/remix1.png)


The smart contract amount in addresses that represent employee_one, employee_two, and employee_three for AssociateProfitSplitter.sol before the smart contract is activated.  The address ending in ...67eBa serves as the withdrawing account with the subsequent 3 address presenting the depositing accounts of the 3 employees.  All 4 addresses have a starting balance of 100 ETH

![Ganache 1](Images/Ganache1.png)


The smart contract AssociateProfitSplitter.sol is compiled.

![Remix Screen Shot 2](Images/Remix2.png)

The smart contract AssociateProfitSplitter.sol activated by hitting the "Transact" button and is also connected to the Custom 5777 network (MetaMask account).

![Remix Screen Shot 3](Images/Remix3.png)

The activated smart contract is reflected within MetaMask.

![MetaMask Screen Shot 1](Images/Metamask1.png)

The smart contract makes a deposit of 10 ETH that is reflected within MetaMask and Ganache.

![Remix Screen Shot 4](Images/Remix4.png)
![MetaMask Screen Shot 2](Images/Metamask2.png)

The ending balances of the withdrawing account ending in ...67eBa is deducted 10 ETH (plus gas fees) with an ending balance of 89.99 ETH and the subsequent addresses of the 3 employees received 3.33 ETH with an ending balance of 103.33 ETH.
![Ganache 2](Images/Ganache2.png)