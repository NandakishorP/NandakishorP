# 💫 About Me

Smart contract engineer building institutional DeFi protocols | Focused on correctness, security, and stateful systems

I work primarily on **lending and credit protocols**, where the hard problems aren’t business logic but **state consistency, accounting invariants, and failure handling** across time, users, and chains. I prioritize correctness over velocity so systems **hold up under adversarial conditions**.

Most of my time goes into:
- Designing protocol flows
- Writing exhaustive tests (unit → fuzz → invariant)
- Reasoning about edge cases, loss scenarios, and admin risk
- Understanding how assumptions fail in production


---

## 🧠 Core Skills

### Smart Contracts & Protocol Design
- Solidity (production-grade patterns)
- Noir and ZK Proofs
- Invariant testing and stress testing models
- Stateful protocol design (lending, tranching, accounting)
- Cross-contract and cross-module coordination
- Upgrade-safe and invariant-aware architectures

### Testing & Verification
- Foundry: unit, fuzz, and invariant testing
- Custom invariant handlers & adversarial flows
- Failure-first testing mindset
- Familiar with formal verification concepts (Certora-style specs)

### Security
- Accounting & rounding safety
- Admin & governance risk analysis
- Oracle & external dependency failure modes
- Cross-chain & async execution risks
- Economic modelling and stress testing

### Cross-Chain Systems
- CCIP architecture & message lifecycle
- State mirroring & synchronization guarantees
- Failure handling for delayed, reordered, or missing messages
- Designing for partial execution & recovery

### Tooling & Infra
- Foundry, Hardhat
- ethers.js, wagmi
- Subgraph indexing (GraphQL)
- Gas profiling & basic Yul optimizations
- Barretenberg and nargo

---

## 🏗️ Ongoing Work

### Credit / Tranche-Based Lending System
- Senior / junior / equity tranches
- Loss waterfalls and recovery handling
- Interest indexing with share-based accounting
- Extensive invariant and fuzz testing
- Python economic modeling for stress scenarios

### Cross-Chain Lending Protocol
- Deposit collateral on one chain, borrow on another
- Explicit state synchronization across chains
- Failure-aware message handling
- Heavy focus on invariants and edge-case correctness
- Experimenting with sending proofs between chains and rwa systems

---

## 🔍 What I’m Going Deep On

- Protocol-level invariants and failure modeling
- Advanced fuzzing & invariant testing strategies
- Gas-aware design tradeoffs
- Governance and admin attack surfaces
- Zero-knowledge systems (Noir), from a protocol-integration perspective


---

## 🧩 Mental Model

I approach protocols like distributed systems:
- Every external call can fail
- Every assumption will be violated
- Every invariant must hold under adversarial input

If it survives fuzzing, invariants, and bad actors — then it’s interesting.


---

## 🚀 Availability


Available 25hrs/week

Comfortable owning a feature end-to-end:
**design → implementation → tests → review**

---

## 💻 Tech Stack

**Solidity · Foundry · Noir · NextJS · GraphQL · Next.js**  
**Unit / Fuzz / Invariant Testing · Protocol Security · Cross-Chain Systems**
