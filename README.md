# FEMIC Public Data Mirror

Local DataLad dataset bootstrap for FEMIC Phase 10 (`P10.6`).

Mirrored seed assets currently tracked:

- `data/misc.thlb.tif`
- `data/bc/tsa/FADM_TSA.gdb`
- `data/bc/siteprod/Site_Prod_BC.gdb`
- `data/bc/vri/2019/VEG_COMP_LYR_R1_POLY.gdb`
- `data/bc/vri/2019/VEG_COMP_VDYP7_INPUT_POLY_AND_LAYER_2019.gdb`

This local repo is linked into FEMIC as submodule
`external/femic-public-data`.

Pending maintainer steps:

1. Publish this repository to `UBC-FRESH/femic-public-data`.
2. Configure/push Arbutus RIA special remote.
3. Backfill SHA256 values in FEMIC `metadata/required_datasets.yaml`.
