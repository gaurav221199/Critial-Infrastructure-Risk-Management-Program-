# Critical Infrastructure Risk Management Program (CIRMP)
### A scenario-based build for an APRA-regulated ADI — *SoCI Act × APRA CPS 230*

A self-directed governance, risk and compliance project that builds a complete, board-facing **Critical Infrastructure Risk Management Program** for a fictional mid-tier Australian bank, **Tasman Mutual Bank (TMB)**. The program is built under the **Security of Critical Infrastructure (SoCI) Act CIRMP Rules** and deliberately **harmonised with APRA CPS 230**, so a single program satisfies both regimes.

> **Scope & honesty note.** Tasman Mutual Bank and all data are **fictional**. This is a **self-directed, scenario-based** practitioner exercise built to demonstrate capability against current Australian regulation — not paid client work, and not a representation of any real entity. Ratings, findings and timelines are illustrative of a realistic mid-tier ADI.

---

## What this project demonstrates

- **All-hazards risk management** across the four SoCI hazard vectors — cyber & information security, personnel, supply chain, and physical & natural.
- **Third-party / supply-chain risk (TPRM)** — a material service provider register with CPS 230 register fields, provider tiering, fourth-party mapping, concentration analysis, and a **FOCI (Foreign Ownership, Control or Influence)** assessment.
- **Dual-regime fluency** — a line-by-line **CPS 230 ↔ SoCI** obligation cross-map showing where the regimes converge and where SoCI adds a national-security lens.
- **Cyber maturity assessment** — scoring against the **ASD Essential Eight Maturity Model** with a current-vs-target view and an uplift roadmap.
- **Board governance & reporting** — a formal CIRMP program document and a board-attested annual report (RBA submission) with an executive risk dashboard.

## Regulatory basis

| Regime | Role in the project |
|---|---|
| **SoCI Act — CIRMP Rules (s8–s11)** | The four hazard vectors and the program obligation |
| **APRA CPS 230** | Operational risk & material service provider management (supply-chain cross-map) |
| **APRA CPS 234** | Information security (supporting) |
| **ASD Essential Eight** | The adopted cyber security framework (ML-1 floor → ML-2 target) |
| **ISO 31000** | Risk management methodology |

Designed toward the **2026 draft CIRMP amendments** — Maturity Level 2, supply-chain dependency/vulnerability mapping, personnel security plans with AusCheck-style screening, and FOCI / vendor-of-concern management — and the SoCI Independent Review's direction to harmonise SoCI with APRA, ISO and NIST.

## The document set

| # | Document | What it is |
|---|---|---|
| 01 | Scope & Engagement Brief | The entity, asset, critical operations, regulator split (RBA/APRA/CISC) and assumptions |
| 02 | All-Hazards Risk Register | 16 risks across the four vectors, inherent→residual scoring, 30/90/180-day treatment, dashboard |
| 03 | Essential Eight Maturity Assessment | Cyber module (s8): current vs ML-1/ML-2, gaps, uplift roadmap |
| 04 | Supply-Chain Hazard Module & MSP Register | TPRM (s10): 11 providers, CPS 230 fields + SoCI flags, CPS 230↔SoCI cross-map, FOCI assessment |
| 05 | Personnel & Physical/Natural Hazard Modules | Vectors s9 and s11: control areas, current state, gaps |
| 06 | CIRMP Program Document | The board-facing program: governance, methodology, tolerances, incident reporting, attestation |
| 07 | Annual CIRMP Report & Dashboard | Board-attested annual report (to the RBA) with executive risk dashboard |

## Suggested repository structure

```
cirmp-tasman-mutual-bank/
├── README.md
├── 01-scope-brief/
│   └── TMB_CIRMP_01_Scope_Brief.docx
├── 02-risk-register/
│   └── TMB_CIRMP_02_Risk_Register.xlsx
├── 03-cyber-essential-eight/
│   └── TMB_CIRMP_03_Essential_Eight_Assessment.xlsx
├── 04-supply-chain-tprm/
│   └── TMB_CIRMP_04_Supply_Chain_MSP_Register.xlsx
├── 05-personnel-physical/
│   └── TMB_CIRMP_05_Personnel_Physical_Modules.docx
├── 06-cirmp-program/
│   └── TMB_CIRMP_06_Program_Document.docx
└── 07-annual-report/
    └── TMB_CIRMP_07_Annual_Report_Dashboard.docx
```

## Author

**Gaurav Govind** — Governance, Risk & Compliance | Financial Services
Sydney, NSW · [LinkedIn](#) · [GitHub](https://github.com/gaurav221199)
