# Inter-Satellite_Optical_Link_Analyzer_ISOLA

Supervised by Professor C. Patrick Yue, we developed this Inter-Satellite Optical Link Analyzer (ISOLA) for practical satellite communications.

## 1. Motivation
The ISOLA is based on the detailed modeling of link budget analysis as shown below.

<img src="Pictures/LinkBudget.png" width="600">

## 2. Environment Requirement
* MATLAB 2019b or newer version

## 3. Tutorial for the ISOLA
The following steps show an example of how to use the ISOLA platform step-by-step. 

Step 1. Download the all files in . Put 'RF_OFDM', 'Matlab_ADS_Data' and 'Cosimulation_TRx_wrk' folders into the same loacation.

Step 2. Open Matlab 2019a (or later). Go to ‘RF_OFDM’ folder, Select and run ‘App_Ver2.mlapp’. 
<img src="Pictures/Run_GUI.png" width="500">

Step 3. Setup the GUI accroding to your requirements, such as number of subcarriers, modulation order, etc. And then click the 'Signal Modulation' icon. After the signal modulation is finished, the normalized power spectrum density (PSD), constellation and time domain waveform (real part) of the BB M-QAM OFDM signal are all displayed on the GUI (left part on the GUI). The following figure (left part) shows an exampple.
<img src="Pictures/Co-simulation_Platform_GUI.png" width="%80">

Step 4. Use ADS2019 or latter to open the workspace named 'Cosimulation_TRx_wrk'. And select and open ‘System_TEST’ schematic. The ADS simulation schematic is as follow. 
<img src="Pictures/ADS_Schematic.png" width="%80">

After completing the simulation in schematic, the results will appear as shown below.
<img src="Pictures/ADS_Simulation_Results.png" width="%80">

Step 5. Go back to the GUI and click "Signal Modulation" button. Wait for a second, the spectrum, constellation and waveform of the transmitted signal are shown in the window, as shown in the figure (right part) in Step 3. 
 
Step 6. Now you can replace your own design to the example project for the Co-Simulation!

For more information, please contact us at: eewmshi@ust.hk
