1. Users can enter the lottery with ETH based on a USD fee
2. An admin will decide when the lottery is over
3. The lottery will select a random winner

How to test?
# Delete the older mainnet-fork or dev first
# Using alchemy do remember to close ganache instance while doing mainnet-fork testing
1. "mainnet-fork" testing 
2. "development" with mocks testing
3. "testnet"

The random number request from Chainlink VRFCoordinator costs 25-30 minutes.
During that time,  the address can not be displayed correctly.
But you can findout the right winner on the rinkeby etherscan address