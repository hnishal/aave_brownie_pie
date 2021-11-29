1. Convert ETH to WETH
1. Deposit some ETH into Aave
1. Borrow some asset with the ETH as colleteral
   1. Sell that borrowed asset. (Short Selling)
1. Repay everything back

# TESTING:

Integration Test: Kovan
Unit Test: Mainnet-fork

## NOTE

if we are not using oracles and we dont need to mock responses from them we can use mainnet-fork

if we are using oracles then we should use development network with testing
