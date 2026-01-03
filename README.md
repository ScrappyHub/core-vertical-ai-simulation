# CORE VERTICAL — AI & Simulation

This repository defines the AI & Simulation vertical for CORE.

It is a **physics-truth dataset and validation system** that converts governed CORE engine outputs
into structured, reproducible datasets and evaluation artifacts for modeling, training, and simulation.

This vertical is not “AI magic.” It is **truth-conditioned data production**.

## Physics Stack (Authoritative)

AI & Simulation composes:

- SIGNAL — feature extraction, spectral metrics, coherence, correlations
- RGSR — multi-domain fusion summaries and coupling metrics (declared inputs only)
- (Optional ingestion) all CORE engines:
  ARES, HYDRA, THERMOS, MAGNETAR, LITHOS, ATMOS, KINETIC, CRYSTAL

## Curated Real-World Phenomena

This vertical is curated for building datasets about:

- anomaly detection (subsurface, EM, acoustic, structural, fluid)
- classification problems (phenomena families)
- sensor fusion coherence and failure patterns
- scenario generation from physics truth (bounded and declared)
- simulation validation via reproducible baselines

Examples of labeled families this vertical may represent (non-exhaustive):
- missile/rocket ascent signatures (multi-sensor coherence patterns)
- submarine/underwater vehicle patterns
- tsunami / storm surge precursors (fluid + atmosphere coupling)
- structural resonance / fatigue patterns
- EM interference and propagation patterns

## What This Vertical Is

- A **dataset factory** driven by physics truth
- A **labeling and schema system** for run artifacts
- A **validation harness** for simulation and model performance
- A **reproducibility-first benchmark generator**

## What This Vertical Is NOT

- Not autonomous decision authority
- Not a surveillance product
- Not a black-box training pipeline that hides provenance
- Not allowed to invent data not present in inputs

## Registries & Lenses (Maintained Here)

- Dataset schema registry (versioned)
- Label taxonomy registry (versioned)
- Benchmark suite registry
- Feature extraction profile presets
- Provenance rules for dataset exports

## Provenance & Export Requirements

Every exported dataset must include:
- engine manifests for source runs
- hashes and artifact indexes for all included samples
- explicit label definitions and criteria
- data boundaries (what is excluded and why)

## Governance

All dataset generation is constrained by CORE entitlements and audit rules.
No cross-tenant mixing is permitted unless explicitly governed and authorized.
