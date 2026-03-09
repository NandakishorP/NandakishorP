# Smart Contract Engineer

Building institutional-grade lending and credit protocols.
Focused on correctness, accounting invariants, and security
under adversarial conditions.

---

## What I Work On

Protocol-level problems in lending and structured finance —
state consistency, waterfall accounting, loss handling, and
failure recovery across complex multi-contract systems.

My work spans the full stack: protocol design → implementation
→ exhaustive testing → security analysis.

---

## Core Skills

**Protocol Design & Solidity**
- Lending, tranching, and credit protocol architecture
- Structured finance primitives (waterfalls, interest indexing,
  share-based accounting)
- Upgrade-safe patterns (UUPS, storage layout safety)
- Cross-contract coordination and invariant-aware design

**Zero-Knowledge Systems**
- Noir circuits (UltraHonk / Barretenberg)
- ZK-Solidity integration (public input binding, Field type
  boundary handling)
- Schnorr signatures over Grumpkin curve

**Testing & Verification**
- Foundry: unit, fuzz, stateful invariant testing
- Echidna and Medusa for property-based fuzzing
- Custom invariant handlers with ghost accounting
- Economic modeling and conservation law validation (Python)

**Security**
- Accounting and rounding safety
- Admin and governance attack surfaces
- Economic stress testing and adversarial flow design
- Cross-chain failure modes and async execution risks

---

## Selected Work

### Credit Rail — Institutional Private Credit Protocol
ZK-verified on-chain credit infrastructure for institutional
borrowers. Borrower financial data stays entirely off-chain.
A Noir circuit proves policy compliance against a frozen credit
policy without revealing any underlying data.

- Three-tranche structured pool (Senior / Junior / Equity)
  with waterfall interest distribution and loss absorption
- Schnorr over Grumpkin for underwriter attestation (~10x
  fewer constraints than secp256k1 ECDSA)
- 17 protocol-level invariants tested across Foundry,
  Echidna, and Medusa
- UUPS upgradeable, deployed on zkSync Era

### Cross-Chain Lending Protocol
Deposit collateral on one chain, borrow on another via CCIP.
Explicit state synchronization with failure-aware message
handling and recovery flows. Exploring ZK proof transmission
for cross-chain RWA systems.

---

## Availability

30 hrs/week. Comfortable owning features end-to-end:
design → implementation → testing → review.

**Solidity · Noir · Foundry · Echidna · Medusa · CCIP**
