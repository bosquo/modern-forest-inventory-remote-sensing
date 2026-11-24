# Evaluation and Comparison of Modern Forest Inventory Methods

![B.Eng. Thesis](https://img.shields.io/badge/Thesis-B.Eng._Forestry_Engineering-1B4332)
![Institution](https://img.shields.io/badge/Institution-HSWT_Freising-2D6A4F)
![Domain](https://img.shields.io/badge/Domain-ALS_LiDAR_%7C_DAP_%7C_UAV_%7C_Satellites-48584F)

> **Bachelor's Thesis — Faculty of Forestry (*Fakultät Wald und Forstwirtschaft*)**  
> Hochschule Weihenstephan-Triesdorf (HSWT), Freising · July 2023  
> **Author:** Florian Georg Herbst · **Supervisor:** Prof. Dr. Ewald Endres

---

## Overview

Conventional national and operational forest inventories typically rely on 10-year terrestrial survey cycles—too slow to react to rapid climate-induced disturbances such as drought, windthrow, and bark beetle outbreaks. Conversely, remote sensing promises timely, scalable measurements, but involves trade-offs between **spatial resolution**, **revisit frequency**, **sub-canopy penetration**, and **cost per hectare**.

This Bachelor's thesis systematically evaluates modern remote sensing platforms and 3D/spectral technologies for operational forest inventories and complements the technical literature review with a **qualitative industry market study** of commercial European remote sensing service providers.

---

## Methodology & Scope

1. **Multi-Platform & Sensor Evaluation**
   - Benchmarked **20 Earth observation satellite missions** (Sentinel-1/2, Landsat, MODIS, WorldView, Pléiades, SPOT, PlanetScope, RADARSAT-2, etc.) on spatial resolution, revisit cycle, open-data access, and budget cost (`€/km²`).
   - Compared **Manned Aerial Vehicles (MAVs)** and **Unmanned Aerial Vehicles (UAVs)** (rotary-wing quad/octocopters, hybrid VTOL, fixed-wing) carrying RGB, multispectral, thermal, hyperspectral, and LiDAR payloads.

2. **3D Point Cloud & Spectral Technology Comparison**
   - Evaluated **Airborne Laser Scanning (ALS)**, **Digital Aerial Photogrammetry (DAP / SfM)**, **HSR/VHSR optical satellite imagery**, and **Terrestrial / Mobile Laser Scanning (TLS — RIEGL VZ-600i/VZ-2000i & smartphone LiDAR)** for estimating key stand parameters (`height`, `DBH`, `basal area`, `timber volume`, `above-ground biomass`, `deadwood`, `forest health`, and `tree species classification`).
   - Synthesized literature accuracy (`%RMSE`) comparing ALS, DAP, WorldView-2, TerraSAR-X, and TanDEM-X.

3. **Qualitative Market Study (Expert Interviews)**
   - Contacted 25 companies and conducted **six partially standardized qualitative expert interviews** (primarily CEOs/specialists of European remote sensing inventory providers) using a structured bilingual interview guideline.
   - Analyzed interview records systematically using **Mayring's qualitative content analysis** to uncover real-world pricing (`5–50 €/ha`), workflow bottlenecks, minimum order thresholds (`2,000–3,000 ha`), and client adoption barriers.

---

## Key Results & Operational Proposal

The thesis synthesizes technical accuracy, sub-canopy capabilities, and economic reality into a **four-pillar operational remote sensing inventory framework**:

1. **Foundational 10-Year ALS Survey (Manned Aircraft):** Establishes a high-precision **Digital Terrain Model (DTM)** and captures vertical sub-canopy structure and deadwood volume.
2. **2–5 Year DAP Inventory Updates:** Uses **Digital Aerial Photogrammetry** normalized against the ALS DTM to update stand height, DBH, volume, and orthophoto basemaps at roughly **half the cost of repeated ALS**.
3. **Continuous Satellite & Targeted UAV Health Monitoring:** Screens for disturbances and vitality drops continuously with free **Sentinel-2** (plus SAR under cloud cover), deploying **UAVs** for very-high-resolution multi-/hyperspectral follow-up inspections.
4. **Collective Scaling for Private Forest Owners:** Pooling adjacent private woodlands through **forestry owner associations (*Waldbesitzervereinigungen*)** unlocks economies of scale, bringing LiDAR/RS inventory pricing down from `~50 €/ha` (at 2,000 ha) toward `5–30 €/ha`.

---

## Repository Structure

```text
modern-forest-inventory-remote-sensing/
├── docs/
│   └── Bachelorarthesis.pdf   # Full Bachelor's thesis, market study, and interview guidelines
├── .gitignore
└── README.md
```

- **Full Bachelor's Thesis:** [`docs/Bachelorarthesis.pdf`](docs/Bachelorarthesis.pdf)

---

<p align="center">
  Part of the <a href="https://bosquo.github.io/e-portfolio/"><strong>Florian Herbst — Geoinformatics &amp; Forestry e-Portfolio</strong></a>
</p>
