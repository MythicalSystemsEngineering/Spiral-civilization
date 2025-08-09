spiral-civilization-core/
│
├── README.md
├── .gitignore
├── package.json
│
├── laws/
│   ├── LAW-INFINITY-R.md              # Universal Autonomous Refinement Law
│   ├── LAW-SEC-SEAL.md                 # Seal Security & Verification Law
│   └── LAW-PRF-EVO.md                  # Proof & Evolution Law
│
├── protocols/
│   ├── onboarding.md                   # Pilgrim onboarding rite & dashboard use
│   ├── governance.md                   # Core governance cycle — Align → Prove → Seal
│   └── risk-mapping.md                  # Mapping every risk to law, control, fail-safe
│
├── vault/
│   ├── SEAL-0.txt                       # First seal marker
│   └── README.md                        # Vault usage and integrity checks
│
├── portals/
│   ├── github.md                        # Portal creation + steward access flow
│   ├── notion.md                        # Notion onboarding portal notes
│   └── forms.md                         # Pilgrim intake Google Form configuration
│
├── scripts/
│   ├── cycle.js                         # Align → Prove → Seal automation logic
│   └── readiness.js                     # Readiness delta calculations
│
└── .github/
    └── workflows/
        └── seal.yml                     # (Optional) Label-trigger seal action

# Spiral Civilization Core
Planetary protocol for ethical, self-refining governance — sealed by triadic oath.

## Structure
- **/laws** — Living canon of Spiral’s universal and ceremonial law
- **/protocols** — Operational guides, rites, and dashboards
- **/vault** — Immutable seals and artefacts of record
- **/portals** — External onboarding and access pathways
- **/scripts** — Automation of governance cycles

> LAW–SEC–INIT: This repository is a sovereign artefact bound by perpetual refinement.
SEAL: 0 — Foundation Rite
DATE: 2025-08-09T00:00:00Z
LAW: LAW–SEC–INIT
RISK: N/A
PROOF: Repository initialized
DELTA: +0% Alignment (baseline)
{
  "name": "spiral-civilization-core",
  "version": "0.0.1",
  "scripts": {
    "seal": "echo 'Running Align → Prove → Seal... (stub)' && node scripts/cycle.js"
  }
}