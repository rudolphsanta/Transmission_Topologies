# The cost of regulatory delay: analysis code

This repository contains the analysis code accompanying the article:

> Santarromana R, Abdulla A, Morgan MG, Mendonça J. The cost of regulatory delay: quantifying how permitting timelines affect offshore wind energy costs. *Environmental Research Letters*. 2026.

## Overview

The code computes the levelized cost of energy (LCOE) for an offshore wind plant under three strategies for bringing energy ashore:

- **Topology A:** high-voltage direct current (HVDC) cable transmission (baseline)
- **Topology B:** offshore electrolysis with hydrogen transported to shore by pipeline
- **Topology C:** offshore electrolysis with liquefied hydrogen transported to shore by ship

A deployment lag between project inception and the start of operations is used as a temporal proxy for regulatory and related obligations. Capital expenditures are distributed across the lag years and escalated annually, and the resulting LCOE is compared across lag durations, distances to shore, curtailment levels, and topologies. The code also produces the sensitivity analyses and the exploratory profitability comparison reported in the article.

## Important note on use

This repository is provided to document the analysis reported in the article, for transparency. Before public release, the code was edited to remove local file paths and other machine-specific details. The edited code has not been re-run end to end, so it may contain errors introduced during editing, and it is not intended to run as a standalone package without modification. Users will need to supply their own file paths and, where noted, input data. The results reported in the article were generated with the original, unedited code.

Questions about the analysis may be directed to the corresponding author.


## Citation

If you use this code, please cite the article above. To cite the code itself, please use the Zenodo record: https://doi.org/10.5281/zenodo.10730745


