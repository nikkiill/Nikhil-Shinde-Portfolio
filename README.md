# The Laundromat — AML Detection Simulator

> You have £1,000,000 in criminal proceeds. Can you clean it across three stages without triggering a Suspicious Activity Report to the NCA?

**Play it →** [your GitHub Pages link]

## What it is

An interactive educational simulation of the three-stage money laundering process — Placement, Layering, Integration — with AML detection systems responding to each decision in real time.

Every scenario maps to documented typologies from FATF guidance, the NCA Annual SARs Report 2024 and the FCA Financial Crime Guide. Regulatory references are cited after every choice.

## How it works

- **3 stages**, each with 3 choices at different risk levels
- Each choice carries a **detection heat score** — visible before you commit
- High-risk choices trigger real detection system responses (structuring alerts, MLRO escalations, SAR filings)
- Accumulate enough heat → NCA alert fires, SAR is submitted, game ends
- After each choice: **Compliance Insight** explains exactly how real AML systems would respond

## Regulatory frameworks covered

| Reference | Topic |
|-----------|-------|
| FATF Typology 7 | Smurfing / structured deposits |
| JMLSG Guidance Part I Ch 4 | Cash-intensive business placement |
| MLR 2017 Reg 37 | CTF threshold monitoring |
| POCA 2002 s.327-330 | Criminal property offences |
| POCA 2002 s.335-336 | NCA consent regime |
| FATF Recommendation 16 | Travel Rule (crypto) |
| Economic Crime Act 2022 | Register of Overseas Entities, UWOs |
| NCA Annual SARs Report 2024 | 901,255 SARs filed in 2023-24 |
| Law Society AML Guidance 2023 | Conveyancing Source of Funds |

## Tech

Vanilla HTML, CSS, JavaScript. No frameworks. No backend. No build step.
Open the file — it runs.

## Author

**Nikhil Shinde** — Product & Operations Analyst | KYC/AML Product Owner  
[LinkedIn](https://linkedin.com/in/nikhil-shinde-55a0a210b) · [Portfolio](https://nikhil2617shinde.netlify.app)

Prior experience: KYC/AML product ownership at Microkred Technologies (Svatantra Microfinance, SBM Bank, Lyra Network, Relipay) · Product & Operations at LV=
