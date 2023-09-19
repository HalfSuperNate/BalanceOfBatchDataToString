# BalanceOfBatchDataToString
Contract Address: 0x41e7BFA6E22E9067D183e28e619e6eB9F1e33e23
A smart contract that converts other smart contract balanceOfBatch data to string for a single wallet with a range of token IDs

This can be useful for getting balances for a single wallet for a range of token IDs fetching data using Unity Metamask SDK.
Just set the params for: what ERC1155 contract, what wallet to check, and a start and end token ID.
The returned data is in a single concatenated string seperated by a comma which can then be parsed to an array of ints.
