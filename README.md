# Single Swap Uniswap V3

This projects demonstrates the swapping of the LINK tokens with WETH (Wrapped Ether) using a Uniswap V3 functions :

- ISwapRouter
- swapExactInputSingle
- swapExactOutputSingle

## To deploy (Goerli)

```
npx hardhat run --network goerli scripts/deploy.js
```

## Testing

We can test the tokens on Remix IDE using Metamask.

(IMP : While testing on the Remix IDE change the import to : https://github.com/Uniswap/v3-periphery/blob/main/contracts/interfaces/ISwapRouter.sol)
