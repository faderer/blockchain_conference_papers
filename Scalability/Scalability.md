# Layer 2
## Payment Channel
### Perun Virtual Payment Hubs over Cryptocurrencies (S&P 2019)
- instead of routing transaction, create virtual payment channels

## Sidechain
### MAD-HTLC: Because HTLC is Crazy-Cheap to Attack （S&P 2021）
- prevent bribery attack in HTLC utilizing miners as participants
- patch the prevalent Bitcoin Client to create Bitcoin-MEV infrastructure

related work:Temporary censorship attacks in the presence of rational miners

## Optimistic rollup
### Arbitrum Scalable, private smart contracts (USENIX 2018)
- use highly-efficient challenge-based protocol
- provides an any-trust guarantee
- execute contracts privately and publish only (saltable) hashes of contract states
- Arbitrum is consensus-agnostic

roles: verifier, key, VM and manager