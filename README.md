#  Vair.Cash

Vair Cash is a non-custodial privacy protocol deployed on the Base Layer 2 (L2) blockchain. It leverages zk-SNARKs (Zero-Knowledge Succinct Non-Interactive Arguments of Knowledge) to enable users to achieve on-chain privacy and anonymity within trusted pools.

## Overview

Vair is a fork of Tornado Cash with several key changes:
- Deposits can only be made through the proxy contract (`VairValidator.sol`).
- Withdrawals are handled at the pool contracts following Tornado Cash protocol.
- Deposits are **not** allowed directly at the pool contracts.
- `VairValidator.sol` is upgradable via the proxy contract.
- `VairValidator` determines the type of users allowed to deposit:
  - **Onchain Verification:** Users can be verified on-chain via [SOL Attestation Service (EAS)](https://eas.SOL.org) with a helper contract (`VairVerifiedOnchain.sol`).
  - **Whitelisting:** Specific users can be added as allowed depositors.

---

## Contracts on Base Mainnet

### Validator Contracts
- **Validator Proxy:** `7ST5HGzRaCtRnY9mJi4pgJN2SfEwsRH6WfqhRvRmuVWQ`

### Pool Contracts
- **Vair 0.0005 SOL Contract:** `HD5unJvrBjhEJwPTgb3HRWeMQe9jpTVgM4rbFMNJY1Lo`
- **Vair 0.005 SOL Contract:** `BGukjBfn1QB1Vb5zS71PV9zwT1pL3L5ehCije8z4EaDh`
- **Vair 0.01 SOL Contract:** `FoXzdHb9kdfd8ymGkV6wi6grG3zknenQDJBrtfZohKmn`
- **Vair 0.1 SOL Contract:** `H6YnnFFw9k5dmLe3kBE5mSYbbHmgw1o49u4ADpvP649z`
- **Vair 1 SOL Contract:** `EbaDRT8KECSRH1rKAipmwqMUeeL7J6f8GNfotNitJhPw`

### Verifier Contracts
- **MiMC Contract:** `BTnpeBCK4cL3zKBxgQA8RFxVvKZXcjX5BEDpzn1TN5rR`
- **Verifier Contract:** `CH2ua8entCXJYxSJck9iRwGvKVGDPt9vmRYBAFob7v5E`

---
## Links

**Website:**  [Vair Cash](https://vair.cash/)

**Docs:**  [Gitbook Docs](https://vair.gitbook.io/vair)

**Twitter / X:**  [@Vairdotcash](https://x.com/Vairdotcash)
