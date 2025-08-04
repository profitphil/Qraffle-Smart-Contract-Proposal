Qraffle Smart Contract Proposal

## Introduction

Qraffle is a simple, smart contract-powered raffle system. It uses Qubic’s native RANDOM sc to ensure fair and transparent winner selection. Qraffle is designed to serve the Qubic ecosystem by offering a fun, community-driven application with real economic benefits. It’s deflationary, pays dividends, and donates to charity! 
To be developed by the innovative Qearn team, Serendipity and Poly. This proposal seeks a funding allocation of $20,000 USD (7.5B Qu @ 0.0000026) to wallet: `GBBDPCKSUDPTAFOIROJCFPRLEPXBJSTMKFONPDVBHBWTPUDVFEKRYPSBLLIA`

Key Features
Fair Winner Selection: Uses Qubic’s RANDOM sc for verifiable, tamper-proof results.
Open Entry: Accepts any Qubic-based token for raffle entries, defaulted to Qubic.
Deflationary Utility: A portion of every raffle is burned, reducing overall Qubic supply.
Dividends: Qraffle distributes a share of earnings to token shareholders.
Charity Support: A set percentage of all proceeds is donated to charitable causes.

Problems Qraffle Solves
Utility for Qubic Tokens → Qraffle gives Qubic tokens new use cases and reasons to hold and spend them.
Inflation Concerns → Qraffle directly combats inflation by burning Qubic from each raffle, supporting the deflationary goals of the network.
Community Engagement → Provides a fun, fair, and repeatable activity that builds on-chain engagement.
Trust in Randomness → Many raffle systems rely on off-chain or opaque RNG. Qraffle uses Qubic's built-in RANDOM, ensuring on-chain, provable fairness.
Social Impact → Donating to real-world causes helps position Qubic as a responsible, community-minded ecosystem.

How Qraffle Benefits Qubic
Increases Qx transaction volume and network usage.
Encourages token diversity by accepting any Qubic token.
Demonstrates real-world use of Qubic’s RANDOM smart contract.
Adds a sustainable way to reduce token supply.
Enhances the Qubic’s credibility by supporting charitable causes
Offers rewards and passive income for long-term holders.

## Business Model

QRaffle Logic:
Choose prize type: 
Qubic, 
Qubic asset (smart contract or token MUST BE PURCHASED OFF QX BEFORE RAFFLE-for value)
actual item (e.g., HASHWallet, CPU, hat, etc).
Calculate prize value in Qubic.
Calculate reserve amount (prize value × 1.2), distributed as: 
100% for raffle prize
10% Qubic burned
5% reserve fund (future prize purchases)
3% shareholders
1% fees (website, qx, random)
1% charity (@Kimz300)
Select token for raffle entries (e.g., Qubic, Garth, CfB, QXMR, Matilda).
Calculate tokens needed: reserve amount ÷ token price.
Click start
Progress bar for entries/required
Once required entries/amount met. Raffle ends. 
SC uses RAMDOM sc to pick winner
Webhook results & Distribution
Auto-reload option (once raffle ends, starts new one with same metrics as previous) 

Example 1
Prize: 1,000,000 Qubic
Entry Token: Qubic (1 Qubic per entry)
Steps:
Prize Type: Qubic
Prize Value: 1,000,000 Qubic
Reserve Amount:
1,000,000 × 1.2 = 1,200,000 Qubic
Distribution:
Prize: 1,000,000 Qubic (100%)
Burned: 120,000 Qubic (10%)
Reserve Fund: 60,000 Qubic (5%)
Shareholders: 36,000 Qubic (3%)
Fees: 12,000 Qubic (1%)
Charity: 12,000 Qubic (1%)
Tokens Needed: 1,200,000 Qubic ÷ 1 Qubic per entry = 1,200,000 entries

Example 2
Prize: 1,000,000,000 Qubic
Entry Token: Qubic (10,000 Qubic per entry)
Steps:
Prize Type: Qubic
Prize Value: 1,000,000,000 Qubic
Reserve Amount:
1,000,000,000 × 1.2 = 1,200,000,000 Qubic
Distribution:
Prize: 1,000,000,000 Qubic (100%)
Burned: 120,000,00 Qubic (10%)
Reserve Fund: 60,000,000 Qubic (5%)
Shareholders: 36,000,000 Qubic (3%)
Fees: 12,000,000 Qubic (1%)
Charity: 12,000,000 Qubic (1%)
Tokens Needed: 1,200,000,000 Qubic ÷ 10,000 Qubic per entry = 120,000 entries

