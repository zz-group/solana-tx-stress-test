# solana-tx-stress-test
Solana team claims the blockchain has a throughput of 50k transactions per second - zz-group wants to test this.


## who and why
Several people from Ukraine have united in the ZZ-GROUP team, participate in TdS and support the nodes in the solana test cluster.

In August 2021, it became necessary to check the declared network characteristics in terms of throughput of 50k transactions per second and how this affects the load of the validator node.

Testing stages:
- create more than 2 million addresses and send test 1 SOL to them
- get 10 million SOL for testing
- transfer transactions between wallets: one era of solana is ~ 3 days. 86400 * 3 = 259k seconds. 50k * 259k = 12,960,000,000tx in 3 days. If you send 0.000001 SOL + commission 0.000005 SOL = ~ 100k sol is required for the test
