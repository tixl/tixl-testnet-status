# tixl-prototype-status
Gives an insight into where we are standing with the Tixl prototype development.

We have set up a channel #github on our Discord server (https://discordapp.com/invite/dzVzMdp) where all commit messages are shared. 

### Crypto 
Repository: tixl-crypto
- [x] NTRU basic setup (encryption) 
- [x] Signatures
- [x] Commitment scheme basic setup
- [x] Commitment scheme range proofs
- [ ] NTRU advanced settings

### Ledger
Repository: tixl-ledger
- [x] Interface
- [x] Data Structure
- [x] Persistence
- [x] Implement validation
- [ ] Import and Export (🔜)


### Gateway
Repository: tixl-gateway
- [x] Distribute transactions to validator network
- [x] Connection to validators (subscription)
- [ ] Implement API (🔜)


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
- [x] recover from stuck states
- [x] State Synchronisation 
- [ ] Integrate with ledger (🔜)
- [ ] Validate transactions 
- [ ] Interface to get state for wallets
- [ ] Deploy test network

### Bot Wallet
- [ ] Create basic operations to interact with Gateway
- [ ] Implement automatic clients, that generate transactions
- [ ] Subscribe to transactions

### Explorer
- [ ] Fetch transactions from network (🔜)
- [ ] Build GUI (🔜)

## Next Steps after first prototype release
- GUI Wallet for everyone to test
- Generate Keys from mnemonic phrase
- Mini PoWs
- Load tests
- Cut through transactions
- Network privacy
- Start Mainnet
