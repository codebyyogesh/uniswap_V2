# Uniswap V2 

## Contracts to interact with uniswap for

1. flash swap
2. liquidity
3. swap

terminal 1:
npx ganache-cli i --fork https://mainnet.infura.io/v3/$WEB3_INFURA_PROJECT_ID  --networkId 999

terminal 2:
truffle migrate --network mainnet_fork
npx truffle test --network mainnet_fork test/testSwap.js