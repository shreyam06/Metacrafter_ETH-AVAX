# Metacrafter_ETH-AVAX
This solidity smart contract demonstrates ownership functionality, allowing only the contract owner to execute certain functions.
The OwnershipContract smart contract is designed to restrict certain functions to be callable only by the owner of the contract. The owner is set during contract deployment and cannot be changed thereafter.

Constructor
The constructor function initializes the contract owner to be the address of the account that deployed the contract.

onlyOwner
This function is a modifier that restricts the execution of certain functions to only the owner of the contract.

onwerHere
This function checks if the caller is the owner of the contract and reverts the transaction if not.

Owner
This function asserts that the caller is the owner of the contract. If the caller is not the owner, the transaction will be reverted.

