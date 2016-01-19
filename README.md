#Field Size Analysis

##Introduction
Field Sizes are analysed using both the EPID and Gafchromic Film.
Analysis is performed using [ImageJ](http://imagej.nih.gov/ij/) software.

##Running Macros
###Macro Launcher
There is a macro launcher (simple batch file) which when run will open ImageJ and start the ImageJ Menu Macro contained within the same folder.

####Macro Menu
There is a menu (created as an ImageJ macro) which has been created to allow consistent running of the macros and simple updating.
The user runs this menu macro and this allows them to select the required test.
This would need updating if the macro file names updated, or a new macro was added.
Note: This replaces the previous menu created in MS Access with the hope of simpler upkeep.
Macros for Linacs (Guildford and Redhill), Gulmay, Papillon and some additional test macros are available.

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

