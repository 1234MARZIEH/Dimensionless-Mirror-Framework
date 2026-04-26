# Rapid Regime & Stability Identification in Bioreactors and Gas–Liquid Absorption Systems

**Author:** Marziyeh Qasemi  
**Framework:** Dimensionless Mirror Framework (DMF)

---

## 🌐 Overview

The **Dimensionless Mirror Framework (DMF)** is a compact and universal methodology for rapid regime identification and stability assessment in:

- Bioreactors (aerobic/anaerobic, stirred tank, airlift, etc.)
- Gas–liquid absorption and separation systems (packed columns, tray columns, scrubbers, reactive absorbers)

Instead of solving full PDE-based transport–reaction models, this framework reorganizes classical dimensionless analysis into structured **Mirror Tables** that directly map:

- Operating regimes  
- Transport vs. reaction dominance  
- Stability and limitation indicators  
- Recommended engineering actions  

This repository is designed for researchers, engineers, graduate students, and process developers seeking rapid diagnostic tools.

---

## ✨ Key Features

- Unified methodology for bioreactors and absorption systems  
- Dimensionless-based fast screening  
- No need for solving differential equations  
- Real-time applicability  
- Extendable to other multiphase and reactive systems  

---

## 📊 Core Dimensionless Groups

The framework is built around the following dimensionless and operational groups:

- **Damköhler number (Da)** – reaction vs. transport dominance  
- **Sherwood number (Sh)** – convective mass transfer intensity  
- **Hatta number (Ha)** – reactive absorption regime indicator  
- **Reynolds number (Re)** – hydrodynamic regime  
- **Schmidt number (Sc)** – momentum vs. mass diffusivity  
- **Volumetric mass transfer coefficient (kLa)**  
- **OTR/OUR ratio** – oxygen transfer stability criterion  

---

## 🧠 Scientific Structure

The Mirror Framework is organized into five primary analytical tables:

1. **Bioreactor Stability Table**  
   (Da, kLa, OTR/OUR relationships)

2. **Operational Instability Indicators**  
   (pH shifts, DO fluctuations, temperature rise, foaming)

3. **Absorption Regime Classification**  
   (Re, Sc, Sh, Ha mapping)

4. **Rapid Limitation Diagnosis Table**  
   (Gas-side vs liquid-side vs reaction control)

5. **Unified Cross-Domain Mirror Table**  
   (Common logic between biological and physicochemical systems)

These tables enable rapid identification of:

- Kinetic vs. mass-transfer limitations  
- Oxygen limitation or overload  
- Hydrodynamic failure regions  
- Reaction-dominated unstable zones  

without numerical simulation.

---

## 📁 Repository Structure

```text
docs/          → Full scientific documentation  
examples/      → Worked example problems  
figures/       → Regime maps and conceptual diagrams  
README.md      → Project overview  
LICENSE        → Usage and distribution license  
CITATION.cff   → Citation metadata  
```

---

## 📘 Documentation

Detailed scientific documentation is available in the `/docs` folder:

- Abstract  
- Introduction  
- Methodological Framework  
- Mirror Tables  
- Discussion  
- Conclusions  

Each section follows a conference/ISI-style scientific structure.

---

## 📚 Example Problems

Located in `/examples`:

- Bioreactor oxygen stability (OTR vs OUR)  
- Reactive gas–liquid absorption (Sh, Ha analysis)  
- Stability classification using Damköhler number  

Each example is solved using:

1. Conventional full analysis  
2. Dimensionless mirror shortcut  

---

## 🧩 Citation

If you use this framework in academic work, please cite as follows:

```yaml
cff-version: 1.2.0
title: "Dimensionless Mirror Framework"
authors:
  - family-names: Qasemi
    given-names: Marziyeh
doi: ""
date-released: 2026-04-26
license: MIT
version: "1.0"
```

---

## 📄 License

Recommended: **MIT License** (Open and research-friendly)

---

## 🤝 Contributions

Pull requests, technical discussions, and framework extensions are welcome.

Researchers are encouraged to adapt the Mirror Tables to specific reactor geometries, biological systems, or hydrodynamic regimes.

---

## ⭐ Support

If this framework contributes to your research or engineering work, consider starring the repository.

---

## 🙌 Acknowledgment

Developed by **Marziyeh Qasemi**  
Chemical Engineering (Biotechnology & Pharmaceutical Engineering)  
Interest areas: aerospace engineering, transport phenomena, and applied mass transfer.
