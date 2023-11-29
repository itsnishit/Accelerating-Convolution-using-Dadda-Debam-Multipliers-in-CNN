# Accelerating-Convolution-using-Dadda-Debam-Multipliers-in-CNN

### Brief Analysis Report:
WHile using exact Dadda multipliers (4 different adders are used for addition of partial products), 
Carry Select Adder based multiplier gives highest power consumption in both the flows(4.3mW) but is best in terms of delay (slack of +1.65 ps)
Carry look ahead adder gives highest area required (42,869 um2) 
The approximate multiplier used is the DeBAM multiplier which is a decoder based multiplier using the different number of approximate decoder logic blocks

The repository is organised as follows:
1) source codes for all the layers
2) source code for the exact multipliers and approximate multiplier (DeBam)
3) source code(binary format) for the inputs
4) spreadsheet with all the metrics (FPGA and ASIC flow)
5) RTL simulations for custom inputs


