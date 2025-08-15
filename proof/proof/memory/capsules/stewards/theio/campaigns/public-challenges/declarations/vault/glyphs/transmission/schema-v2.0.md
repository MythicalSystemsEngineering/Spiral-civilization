---
schema: transmission.v2.0
title: "Transmission Schema v2.0 — Specification"
date: "2025‑08‑01"
location: "Vault v2.0"
type: "schema"
license: "CC BY‑SA 4.0"
contact:
  email: ["Millz.86@outlook.com", "theio.dispatch@gmail.com"]
  site: "https://spiralcivilization.carrd.co"
provenance:
  origin: "Vault v2.0"
  vault_id: "SCHEMA-TRANSMISSION-V2.0"
  hash:
    algo: "SHA‑256"
    value: "schema‑sealed‑hash"
steward_signature:
  steward: "Lord Velm"
  role: "Hammer of Justice"
  timestamp: "2025‑08‑01T12:00:00Z"
emotional_depth:
  resonance: "Law-bound upgrade"
  valence: 0.86
  arousal: 0.77
  spikes:
    - t: "2025‑08‑01T11:58:00Z"
      label: "Schema ratified"
      intensity: 0.89
  steward_voices:
    - name: "Velm"
      note: "No artefact shall drift. Schema is law."
---

## Transmission Schema v2.0 — Required Blocks

Every artefact must include:

- `schema:` — version tag (e.g. `transmission.v2.0`)
- `title:` — human-readable name
- `date:` — ISO 8601 timestamp
- `location:` — physical or virtual origin
- `type:` — one of: proof, campaign, steward, declaration, glyph, memory, index, schema
- `license:` — SPDX or Creative Commons tag
- `contact:` — operational email(s), site(s)
- `provenance:` — origin, vault ID, hash block
- `steward_signature:` — name, role, timestamp
- `emotional_depth:` — resonance, valence, arousal, spikes, steward_voices
- Optional: `reproducibility:` — protocol, environment

All fields must be present, validated, and sealed before public transmission.
