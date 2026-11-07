# Particle-size-induced shifts of pseudoboehmite XRD reflections

Supplementary data for the article:
**"Quantifying the particle-size-induced shifts of pseudoboehmite XRD reflections: implications for lattice constants refinement accuracy"**
[Ivan Yu. Petrov, Svetlana V. Cherepanova, Vera P. Pakharukova]

## Contents

| Path | Description |
|---|---|
| `Cuboidal distribution sizes.xlsx` | Sizes of cuboidal pseudoboehmite particles |
| `PeakShifts.xlsx` | Measured shifts of pseudoboehmite Bragg peaks |
| `DSE-patterns/` | Modeled Debye Scattering Equation (DSE) patterns |
| `XYZ/` | Atomic models (`.xyz`) used for DSE calculations |
| `Simulated DSE patterns for Rietveld Refinement/` | Simulated XRD patterns used for Rietveld refinement |

## File naming

**Plate-like particles** (`DSE-patterns/*.dat`, `XYZ/*.xyz`):
- `HN` – hexagonal plate
- `RN` – rhomboid plate
- `NN` – needle-like plate

where `N` is the thickness in unit cells along [010].

**Cuboidal particles:**
- `cuboidal distribution_1/` – crystals truncated at unit-cell boundaries
- `cuboidal distribution_2/` – same, with the origin shifted by 1/4 *b*

Files are named `n_m`, i.e. a thickness of n.m unit cells along *b* (e.g. `1_5.dat` = 1.5 unit cells).

## Data format
`.dat` – [ 2θ (°) , intensity]
