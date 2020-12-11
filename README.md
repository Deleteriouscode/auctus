The subgraph tracks transactions on Auctus token contract on the main network: 0xc12d099be31567add4e4e4d0D45691C3F58f5663. It records changes in total supply, transactions, and wallet balances.

Getting started
Once download the code, run:

yarn install
Entities description
Token - stores Auctus address as ID and total supply derived from TotalSupply entity.

TotalSupply - records token total supply. Note, only total supply that's different from previous will be recorded.

Transfer - records transfers on the contract.

Balances - records token balances that own the token.

_LastTokenSupply - helper entity to keep track of last token supply to compare the changes to current token supply
