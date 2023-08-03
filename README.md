### Token Details

- Token Name: [Monika's token]
- Token Symbol: [MON]
- Decimals: [18]
- Total Supply: [1000000 * 10]

#### Transfer Tokens

Users can transfer tokens to other addresses. To transfer tokens to another address call the `transfer` function of the smart contract, passing the recipient's address and the amount of tokens to transfer.

#### Approve Token Spending 
To allow another address (a smart contract or a third-party application) to spend tokens on your behalf, you need to approve the spending first:
1. Connect your Ethereum wallet to the network where the ERC-20 token contract is deployed.
2. Call the `approve` function of the smart contract, passing the spender's address and the amount of tokens you want to approve for spending.

#### DEPLOYMENT AND COMPILATION 
Once the smart contract is deployed, the mint function will be available for use, and you can provide any valid Ethereum address in the mint function to mint new tokens and add them to that address's balance.
Here's how it works:
1.Deploy the smart contract to the Ethereum network using Remix, HardHat, or any other preferred development tool.
2.Once the contract is deployed, the address that deployed the contract becomes the contract owner. The contract owner is the only address that can call the mint function since it has the onlyOwner modifier, which restricts access to the owner.
3. To mint tokens for a specific address, you, as the contract owner, can call the mint function and pass the desired recipient's address (to address) and the amount of tokens you want to mint (amount) as function arguments.
