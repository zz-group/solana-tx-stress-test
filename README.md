# solana-tx-stress-test
Solana team claims the blockchain has a throughput of 50k transactions per second - zz-group wants to test this.

## Who and Why
Several people from Ukraine have united in the ZZ-GROUP team, participate in TdS and support the nodes in the Solana test cluster.

In August 2021, it became necessary to check the declared network characteristics in terms of throughput of 50k transactions per second and how this affects the load of the validator node.

Testing stages:
- create more than 2 million addresses and send test 1 SOL to them (get SOL in faucet)
- get 10 million SOL for testing
- transfer transactions between wallets: one era of solana is ~ 3 days. 86400 * 3 = 259k seconds. 50k * 259k = 12,960,000,000tx in 3 days. If you send 0.000001 SOL + commission 0.000005 SOL = ~ 100k SOL are required for the test

## Our skills
Besides the staking providing services, we previously performed load testing of the blockchain on the Tendermint engine:
the declared throughput was 2000 transactions per second. This throughput was enabled only by 4 validators run in greenhouse conditions. At the start, there were more than 16 validators, and the maximum possible number of transactions was several times less

## Address for testnet SOL in TdS
7sh7JZ3y3ihH1MB6YRpdUhm2Z7gQDwxcNahgyuwAfdX6

# Contacts
Telefram: https://t.me/solana_informer

Telegram Group: https://t.me/solana_informer_group

mail: github-contact@zz-group.infocoin.pro
