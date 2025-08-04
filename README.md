# Qraffle Smart Contract Proposal

## Introduction

Qraffle is a simple, smart contract-powered raffle system. It uses Qubic’s native `RANDOM` smart contract to ensure fair and transparent winner selection. Qraffle is designed to serve the Qubic ecosystem by offering a fun, community-driven application with real economic benefits. It’s deflationary, pays dividends, and donates to charity!

To be developed by the innovative Qearn team, Serendipity and Poly.  
**Funding Request:** $20,000 USD (7.5B Qu @ 0.0000026)  
**Destination Wallet:** `GBBDPCKSUDPTAFOIROJCFPRLEPXBJSTMKFONPDVBHBWTPUDVFEKRYPSBLLIA`

---

## Key Features

- **Fair Winner Selection:** Uses Qubic’s `RANDOM` smart contract for verifiable, tamper-proof results.
- **Open Entry:** Accepts any Qubic-based token for raffle entries, defaulted to Qubic.
- **Deflationary Utility:** A portion of every raffle is burned, reducing overall Qubic supply.
- **Dividends:** Qraffle distributes a share of earnings to token shareholders.
- **Charity Support:** A set percentage of all proceeds is donated to charitable causes.

---

## Solutions Offered by Qraffle

- **Utility for Qubic Tokens**  
  → Qraffle gives Qubic tokens new use cases and reasons to hold and spend them.

- **Inflation Concerns**  
  → Qraffle combats inflation by burning Qubic from each raffle.

- **Community Engagement**  
  → Provides a fun, fair, and repeatable activity that builds on-chain engagement.

- **Trust in Randomness**  
  → Uses Qubic’s built-in `RANDOM`, ensuring on-chain, provable fairness.

- **Social Impact**  
  → Donates to real-world causes, positioning Qubic as a community-minded ecosystem.

---

## How Qraffle Benefits Qubic

- Increases QX transaction volume and network usage.
- Encourages token diversity by accepting any Qubic token.
- Demonstrates real-world use of Qubic’s RANDOM smart contract.
- Adds a sustainable method to reduce token supply.
- Enhances Qubic’s credibility through charitable giving.
- Offers rewards and passive income for long-term holders.

---

## Business Model

### Qraffle Logic

1. **Choose prize type:**
   - Qubic
   - Qubic asset (must be purchased via QX)
   - Actual item (e.g., CPU, merchandise)

2. **Calculate prize value** in Qubic.
3. **Calculate reserve amount** (Prize × 1.2)  
   Distributed as:
   - 100% Prize
   - 10% Burned
   - 5% Reserve Fund
   - 3% Shareholders
   - 1% Fees
   - 1% Charity

4. **Select token for raffle entries**  
5. **Calculate required entries** based on token market price  
6. **Start raffle**  
7. **Track progress bar**  
8. When full, raffle ends  
9. RANDOM smart contract picks winner  
10. Distribute prize, update webhook  
11. Optional: Enable auto-reload for recurring raffles

---

## Examples

### Example 1
- Prize: 1,000,000 Qubic  
- Entry: 1 Qubic  
- Reserve: 1,200,000 Qubic  
- Entries Needed: 1,200,000

### Example 2
- Prize: 1,000,000,000 Qubic  
- Entry: 10,000 Qubic  
- Reserve: 1,200,000,000 Qubic  
- Entries Needed: 120,000

### Example 3
- Prize: Nostromo SC (500M Qubic value)  
- Entry Token: Garth (8 Qubic)  
- Reserve: 600M Qubic  
- Entries Needed: 75,000,000 Garth

### Example 4
- Prize: CPU (600M Qubic value)  
- Entry Token: QXMR (1 Qubic)  
- Reserve: 720M Qubic  
- Entries Needed: 720,000,000 QXMR

---

## Active Qraffles (Autoload Options)

1. 1 Qubic entry → 100k Qubic reward  
2. 1k Qubic entry → 10M Qubic reward  
3. 10k Qubic entry → 100M Qubic reward  
4. 50k Qubic entry → 1B Qubic reward  
5. 1M Qubic entry → 10B reward or SC asset  
6. Special Raffle → Tangible item or alt-token entry  

---

## Token Owner Participation

- Fee: 10M Qubic (burned)
- Supply: 20% reserve fund
- Collected tokens: Burned, sold, or returned to creator

---

## Components to Be Developed

### Frontend UI
- Inspired by Qearn UI
- WalletConnect
- Hosted at: [https://qraffles.com/](https://qraffles.com/)
- Alpha previews: [https://www.qxmr.quest/raffles](https://www.qxmr.quest/raffles) (Password: `admin`)

### Smart Contract
- Raffle logic
- Qubic burn function
- Distribution mechanics

---

## Technical Architecture

- **Smart Contract:** C++ (Qubic environment)  
- **Frontend:** React + Vite + Qubic Connect  

---

## User Journey

1. Connect wallet with WalletConnect  
2. Select a raffle  
3. Send entries (no limit)  
4. Wait for completion  
5. If selected, prize is sent automatically  
6. Webhook updates results  
7. Tangible prizes require ownership verification and shipping details  

---

## Detailed Scope and Timeline

### Estimated Duration: 6–8 Weeks

| Week     | Milestone                                  |
|----------|---------------------------------------------|
| 1        | UI mockups, contract architecture docs      |
| 2–3      | Alpha prototype, basic reward logic         |
| 4–6      | Smart contract integration, testing         |
| 7–8      | Audit, IPO, mainnet launch                  |

---

## Milestones and Deliverables

### Milestone 1 (20%)
- UI mockup (no logic)
- Smart contract architecture

### Milestone 2 (30%)
- WalletConnect
- Core integrations
- Alpha prototype
- SC v1

### Milestone 3 (20%)
- Full integration
- Updated smart contract
- Testing script

### Milestone 4 (30%)
- Audit
- IPO and launch

---

## Payment Terms

**Total Request:** $20,000 USD  
**Disbursement:**
- M1 – 20%  
- M2 – 30%  
- M3 – 20%  
- M4 – 30%  

---

## Team Composition

- **Profitphil** – Team Lead  
- **Serendıpıtч** – Lead Frontend UI Developer  
- **Poly** – Lead Smart Contract Developer  

**Website:** [https://www.qxmr.quest](https://www.qxmr.quest)  
**X (Twitter):** [@_qxmr_token_](https://x.com/_qxmr_token_)

---
