# tixl-testnet-status
Gives an insight into where we are standing with the Tixl testnet development.

We have set up a channel #github on our Discord server (https://discordapp.com/invite/dzVzMdp) where all commit messages are shared. 

Development updates are shared on [Discord](https://discord.gg/dzVzMdp), [Telegram](https://t.me/tixlcurrency) and [Twitter](https://twitter.com/tixlcurrency). Join our channels to stay up to date.

## Completed parts testnet version "Blankenese"
To learn more about this release, read the corresponding medium article: 
[Autobahn Network Testnet “Blankenese”](https://medium.com/tixlcurrency/autobahn-network-testnet-blankenese-4250e7171e7c)

### General
- [x] Refactoring
- [x] Websockets

### GUI Wallet
Repository: tixl-wallet
- [x] Improve usability / UX
- [x] Improve state handling
  - Already a lot of the state handling has been refactored but we are still in the final refactoring steps.
- [x] StealhChains
  - Transactions are already written to StealthChains and we are in the final testing.
  - At the moment we have one StealthChain per asset instead per sender/receiver combination which has to be done, too.
- [x] Shorter addresses (BIP-39 compatible)
- [x] Use High-Level Ledger API
- [x] Show transaction hash
- [x] Key handling (allow restore wallet from private key)
- [x] Show invalid blocks
- [x] Error handling (e.g. not enough balance, invalid block)

### Deployment & Infrastructure
- [x] Internal Development Testnet

### Ledger
Repository: tixl-ledger
- [x] Provide High-Level API
- [x] Allow (encrypted) transaction payload

## Completed parts testnet version "Altona"
To learn more about this release, read the corresponding medium article: 
[Autobahn Network Testnet “Altona”](https://medium.com/tixlcurrency/tixl-testnet-rc-altona-e3198c88af02)

### Crypto for browser
- [x] NTRU Web Assembly
- [x] AES Web Assembly
- [x] Perdersen Commitments Web Assembly
- [x] export to module
 
### GUI Wallet
- [x] Build UI
- [x] Handle State
- [x] Connect to Testnet

### Deployment & Infrastructure
- [x] Deploy Validator test setup
- [x] Deploy Gateway
- [x] Deploy Witness Node
- [x] Deploy Wallet Bots
- [x] Deploy Explorer
- [x] Make all services available via domain
- [x] Make services available with SSL
- [x] Deploy GUI Wallet
- [x] Faucet to get Testnet Tokens

### Crypto 
Repository: tixl-crypto
- [x] NTRU basic setup (encryption) 
- [x] Signatures
- [x] Commitment scheme basic setup
- [x] Commitment scheme range proofs
- [x] NTRU advanced settings
- [x] NTRU Web Assembly Port

### Ledger
Repository: tixl-ledger
- [x] Interface
- [x] Data Structure
- [x] Persistence
- [x] Implement validation
- [X] Import and Export
- [X] Encrypted transactions

### Gateway
Repository: tixl-gateway
- [x] Distribute transactions to validator network
- [x] Connection to validators (subscription)
- [x] Implement API

### Consensus 
Repository: tixl-consensus
- [x] Federated Byzantine Agreement
- [x] Implement SCP protocol
- [x] Run simulations
- [x] Handle further Edge-Cases

### Validator Nodes 
Repository: tixl-validator
- [x] Integrate with consenus
- [x] Generate Keypairs
- [x] Sign and Validate messages
- [x] Build HTTP Interface
- [x] Implement P2P Communication
- [x] Receive transactions
- [x] Hand off transactions to consensus as hash
- [x] Broadcast transcations to other validators
- [x] Witness mode
- [x] Recover from stuck states
- [x] State Synchronisation 
- [x] Integrate with ledger
- [x] Validate transactions 
- [x] Interface to get state for wallets
- [x] Deploy test network

### Bot Wallet
Repository: tixl-wallet-bots
- [x] Create basic operations to interact with Gateway
- [x] Implement automatic clients, that generate transactions
- [x] Subscribe to transactions

### Explorer
Repository: tixl-explorer
- [X] Fetch transactions from network (subscription)
- [X] Build GUI
- [X] Fetch transactions from network (history)
- [X] Improve GUI

## Next Steps after Cranz testnet release

- Generate Keys from mnemonic phrase
- Mini PoWs
- Load tests
- Cut through transactions
- Network privacy
- Start Mainnet development
