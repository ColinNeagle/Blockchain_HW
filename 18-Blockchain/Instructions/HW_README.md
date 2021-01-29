# Imstructions for setting up the chain

CD into your blockchain_rules folder


![screenshot](Screenshot/blockchain_rules.png)

## Create accounts for two nodes for the network with a separate datadir for each using geth. 

`./geth --datadir node1 account new`


`./geth --datadir node2 account new`


![screenshot](Screenshot/Node_accts.png)



create password


![screenshot](Screenshot/password.png)



open VS Code

`code .`

run puppeth

`./puppeth`

![screenshot](Screenshot/puppeth.png)






![screenshot](Screenshot/puppeth2.png)


Paste accounts into the seal

![screenshot](Screenshot/accounts.png)


`’Manage existing genesis’`

![screenshot](Screenshot/existing_genesis.png)



## Initialize the nodes with the genesis' json file

Initialize each node

![screenshot](Screenshot/initialize.png)


## Use nodes to mine blocks

#![screenshot](Screenshot/mine_blocks.png)


Type password

## Open MyCrypto

Select Change network

Setup custom node

#![screenshot](Screenshot/custom_node_cn.png)


## Test the transaction

#![screenshot](Screenshot/test_transaction.png)


## Check status

#![screenshot](Screenshot/Transaction_success_cn.png)

When completed the Status will change from "PENDING" to "SUCCESSFUL"