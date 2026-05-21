# YetiWork 🚀
### Programmable Trust for Global Freelance Work

**YetiWork** is a decentralized freelance escrow platform built on the **Sui ecosystem**. It protects both freelancers and clients using programmable smart contracts, encrypted deliverable vaults, and immutable on-chain proof-of-delivery.

By eliminating expensive intermediaries and replacing them with trustless code, YetiWork ensures that freelancers get paid for their work and clients receive exactly what they paid for—faster, cheaper, and more securely.

---

## 🔴 The Problem: The "Trust Gap" in Global Freelancing

The modern freelance economy (worth $450B+) still relies on centralized platforms (Upwork, Fiverr) that act as "digital police." This creates several pain points:

- **Ghosting:** Clients disappear after receiving final work without paying.
- **Predatory Fees:** Platforms take 10-20% of the freelancer's hard-earned income.
- **Unfair Disputes:** Centralized arbitration is often slow, opaque, and biased toward whoever spends more.
- **Payment Latency:** International bank transfers take days and lose value through poor exchange rates.
- **Verification Fraud:** No immutable way to prove *when* and *what* was actually delivered.

---

## 🟢 The Solution: YetiWork Infrastructure

YetiWork replaces "Centralized Trust" with **"Programmable Trust."**

### 🧠 Sui — The Brain (Smart Escrow)
Every project on YetiWork is a **Sui Object**. 
- **Non-Custodial Escrow:** Funds are locked in a smart contract, not held by a company.
- **Programmable Logic:** Payments are released automatically based on milestones, deadlines, or multisig approvals.
- **Fast & Cheap:** Leveraging Sui’s parallel execution for near-instant agreement updates.

### 🛡️ Walrus — The Vault (Encrypted Proof-of-Delivery)
Large deliverables (Source code, 4K Video, High-res designs) are stored on **Walrus**.
- **Cryptographic Evidence:** Freelancers upload work to Walrus, generating a permanent blob ID.
- **Encrypted Access:** Files are encrypted; the decryption key is only released via the Sui smart contract once the client confirms payment or a milestone is met.
- **Immutability:** Clients cannot claim "I didn't receive the file" if the blob ID is recorded on-chain.

### 💹 DeepBook — The Bank (Instant Settlement)
Global work needs global currency flexibility.
- **Cross-Token Payments:** A client can pay in SUI, while the freelancer receives USDC or their preferred stablecoin.
- **Deep Liquidity:** DeepBook handles the back-end conversion instantly with minimal slippage, protecting freelancers from crypto volatility.

---

## ✨ Key Features

- **zkLogin Onboarding:** Log in using Google/Apple/Twitch—no seed phrases required for non-crypto users.
- **Sponsored Transactions:** Clients/Brands can pay for gas fees, making the platform feel like a standard Web2 app.
- **Milestone-Based Streaming:** Funds are released in stages as work progresses.
- **Immutable Timeline:** Every revision and message is timestamped on-chain for dispute evidence.
- **Auto-Settlement:** If a client doesn't "Approve" or "Dispute" within a set timeframe, funds are automatically released to the freelancer.

---

## 🛠️ Tech Stack

| Layer | Technology | Role |
|---|---|---|
| **Blockchain** | **Sui Network** | Logic, Escrow, and Ownership |
| **Storage** | **Walrus** | Decentralized storage for large deliverables |
| **Liquidity** | **DeepBook (CLOB)** | Instant token conversion and settlement |
| **Smart Contracts** | **Sui Move** | Programmable escrow and project objects |
| **Frontend** | **Next.js 14 / TypeScript** | Core Application UI |
| **Styling** | **Tailwind CSS** | Modern and responsive design |
| **Authentication** | **Sui zkLogin** | Seamless Web2-to-Web3 onboarding |

---

## 🔄 How It Works (The Workflow)

1. **Agreement:** Client creates a project, defines milestones, and locks SUI/USDC into the **YetiWork Escrow Contract**.
2. **Execution:** Freelancer starts working. Progress is tracked via on-chain milestones.
3. **Delivery:** Freelancer uploads the final asset to **Walrus**. The system generates an encrypted blob and records the proof on Sui.
4. **Verification:** Client receives a notification. They can view a preview or low-res version.
5. **Settlement:** 
   - Client clicks "Approve" -> Payment is released.
   - If a different token is needed, **DeepBook** swaps it mid-flight.
   - Decryption key is handed over to the client automatically.

---

## 📈 Scalability & Sustainability

- **Architecture:** Built using Sui’s object-centric model, allowing the platform to handle thousands of concurrent projects without congestion.
- **Cost Efficiency:** Using Walrus for storage is significantly cheaper than any other decentralized or on-chain storage solution.
- **Adoption:** Designed with a "Web2-first" UX focus to capture the 99% of freelancers who aren't yet in crypto.

---

## 🗺️ Roadmap

- [ ] **Phase 1:** Core Escrow Move Contract & Walrus Integration (MVP).
- [ ] **Phase 2:** DeepBook Auto-Swap integration for multi-currency support.
- [ ] **Phase 3:** AI-Powered Dispute Analyzer (Analyzing Walrus-stored chat logs).
- [ ] **Phase 4:** Decentralized Reputation System (On-chain Freelancer CV).

---

## 💡 Lessons Learned

- **Sui Move**'s ability to treat assets as objects makes escrow logic much safer than EVM-based "Account" models.
- **Walrus** is the missing piece for Web3 freelance platforms, solving the "Proof of Delivery" problem for large files.
- **UX is King:** For global adoption, the blockchain must stay in the background.

---

**Developed for the Lofi the Yeti Hackathon.**
*Bridging the gap between creative freedom and programmable trust.*
