# tixl-testnet-status
Gives an insight into where we are standing with the Tixl testnet development.

We have set up a channel #github on our Discord server (https://discordapp.com/invite/dzVzMdp) where all commit messages are shared. 

Further tasks are tracked in the Issues Tab.


## Completed parts

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
- [ ] Handle further Edge-Cases

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

## Next Steps after first testnet release

- Faucet to get Testnet Tokens
- Generate Keys from mnemonic phrase
- Mini PoWs
- Load tests
- Cut through transactions
- Network privacy
- Start Mainnet development
