# Smart Contract
## Parallelization
### iBatch Saving Ethereum Fees via Secure and Cost-Effective Batching of Smart-Contract Invocations (FSE 2021)
- design middleware system on top of unmodified Ethereum network to batch smart contract invocations
- **Security**: use jointly signing to lower the trust overhead
- **Cost-efective**: various batching policies from conservative to aggressive
- automatic rewrite of smart contracts to support batching ([EIP-3074](https://eips.ethereum.org/EIPS/eip-3074))

## Off-chain Execution
### POSE: Practical Off-chain Smart Contract Execution (NDSS 2023)
- TEE-based off-chain execution

## Vulnerability Exploitation
### Smart Contract Vulnerabilities: Vulnerable Does Not Imply Exploited (USENIX Security 2021)
- Datalog-based formalization for performing EVM execution traces
- express six types of vulnerabilities
  - Re-Entrancy (RE)
  - Unhandled Exceptions (UE)
  - Locked Ether (LE)
  - Transaction Order Dependency (TO)
  - Integer Overflow (IO)
  - Unrestricted Action (UA)

