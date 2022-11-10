# bare-box
Truffle Box for a bare-minimum Truffle project (`truffle init`)

```bash
ling@LAPTOP-SIM0A8SC:~/go/src/blockchain/pet-shop-tutorial$ sudo truffle  migrate

Compiling your contracts...
===========================
> Everything is up to date, there is nothing to compile.


Starting migrations...
======================
> Network name:    'development'
> Network id:      1668059162732
> Block gas limit: 6721975 (0x6691b7)


1_initial_migration.js
======================

   Deploying 'Migrations'
   ----------------------
   > transaction hash:    0xcf6f8635d03206491d34e10d952bc93e411a374abfd29c86669ddbd4d5ec973c
   > Blocks: 0            Seconds: 0
   > contract address:    0x8b71cBA7Db4D2446489907d9e8293551e6410c47
   > block number:        1
   > block timestamp:     1668059197
   > account:             0x1552Fc72cA293BdDD98111Be685d26fb6e4b38D4
   > balance:             99.99616114
   > gas used:            191943 (0x2edc7)
   > gas price:           20 gwei
   > value sent:          0 ETH
   > total cost:          0.00383886 ETH

   > Saving migration to chain.
   > Saving artifacts
   -------------------------------------
   > Total cost:          0.00383886 ETH


2_deploy_contracts.js
=====================

TypeError: deployer.deployer is not a function
    at module.exports (/home/ling/go/src/blockchain/pet-shop-tutorial/migrations/2_deploy_contracts.js:4:14)
    at Migration.<anonymous> (/usr/lib/node_modules/truffle/build/webpack:/packages/migrate/dist/src/Migration.js:86:1)
    at Generator.next (<anonymous>)
    at fulfilled (/usr/lib/node_modules/truffle/build/webpack:/packages/migrate/dist/src/Migration.js:28:43)
    at processTicksAndRejections (internal/process/task_queues.js:95:5)
Truffle v5.6.5 (core: 5.6.5)
Node v14.20.0
```

```bash 
ling@LAPTOP-SIM0A8SC:/usr/local/bin$ sudo ganache-cli 
Ganache CLI v6.12.2 (ganache-core: 2.13.2)

Available Accounts
==================
(0) 0x1552Fc72cA293BdDD98111Be685d26fb6e4b38D4 (100 ETH)
(1) 0x2fe1697e0c89a42e2558dF880285D33e0f297233 (100 ETH)
(2) 0x80ea47ff41F1b8500ba68c70AA0CebeA141E56dA (100 ETH)
(3) 0x7CA7F8B167e0AC8076e41Ce4D0aaeBD900E9595C (100 ETH)
(4) 0xC08b4036763aB0A94aAE05e3ab4f77B10719e390 (100 ETH)
(5) 0x28DAE219CB529637A5A8420c14952C3609B74152 (100 ETH)
(6) 0xd71eAcdA00bAdfa1aA10b8f0d1addFba77C35512 (100 ETH)
(7) 0xf6c97f0578499De5077eab1981F23dcBc7d04931 (100 ETH)
(8) 0xa18f9147Fa37641b15c44CCd296C23Ce6363cc77 (100 ETH)
(9) 0xCFb1A5632b5e6955A6531D68F76418F212D969A9 (100 ETH)

Private Keys
==================
(0) 0xa5f3b9649014f4757d449bad9876ffd879fade2635ca5fe582a304806b5c0937
(1) 0x110b8a10303b587717766b93b3f86b4969ee5ee2ac0e395acb6e16d8d98a5a01
(2) 0x1e3f8c06ae912987a45eb3ada953de059fe04c9428b55c5e8162bf31a8058951
(3) 0x9d18211c274132304dbcad0db35ac4cab2a2a6b5e8bc7ce2e06210f7f402492b
(4) 0x438bcec17b3556f2935004281660d83a44142b620af7d54e705da62a52f4eafb
(5) 0x53a199787fe7b10effbb28c697c33cdbbc75e6aafa676696a53dc55e54e32a14
(6) 0x5ca7e9d3b61fc76307154db5baec4e2f0e363ffa0fda107e0ed3698cbe539d27
(7) 0x679355a18e95d1d08a245b0e33c433e34d7496d6151655c9ee7317de55fcf5f5
(8) 0x4d8bc9a6b098be34e0b0fed83902b81f353ca806e960bbe01251008c7dd793dd
(9) 0xfde15e6b26b919bc44b5cfb1919e279d84b14e916e6db2c61bbbf69b633a20c9

HD Wallet
==================
Mnemonic:      urge misery quiz milk bonus ill sponsor mixture pupil wash lobster coil
Base HD Path:  m/44'/60'/0'/0/{account_index}

Gas Price
==================
20000000000

Gas Limit
==================
6721975

Call Gas Limit
==================
9007199254740991

Listening on 127.0.0.1:8545
eth_blockNumber
net_version
eth_accounts
eth_getBlockByNumber
eth_accounts
net_version
eth_getBlockByNumber
eth_getBlockByNumber
net_version
eth_getBlockByNumber
eth_estimateGas
net_version
eth_blockNumber
eth_getBlockByNumber
eth_estimateGas
eth_getBlockByNumber
eth_gasPrice
eth_sendTransaction

  Transaction: 0xcf6f8635d03206491d34e10d952bc93e411a374abfd29c86669ddbd4d5ec973c
  Contract created: 0x8b71cba7db4d2446489907d9e8293551e6410c47
  Gas usage: 191943
  Block Number: 1
  Block Time: Thu Nov 10 2022 13:46:37 GMT+0800 (China Standard Time)

eth_getTransactionReceipt
eth_getCode
eth_getTransactionByHash
eth_getBlockByNumber
eth_getBalance
eth_getBlockByNumber
eth_getBlockByNumber
eth_estimateGas
eth_getBlockByNumber
eth_gasPrice
eth_sendTransaction

  Transaction: 0x826e8c01dc622ee1e576dce7daef7f5f2072398aa8b8f3828d40e3546390ddbd
  Gas usage: 42338
  Block Number: 2
  Block Time: Thu Nov 10 2022 13:46:37 GMT+0800 (China Standard Time)

eth_getTransactionReceipt
eth_getBlockByNumber
eth_accounts
```
