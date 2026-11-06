# LCK recruitment inhibitors docking data

Input files and complete outputs of the molecular docking calculations
reported in "Controlling TCR and CAR activation by targeting LCK
recruitment with novel small-molecule inhibitors".

## Contents

### `HTVS_results/`
High-throughput virtual screening. Contains the receptor inputs and the full set of
output poses and scores. The ENAMINE compound library used as the
screening source is not redistributed here; it is available from the
vendor.

### `AutoDockCrankPep_results/`
Peptide docking of the loop motif with AutoDockCrankPep. The input is
the loop sequence rather than a three-dimensional model, since ADCP
builds the peptide conformations internally, so no starting structure
for the RK motif is included. The receptor inputs and
all resulting poses and scores are provided.
