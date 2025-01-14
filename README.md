# Inter-Satellite_Optical_Link_Analyzer_ISOLA

Supervised by Professor C. Patrick Yue, we developed this Inter-Satellite Optical Link Analyzer (ISOLA) for practical satellite communications.

## 1. Motivation
The ISOLA is based on the detailed modeling of link budget analysis as shown below.

<img src="Pictures/LinkBudget.png" width="%50">

## 2. Environment Requirement
* MATLAB 2019b or newer version

## 3. Tutorial for the ISOLA
The following steps show an example of how to use the ISOLA platform step-by-step. 

Step 1. Download all files in "MATLAB Files", and unzip them into the same folder.

Step 2. Open Matlab 2019a (or later). Go to ‘MATLAB Files’ folder, Select and run ‘InterSatellite_Optical_Link_Analyzer_ISOLA_GitHub.mlapp’. 
<img src="Pictures/ISOLA1.png" width="%80">

Step 3. Setup the link parameters in GUI according to your requirements, such as required received power, link distance, etc. And then click the 'BER Curve Fitting' icon. After the curve appears, the corresponding required optical power at the receiver is displayed on the GUI (left part on the GUI). The following figure (left part) shows an exampple.
<img src="Pictures/ISOLA2.png" width="%80">

Step 4. Use ADS2019 or latter to open the workspace named 'Cosimulation_TRx_wrk'. And select and open ‘System_TEST’ schematic. The ADS simulation schematic is as follow. 
<img src="Pictures/ADS_Schematic.png" width="%80">

After completing the simulation in schematic, the results will appear as shown below.
<img src="Pictures/ADS_Simulation_Results.png" width="%80">

Step 5. Go back to the GUI and click "Signal Modulation" button. Wait for a second, the spectrum, constellation and waveform of the transmitted signal are shown in the window, as shown in the figure (right part) in Step 3. 
 
Step 6. Now you can replace your own design to the example project for the Co-Simulation!

For more information, please contact us at: eewmshi@ust.hk
