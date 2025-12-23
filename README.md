This repository contains Lumerical FDTD scripts for designing, simulating, and saving results for apodized amorphous silicon-on-diamond (a-Si-on-diamond) grating couplers.

The apodization methodology implemented here is based on the approach described in:
https://doi.org/10.1038/s41598-017-16505-z

In this implementation, apodization is applied to the first few grating unit cells by gradually modifying the duty cycle and grating period according to the algorithm outlined in the reference. The apodized section is then followed by a uniform grating region to complete the coupler structure.

These scripts are intended to demonstrate the design workflow and simulation methodology for apodized grating couplers rather than provide a foundry-ready design.
