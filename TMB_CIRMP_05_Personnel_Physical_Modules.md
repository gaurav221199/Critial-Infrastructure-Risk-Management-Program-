**TASMAN MUTUAL BANK**

**Critical Infrastructure Risk Management Program (CIRMP)**

Document 5 - Personnel & Physical/Natural Hazard Modules

These two hazard modules complete the four-vector CIRMP assessment, alongside the cyber module (Doc 3) and the supply-chain module (Doc 4). Detailed inherent-residual scoring for each risk below is held in the All-Hazards Risk Register (Doc 2); this document records the control requirements, TMB's current state, and the gap and treatment per risk.

# Module A - Personnel security hazard (CIRMP Rules s9)

## Requirement intent

The CIRMP must establish and maintain processes to minimise or eliminate the material risk that personnel - through malicious, negligent or compromised action, or through their absence - pose to the payment-systems asset. In practice this covers four control areas: screening, trusted-insider access, key-person continuity, and resistance to social engineering.

## Direction of travel (draft amendments)

The draft CIRMP amendments strengthen this vector by requiring personnel security plans and AusCheck-style background checking for personnel in positions of trust. TMB's remediation below is designed toward that standard.

## Assessment

| **Ref** | **Control area**                          | **Current state**                                                                     | **Gap → treatment (target)**                                                                                                                      | **Owner**                   |
| ------- | ----------------------------------------- | ------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------- |
| PER-02  | Pre-employment & ongoing screening        | Pre-employment police / identity checks; role-based access; no periodic re-screening. | Establish a personnel security plan; introduce periodic re-screening for trusted roles; prepare for AusCheck-style background checking. (90 days) | CHRO                        |
| ---     | ---                                       | ---                                                                                   | ---                                                                                                                                               | ---                         |
| PER-01  | Trusted-insider access & monitoring       | Partial data-loss prevention; periodic access reviews; activity logging.              | Uplift DLP coverage; enforce least privilege; deploy user-behaviour analytics (UEBA). (90 days)                                                   | CISO / CHRO                 |
| ---     | ---                                       | ---                                                                                   | ---                                                                                                                                               | ---                         |
| PER-03  | Key-person dependency & continuity        | Some documented runbooks; partial cross-skilling of payments staff.                   | Cross-train; complete operational runbooks; define succession for key payments roles. (180 days)                                                  | Head of Payments Operations |
| ---     | ---                                       | ---                                                                                   | ---                                                                                                                                               | ---                         |
| PER-04  | Awareness & social-engineering resistance | Security awareness training; email filtering; MFA.                                    | Run recurring phishing simulations; deploy phishing-resistant (FIDO2) MFA; tighten help-desk verification. (90 days)                              | CISO                        |
| ---     | ---                                       | ---                                                                                   | ---                                                                                                                                               | ---                         |

**Summary:** the principal personnel exposure is the absence of a structured personnel security plan and periodic re-screening (PER-02), which underpins trusted-insider risk (PER-01). Phishing-resistant MFA (PER-04) also closes a shared gap with the cyber module (CYB-02).

# Module B - Physical & natural hazard (CIRMP Rules s11)

## Requirement intent

The CIRMP must establish and maintain processes to minimise or eliminate the material risk that physical security hazards (unauthorised access, tampering, theft) and natural hazards (fire, flood, storm and similar) pose to the asset and the sites that support it.

## Direction of travel (draft amendments)

The draft CIRMP amendments expect responsible entities operating high-risk asset classes to centrally manage physical security. TMB's remediation introduces a central physical-security register and access-review cadence to that effect.

## Assessment

| **Ref** | **Control area**                             | **Current state**                                                       | **Gap → treatment (target)**                                                                                                      | **Owner**                      |
| ------- | -------------------------------------------- | ----------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------- | ------------------------------ |
| PHY-01  | Site resilience (power / environmental)      | UPS and standby generator; environmental monitoring; DR site available. | Test DR failover to tolerance; validate fuel / power endurance; review primary-site flood rating. (180 days)                      | Head of Infrastructure         |
| ---     | ---                                          | ---                                                                     | ---                                                                                                                               | ---                            |
| PHY-02  | Facility access control                      | Badge access; CCTV; visitor sign-in.                                    | Introduce quarterly physical-access reviews; tighten visitor escorting; maintain a central physical-security register. (180 days) | Head of Facilities             |
| ---     | ---                                          | ---                                                                     | ---                                                                                                                               | ---                            |
| PHY-03  | Natural-hazard exposure (HQ / site)          | Business continuity plan; remote-work capability.                       | Scenario-test extreme-but-plausible events (per CPS 230); confirm a geographically separated recovery site. (180 days)            | Head of Operational Resilience |
| ---     | ---                                          | ---                                                                     | ---                                                                                                                               | ---                            |
| PHY-04  | Concurrent loss of primary & secondary sites | Two operating sites; geographic separation distance unverified.         | Verify geographic separation; define a recovery-time tolerance; conduct a dual-site loss test. (180 days)                         | Head of Operational Resilience |
| ---     | ---                                          | ---                                                                     | ---                                                                                                                               | ---                            |

**Summary:** physical access and single-site power controls are largely effective, so residual ratings are lower here than in the cyber and supply-chain vectors. The material exposure is continuity-related - unverified geographic separation between the primary and recovery sites (PHY-04) - which also intersects the cloud / data-centre concentration risk in the supply-chain module (SUP-01, MSP-08).

# Cross-references

- All four hazard vectors now have a module: cyber (Doc 3), supply chain (Doc 4), and personnel & physical/natural (this document).
- Every risk above is scored inherent-residual in the All-Hazards Risk Register (Doc 2) and rolls up into the program-level remediation roadmap and board-attested annual report (Docs 6 and 7, to follow).