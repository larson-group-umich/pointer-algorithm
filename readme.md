# Pointer-Algorithm: A mesoscopic simulation method for accurate rheology of surfactant solutions

## About

The files provided here are several versions of the "pointer algorithm" simulation developed to describe the linear oscillatory shear rheology of surfactant solutions containing wormlike micelles as well as instructions for how to use the pointer algorithm code.



## List of files

pointer_algorithm_user_manual.pdf
A summary of and instructions to use the pointer algorithm code.

parameter_calculation.xlsx
An excel spreadsheet that can be used to extract the persistence length from experimental data if desired.  Its use is described in the user manual, and more complete instructions are found in excel_spreadsheet_instructions.pdf.

excel_spreadsheet_instructions.pdf
Instructions for how to use the provided excel spreadsheet to extract the persistence length from experimental data.


## Versions

Pointer algorithm versions (described in more detail in the user manual):
unmerged - describes the rheology of well-entangled micelles

** ** merged v3.1 - the unmerged code with the effects of unentangled micelles (shorter than the entanglement length) added so that solutions at lower concentrations can be fitted using the pointer algorithm

** ** merged v3.3 - a modification of the merged v3.1 code that adds additional Rouse modes based on a comparison with the slip-spring model and improves the high-frequency fits
**This folder also contains the input files for a couple specific example simulations that will generate simulation data found in [1] and [2]. Example 1 is a non-iterative pointer algorithm simulation and Example 2 is an iterative pointer algorithm simulation.

** ** branched - a version of the pointer algorithm code that includes branched micelles typically found at high salt concentrations past the viscosity peak on a salt curve
**This folder contains an input file for an example simulation that generates simulation data from [3].


## User Instruction
	pointer_algorithm_user_manual.pdf
	excel_spreadsheet-Instructions.pdf
**These files contain instructions for user. Please download the files and open with any pdf viewer. GitHub renders the pages in the pdf in wrong order.

## References

	[1] Tan, G.; Larson, R. Quantitative Modeling of Threadlike Micellar Solution Rheology. Rheol. Acta. 2022, 61, 443-457. https://doi.org/10.1007/s00397-022-01341-4.

	[2] Tan, G.; Zou, W.; Weaver, M.; Larson, R. G. Determining Threadlike Micelle Lengths from Rheometry. J. Rheol. 2021, 65 (1), 59ñ71. https://doi.org/10.1122/8.0000152.

	[3] Zou et al. "Mesoscopic Modeling of the Effect of Branching on the Viscoelasticity of Entangled Micellar Solution." (in preparation)

## Acknowledgement

Created by Grace tan and Weizhong Zou
