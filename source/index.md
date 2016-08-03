# BlockApps API v1.2 API documentation version v1.2
http://hacknet.blockapps.net/eth/v1.2

---

## /faucet
handler: FaucetR

### /faucet

* **post**: Claim ether from the faucet

## /extabi
handler: ExtABIR

### /extabi

* **post**: Get the symbol table associated with a solidity source file.

## /stats

### /stats/difficulty
handler: StatDiffR

* **get**: Get the current total difficulty on the blockchain

### /stats/totaltx
handler: StatTxR

* **get**: Get the current total number of transactions on the blockchain

## /block
handler: BlockInfoR

### /block

* **get**: Query the blocks

### /block/last/{Integer}
handler: BlkLastR

* **get**: Get the last number of blocks

## /log
handler: LogInfoR

### /log

* **get**: Query logs

## /account
handler: AccountInfoR

### /account

* **get**: Query the accounts

## /transaction
handler: TransactionR

### /transaction

* **get**: Query the transaction
* **post**: 
* **options**: 

### /transaction/last/{Integer}
handler: TxLastR

* **get**: Get the last number of transactions

### /transaction/last/queued
handler: QueuedTransactionsR

* **get**: Get queued (unprocessed) transactions

## /transactionResult

### /transactionResult/{SHA}
handler: TransactionResultR

* **get**: Get the status of a transaction by the SHA

## /storage
handler: StorageInfoR

### /storage

* **get**: Query the storage

## /register
handler: RegisterAppR

### /register

* **get**: Confirm that the developer registered an app.
* **post**: Register a new application.

## /login
handler: LoginR

### /login

* **post**: 

## /wallet
handler: WalletR

### /wallet

* **get**: 
* **post**: 

## /developer
handler: DeveloperR

### /developer

* **post**: 

## /coinbase
handler: CoinbaseR

### /coinbase

* **get**: Get the mining coinbase of the

