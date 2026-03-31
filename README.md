# Temporal Event Assertion Framework (TEAF)

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.18715558.svg)](https://doi.org/10.5281/zenodo.18715558)
![License](https://img.shields.io/badge/License-CC%20BY--NC--ND%204.0-lightgrey.svg)

## 🌐 Overview
TEAF is a constraint-based epistemic governance model designed to establish event legitimacy in digital and cyber-physical systems. It positions **Time** as the primary authority, separating raw signals from algorithmic interpretation to ensure data integrity in non-deterministic environments.

---

## 🛠️ Framework Logic Flow (Based on v1.1)
TEAF ensures that every digital event is "anchored" before it is interpreted. This prevents retroactive manipulation and AI-generated hallucinations by separating the **Temporal Assertion** from the **Algorithmic Interpretation**.

```mermaid
graph TD
    %% Layer 1: The Input
    Signal[RAW SIGNAL: Sensor/Log Data] --> Anchor{Temporal Anchor}
    
    %% Layer 2: The Assertion Core
    Anchor -->|PQC Hash + Timestamp| Chain[Distributed Ledger / Secure Log]
    Chain --> Governance{EPISTEMIC GOVERNANCE}
    
    subgraph "TEAF Constraint-Based Validation"
    V1[Linear Continuity Check]
    V2[Structural Integrity / Hash Lock]
    V3[Distributed Verification]
    end
    
    Governance --- V1
    Governance --- V2
    Governance --- V3
    
    %% Layer 3: The Output & Separation
    Governance --> Assertion[LEGITIMATE TEMPORAL ASSERTION]
    Assertion -.-> Interpretation[Algorithmic Interpretation / AI]

    style Signal fill:#e1f5fe,stroke:#01579b
    style Anchor fill:#fff9c4,stroke:#fbc02d
    style Assertion fill:#c8e6c9,stroke:#2e7d32
    style Interpretation fill:#f8bbd0,stroke:#c2185b,stroke-dasharray: 5 5
```

## Official Publication
The full whitepaper (v1.1) is officially archived on Zenodo. You can read and download the complete document here:
👉 **[Read on Zenodo](https://doi.org/10.5281/zenodo.18715558)**
![License](https://img.shields.io/badge/License-CC%20BY--NC--ND%204.0-lightgrey.svg)
## Key Applications
* **Digital Forensics:** Validating event logs in non-deterministic environments.
* **Cyber-Physical Systems:** Ensuring sensor data integrity in IoT and Drones.
* **AI Reliability:** Differentiating between classification failure and event absence.

📄 Official Publication
The full whitepaper (v1.1) is officially archived on Zenodo.

## Citation
If you use this framework, please cite it as:
> Rompis, J. M. E. (2026). *Temporal Event Assertion Framework (TEAF): A Constraint-Based Epistemic Governance Model for Digital and Cyber-Physical System*. Zenodo. https://doi.org/10.5281/zenodo.18715558

---
*Maintained by Jadwin M.E. Rompis - Independent Researcher*
