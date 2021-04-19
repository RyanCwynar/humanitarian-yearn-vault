# Humanitarian Yearn Vault

This project will follow a simple 3 step trajectory:
1. get a copy of a successful Yearn vault strategy
2. add code to send half of the interest generated somewhere else (usually this would be theft, but in this case it's helping people by backing a universal basic income or supporting the functions of a DAO that manages it)
3. profit

## Discussion

After some initial conversations with people more familiar with solidity than myself, I've boiled down that basically what this thing has to do is be vault that uses another vault.

Currently there's a number of successful strategies on Yearn. What we want to do is wrap one and then use the interest to buy and burn UBI tokens, thus providing a much needed mechanism for scarcity into the network.

To do this, I'll need to understand the interface of a Yearn vault and a Yearn strategy.

I'll have to figure out how to use one vault from another.

I'll have to include logic which uses the interest (likely in DAI) to buy and burn UBI tokens from Uniswap's market.

## Reference
Yearn Vaults - https://github.com/yearn/yearn-vaults