Example 3
Prize: 1 Nostromo SC (purchased on QX, valued at 500,000,000 Qubic)
Entry Token: Garth token (market value 8 Qubic)
Steps:
Prize Type: Qubic asset (smart contract)
Prize Value: 500,000,000 Qubic
Reserve Amount:
500,000,000 × 1.2 = 600,000,000 Qubic
Distribution:
Prize: 1 Nostromo SC
Burned: 60,000,000 Qubic (10%)
Reserve Fund: 30,000,000 Qubic (5%)
Shareholders: 18,000,000 Qubic (3%)
Fees: 6,000,000 Qubic (1%)
Charity: 6,000,000 Qubic (1%)
Token for Entries: Garth token
Token Market Price: 1 Garth = 8 Qubic
Tokens Needed: 600,000,000 Qubic ÷ 8 Qubic per Garth = 75,000,000 Garth tokens
Example 4
Prize: CPU (valued at 600,000,000 Qubic)
Entry Token: QXMR token (market value 1 Qubic)
Steps:
Prize Type: Actual item (CPU)
Prize Value: 600,000,000 Qubic
Reserve Amount:
600,000,000 × 1.2 = 720,000,000 Qubic
Distribution:
Prize: CPU
Burned: 72,000,000 Qubic (10%)
Reserve Fund: 36,000,000 Qubic (5%)
Shareholders: 21,600,000 Qubic (3%)
Fees: 7,200,000 Qubic (1%)
Charity: 7,200,000 Qubic (1%)
Token for Entries: QXMR token
Token Market Price: 1 QXMR = 1 Qubic
Tokens Needed:
720,000,000 Qubic ÷ 1 Qubic per QXMR = 720,000,000 QXMR tokens


6 Active Qraffles (5 Qubic token entry, 1 alt token entry):
1 Qubic entry (100k Qubic reward) auto-reload
1k Qubic entry (10m Qubic reward) auto-reload
10k Qubic entry (100m Qubic reward) auto-reload
50k Qubic entry (1b Qubic reward) auto-reload
1m Qubic entry (10b Qubic reward or SC asset)
Special Raffle (cpu, alt token entries)


TOKEN OWNERS
If token owner wants to have a raffle use their tokens as entries, they must:
Pay 10m Qubic fee (to be burned)
Supply 20% reserve fee
Tokens collected for raffle entries will be:
Burned, sold, or returned to token creator


## Components to Be Developed (High-Level)

### Frontend UI:
- Similar with Qearn UI.
- WalletConnect
Hosted at [https://qraffles.com/]
alpha examples can be seen at https://www.qxmr.quest/raffles
There is an Admin link on each (password: admin)

***Example UI (UI mockup - not representative of Serendipity's work. UI will resemble Qearn’s***)


### Smart Contract:
Raffle logic
Burn mechanism
Distribution of Qubic rewards 

## Technical Architecture (High-Level)
- **Smart Contract:** C++
**Frontend:** React + Vite + Qubic Connect


## User Journey/Examples

User connects wallet with wallet connect
Pick which raffle they want to enter
Sends desired amount of entries
No limit on entries 
If entry is 1 Qubic and user sends 100 qu, they have 100 entires, etc
If user is selected as winner, Qraffle automatically transfers rewards/asset to wallet
Webhook contains raffle results 
If reward is tangible (cpu, shirt) user must check webhook and verify ownership of wallet (send 1 qu?)
Once verified, arrangements made for shipping, etc


## Detailed Scope and Timeline

### Timeline (6-8 weeks):
- **Week 1:** Design UI mockups and smart contract architecture
- **Week 2-3:** Prototype with raffle and reward functionality
- **Week 4-6:** Smart contract integration and final testing
- **Week 7-8:** Audit, IPO, and Mainnet deployment

## Milestones and Deliverables

**Milestone 1 (1 Week):**
- Create user interface mockup without logic implementation
- Smart contract architecture docs

**Milestone 2 (3 Weeks):**
- Wallet connect
- Qubic core services integration
- Develop a functional prototype implementing staking and reward distribution features
- Smart contract first version

**Milestone 3 (2 Weeks):**
- Integration of UI with smart contract
- Final smart contract with possible updates for providing better data and interaction with UI
- Smart contract test script

**Milestone 4 (2 Weeks):**
- Audit, IPO, and Mainnet deployment

## Payment Terms

**Funding Request:** $20,000 USD
- Breakdown: 100% for devs

**Disbursement**
- 20% M1: UI mockup (without functionalities), smart contract docs
- 30% M2: Alpha version of UI and smart contract
- 20% M3: All test finished beta version
- 30% M4: Mainnet deployment

## Team Composition

- **Profitphil:** Team Lead
- **Serendıpıtч:** Lead frontend UI developer
- **Poly:** Lead smart contract developer

-Website: https://www.qxmr.quest
-X: @_qxmr_token_
