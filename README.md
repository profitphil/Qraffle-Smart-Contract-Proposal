# Qraffle Smart Contract Proposal

## Introduction

Qraffle is a simple, smart contract-powered raffle system. Unlike Quottery, which places yes/no bets, Qraffle uses Qubic’s native `RANDOM` smart contract to ensure fair and transparent winner selection. Qraffle is designed to serve the Qubic ecosystem by offering a fun, community-driven application with real economic benefits. It’s deflationary, pays dividends, and donates to charity!

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

Key terms defined
- **Reserve:** The amount need to complete a raffle in order to fulfill all required distributions.
- **Purchase Fund:** The fund used to purchase assets from Qx to be used in future raffles.
- **Entries needed:** The amount of raffle entries required to meet reserve and complete a raffle.

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
   - 5% Purchase Fund (qx asset purchases)
   - 3% Shareholders
   - 1% Fees (website, qx, random)
   - 1% Charity (@Kimz300)

4. **Select token for raffle entries**  
5. **Calculate required entries** based on token market price  
6. **Start raffle**  
   - Track progress bar  
   - When reserve is reached(entries needed is met), raffle ends  
   - RANDOM smart contract picks winner  
   - Distribute prize, webhook sent with raffle details and winner 
11. Optional: Enable auto-reload for recurring raffles

---

## Examples

### Example 1
- Prize: 1,000,000 Qubic  
- Entry: 1 Qubic  
- Reserve: 1,200,000 Qubic  
- Entries Needed: 1,200,000
- Distribution:
    - Prize: 1,000,000 Qubic (100%)
    - Burned: 120,000 Qubic (10%)
    - Purchase Fund: 60,000 Qubic (5%)
    - Shareholders: 36,000 Qubic (3%)
    - Fees: 12,000 Qubic (1%)
    - Charity: 12,000 Qubic (1%)

### Example 2
- Prize: 1,000,000,000 Qubic  
- Entry: 10,000 Qubic  
- Reserve: 1,200,000,000 Qubic  
- Entries Needed: 120,000
- Distribution:
    - Prize: 1,000,000,000 Qubic (100%)
    - Burned: 120,000,00 Qubic (10%)
    - Purchase Fund: 60,000,000 Qubic (5%)
    - Shareholders: 36,000,000 Qubic (3%)
    - Fees: 12,000,000 Qubic (1%)
    - Charity: 12,000,000 Qubic (1%)

### Example 3
- Prize: Qswap SC (500M Qubic value)  
- Entry Token: Garth (8 Qubic)  
- Reserve: 600M Qubic  
- Entries Needed: 75,000,000 Garth
- Distribution:
    - Prize: 1 Qswap SC
    - Burned: 60,000,000 Qubic (10%)
    - Purchase Fund: 30,000,000 Qubic (5%)
    - Shareholders: 18,000,000 Qubic (3%)
    - Fees: 6,000,000 Qubic (1%)
    - Charity: 6,000,000 Qubic (1%)

### Example 4
- Prize: CPU (600M Qubic value)  
- Entry Token: QXMR (1 Qubic)  
- Reserve: 720M Qubic  
- Entries Needed: 720,000,000 QXMR
- Distribution:
    - Prize: CPU
    - Burned: 72,000,000 Qubic (10%)
    - Purchase Fund: 36,000,000 Qubic (5%)
    - Shareholders: 21,600,000 Qubic (3%)
    - Fees: 7,200,000 Qubic (1%)
    - Charity: 7,200,000 Qubic (1%)

---

## 6 Active Qraffles Planned

1. 1 Qubic entry → 100k Qubic reward  (auto-reload)
2. 1k Qubic entry → 10M Qubic reward  (auto-reload)
3. 10k Qubic entry → 100M Qubic reward  (auto-reload)
4. 50k Qubic entry → 1B Qubic reward  (auto-reload)
5. 1M Qubic entry → 5B+ Qubic reward or SC asset  
6. Special Raffle → Tangible item or alt-token entry

## Epoch Estimates
**Qubic Burned**
- Small entry raffles (1 and 1000 Qubic) estimate at least 1 raffle completed each day
  - 1 Qubic entry raffle burns 10,000 Qubic = 7 days = 70k Qubic burned
  - 1k Qubic entray burns 1M Qubic x 7 days = 7M Qubic burned
- Remaining raffles are estimated to complete 1 each epoch
  - 10k Qubic entry burns 10M Qubic 
  - 50k Qubic entry burns 100M Qubic 
  - 1M Qubic entry est burns 20M - 1B Qubic (depends on which sc share or Qubic Reward (5B, 10B, etc)
  - Special Raffle burn depends on value of item
- Estimated Minimum Weekly Qubic Burned 250m+ (13B+ annually)

**Charity Donated**
  - 25m+ Qubic each Epoch (1.3B+ annually)
  
---

## Tokens for Entries

When a raffle uses a token(other than qu), the reserve amount must be available/deposited in order to start auciton.
Once raffle is completed, the collect tokens will be sold on Qx to pay for completed raffle.

**Token Deflationary Measures:**
Should a token creator request to burn all or a portion of collected tokens, token creator must pay that portion of reserve. Then that portion of tokens will be burned.

---

## Components to Be Developed

### Frontend UI
- Inspired by Qearn UI
- WalletConnect
- To be hosted at: [https://qraffles.com/](https://qraffles.com/)
- Example preview: [https://www.qxmr.quest/qraffles](https://www.qxmr.quest/qraffles) (Admin UI Password: `admin`)
- Example preview does not represent Serendipity's work. It's a mock version of what it might look like.

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
4. Watch for raffle completion  
5. If selected, prize(Qubic or assets) is sent automatically by Qraffle SC
6. Webhook with raffle results  
7. Tangible prizes require wallet ownership verification and shipping details  

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
- SC development 240 hrs @$60/hr = $14,400
- Frontend + UI development - 120 hrs @$35/hr = $4,200
- Webserver setup/development - $1400
  
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

---
