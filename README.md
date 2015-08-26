#Field Size Analysis

##Introduction
Field Sizes are analysed using both the EPID and Gafchromic Film.
Analysis is performed using [ImageJ](http://imagej.nih.gov/ij/) software.

##Method
###EPID
1. An in-house phantom is aligned with the CAX and imaged with a 10x10 photon field.
2. Markers within the phantom are located to allow the CAX to be found.
3. Measurements of the 50% field edge are taken in each direction along the CAX for each individual Jaw.
4. Measured distances are converted to cm and compared to tolerance levels.
5. Results are saved in specific format.

###Gafchromic
1. Gafchromic film is scanned following local protocol
2. In ImageJ user selects CAX markers.
3. The 50% field edges are found relative to the marked CAX.
4. For *some* films Unifomrity measurements are taken relative to the CAX.
5. Measured results are compared to tolerances which are specific to the selected field size & SSD.

##Current Usage
Similar macro files are use for Linac/Gulmay and Papillon Field Analysis.

##Future
- More efficient code.
- A custom macro has been made for use in the **National Papillon dosimetry audit** which is a collaboration between [NPL](http://www.npl.co.uk/) and UK radiotherapy centres.
- Migrate over to using [Fiji](http://fiji.sc/Fiji)

