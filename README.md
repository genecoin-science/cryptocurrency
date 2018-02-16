# cryptocurrency
Establishes the characteristics of Genecoin Tokes, how many are created, behave pre and post TSE, locked unlocked and destructed.

So far, Genecoin is an ERC20 Token in Ethereum. This contract will create the definitive token that will replace the initial one.

Actions performed by the contract:
1.1)Create token
1.1.1)Description:
Type: financial instrument - community currency
Name of Token: Genecoin
Ticker: GEN (ou G3N ou GNC ou G$N) or GENE 
Total maximum supply: 100,000,000
Decimals: suggested 8
All available tokens will be sent initially to the contract creator wallet.
1.1.2) Benchmark: ERC20 Ethereum Contracts.
1.2) Keep tokens locked till certain date or signed otherwise (date can be changed).
1.3) Destruction of tokens after ICO.
The remaining tokens on the contract creation wallet will be burned after a set date. It should be part of the creation smart contract the end date on which this will automatically happen, although this final date must be open for some adjustment. 
1.3.1) Benchmark: https://github.com/OpenZeppelin/zeppelin-solidity/blob/master/contracts/token/BurnableToken.sol
1.4) Unlock tokens after burn.
