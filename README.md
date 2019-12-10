# ERC20Distributor.sol
Allows the creator to specify different addresses with differently sized shares, which will get accordingly sized portions of all Tokens from any at deployment defined ERC20 token contract, whichs are sitting in this smart contract, by calling distributeTokens() from anyone.
I am a bloody beginner at solidity/smart contract development right now
- *so if you find some critical bugs in there or simply wanna add/change something, feel free ^^*


**ERC20Distributor.sol** after the first view short help libraries is the actual code.

**BasicERC20.sol** is just a simple ERC20 helper debug contract to generate random debug ERC20-tokens.
I think I basically copy pasted it from https://gist.github.com/giladHaimov/8e81dbde10c9aeff69a1d683ed6870be
Thank you for your help!


Some deployment notes for myself:
 - combile using remix with constructor argument

 - copy combiled bytcode (Data) (from Confirm TX window)

 - Use mycrypto -> Contracts -> Deploy to actually deploy contract (take care of fees)

 - Check it out on etherscan and verify and publish the code for fancy user interface on etherscan
 - Take care! Combiler version and all other settings as well as code of course need to be identical