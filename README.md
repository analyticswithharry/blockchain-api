# Blockchain API Lab

Build blockchain integration APIs for wallet reads, signed transactions, and chain state tracking.

## Core concepts

- Wallet and account abstractions
- Signed transaction submission flow
- Nonce, gas, and confirmation lifecycle
- Pending vs finalized transaction states
- Provider failover and chain error handling

## Suggested Stack

- Web3 libraries + provider SDK (testnet first)

## Learning Tasks

- Read balances and transaction history
- Submit signed testnet transactions
- Track confirmation status updates
- Handle nonce collisions and gas strategy
- Add structured chain error responses

## Validation checklist

- [ ] Transaction signing flow is correct
- [ ] Confirmation polling/subscription works
- [ ] Nonce and gas logic is tested
- [ ] Failure states are mapped clearly
