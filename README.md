# solana-tx-stress-test
Solana team claims the blockchain has a throughput of 50k transactions per second - zz-group wants to test this.

## Who and Why
Several people from Ukraine have united in the ZZ-GROUP team, participate in TdS and support the nodes in the solana test cluster.

In August 2021, it became necessary to check the declared network characteristics in terms of throughput of 50k transactions per second and how this affects the load of the validator node.

Testing stages:
- create more than 2 million addresses and send test 1 SOL to them (get Sol in faucet)
- get 10 million SOL for testing
- transfer transactions between wallets: one era of solana is ~ 3 days. 86400 * 3 = 259k seconds. 50k * 259k = 12,960,000,000tx in 3 days. If you send 0.000001 SOL + commission 0.000005 SOL = ~ 100k sol is required for the test

## Our skills
We previously performed load testing of the blockchain on the tendermint engine:
- the declared characteristics of 2 thousand transactions per second were carried out in greenhouse conditions with only 4 validators. When there were more than 16 Validators, the maximum possible number of transactions was several times less.

## Address for testnet SOL in TdS
7sh7JZ3y3ihH1MB6YRpdUhm2Z7gQDwxcNahgyuwAfdX6
