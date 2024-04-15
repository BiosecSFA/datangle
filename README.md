# DATANGLE
**DATA for genTANGLE**
___

## Overview

This repository contains data and results for the [GENTANGLE](https://github.com/BiosecSFA/gentangle) (Gene Tuples ArraNGed in overLapping Elements) pipeline including its computational core [CAMEOX](https://github.com/BiosecSFA/cameox) (CAMEOs eXtended). 

## Data

The data in this repository could be used as an example to run the different entry points on the GENTANGLE Singularity container. Please visit the [GENTANGLE repository](https://github.com/BiosecSFA/gentangle) and [GENTANGLE wiki](https://github.com/BiosecSFA/gentangle/wiki) for further details and updated documentation on how to use the data in the DATANGLE repository.

## Results

This repository contains the complete results for an end-to-end gene entanglement example: _aroB_ and _infA_ genes with _Pseudomonas protegens_ PF5 as bacterial host of the synthetic sequences. These results are stored in the `output/aroB_pf5_uref100_infA_pf5_uref100_p1` directory, and include:
* Three different interactive plots in HTML format:
  * All the variants with series by CAMEOX run.
  * Redundant variants for multiplicity analysis.
  * Sampled variants by sampling method (Pareto, multiplicity, overdensities, and random) and ERP (Entanglement Relative Position).
* Output jupyter notebook as front-end of the analysis.
* Several data files in different tabular formats, such as plain CSV and compressed serialized pandas dataframes. 
Please visit the [GENTANGLE repository](https://github.com/BiosecSFA/gentangle) and [GENTANGLE wiki](https://github.com/BiosecSFA/gentangle/wiki) for further details and updated documentation on the different results files.

## License

DATANGLE is released as part of the [GENTANGLE](https://github.com/BiosecSFA/gentangle) pipeline ([LLNL](https://www.llnl.gov/)-CODE-845475) and is distributed under the terms of the GNU Affero General Public License v3.0 (see LICENSE). 

SPDX-License-Identifier: AGPL-3.0-or-later

LLNL-CODE-845475

## Funding

This work is supported by the U.S. Department of Energy, Office of Science, Office of Biological and Environmental Research, Lawrence Livermore National Laboratory Secure Biosystems Design SFA “From Sequence to Cell to Population: Secure and Robust Biosystems Design for Environmental Microorganisms”.  Work at LLNL is performed under the auspices of the U.S. Department of Energy at Lawrence Livermore National Laboratory under Contract DE-AC52-07NA27344. 

___

If you use GENTANGLE in your research, please cite the following papers. Thanks!

 1. Martí, JM, _et al._ **GENTANGLE: integrated computational design of gene entanglements**. bioRxiv. 2023.11.09.565696. https://doi.org/10.1101/2023.11.09.565696

 2. Blazejewski T, Ho HI, Wang HH. **Synthetic sequence entanglement augments stability and containment of genetic information in cells**. _Science_. 2019 Aug 9;365(6453):595-8. https://doi.org/10.1126/science.aav5477
___

