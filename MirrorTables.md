# Mirror Tables
Unified Dimensionless Framework for Rapid Regime and Stability Identification

This document presents five mirror tables designed for rapid identification of transport–reaction regimes, system limitations, and operational stability in bioreactors and gas–liquid absorption systems.

---

## Table 1 — Rapid Stability Assessment in Bioreactors

| Criterion | Dimensionless Condition | Interpretation | Engineering Implication |
|----------|-------------------------|----------------|-------------------------|
| Kinetic regime | Da << 0.1 | Reaction slower than transport | System typically stable |
| Transitional regime | 0.1 ≤ Da ≤ 1 | Comparable time scales | Sensitive to disturbances |
| Transport-limited | Da >> 1 | Reaction faster than mixing | Risk of gradients & instability |
| Weak gas–liquid transfer | kLa < 50 h⁻¹ | Limited oxygen supply | Possible oxygen limitation |
| Oxygen sufficient | OTR ≥ OUR | Transfer exceeds demand | Stable oxygen conditions |
| Oxygen-limited | OTR < OUR | Uptake exceeds supply | Risk of productivity loss |

---

## Table 2 — Operational Indicators of Instability in Bioreactors

| Observable Signal | Likely Physical Cause | Mirror Interpretation | Recommended Action |
|-------------------|----------------------|----------------------|-------------------|
| Sharp pH drop | Substrate overload / acid formation | Reaction dominating buffering | Reduce feed rate |
| DO fluctuations | Poor mixing | Local mass transfer limitation | Increase agitation |
| Excessive foaming | High gas evolution | Approaching hydrodynamic limits | Antifoam / adjust gas flow |
| Gradual temperature rise | Exothermic metabolism | Heat removal < heat generation | Improve cooling |

---

## Table 3 — Regime Classification in Gas–Liquid Absorption Systems

| Dimensionless Range | Physical Regime | Dominant Mechanism | Design Insight |
|---------------------|----------------|--------------------|----------------|
| Re << 100 | Laminar flow | Diffusion dominated | Increase velocity |
| Re ≥ 1000 | Turbulent flow | Convection enhanced | Higher transfer, higher energy |
| Sc >> 1 | Momentum diffuses faster than mass | Thin mass boundary layer | Liquid-side resistance important |
| High Sh | Strong convective transfer | Reduced film resistance | Efficient external transfer |
| Ha < 0.3 | Kinetic control | Reaction slower than diffusion | Increase reactivity |
| 0.3 ≤ Ha ≤ 3 | Mixed regime | Coupled reaction–diffusion | Sensitive design zone |
| Ha > 3 | Diffusion-limited | Film-controlled absorption | Increase turbulence |

---

## Table 4 — Rapid Limitation Diagnosis in Absorption Systems

| Observed Behavior | Dominant Resistance | Mirror Diagnosis | Engineering Action |
|------------------|--------------------|------------------|--------------------|
| Large gas–liquid ΔC, low removal | Gas-side | Gas film limitation | Increase gas velocity |
| Small ΔC, low overall rate | Liquid-side | Liquid diffusion resistance | Improve packing |
| Sh_exp << Sh_theor | Hydrodynamic maldistribution | Fouling or poor wetting | Clean / redesign internals |
| Temperature rise | Strong exothermic reaction | Thermal instability risk | Staged absorption / cooling |

---

## Table 5 — Unified Mirror View of Reaction–Transport Systems

| Aspect | Governing Numbers | Mirror Criterion | Physical Meaning | Stability Insight |
|--------|------------------|-----------------|-----------------|------------------|
| Reaction vs transport | Da, Ha | << 1 | Kinetic control | Typically stable |
|  |  | >> 1 | Transport-limited | Gradient formation |
| Hydrodynamics | Re, Sc | Low Re | Diffusion-dominated | Low mixing |
|  |  | High Re | Convective regime | Enhanced transfer |
| External mass transfer | Sh | High Sh | Strong convection | Low film resistance |
| Operational stability | OTR/OUR, heat balance | Transfer ≥ demand | Stable operation |
|  |  | Transfer < demand | Instability risk |