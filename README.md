# ELEC5551-Rocket-Telemetry-Design-Project-Team-6
The purpose of this final design report is to present a TTS design for the UWAAL sub-orbital launch project. The design primarily aims to track the rocket’s sub-orbital launch to 4 km altitude, monitor its descent, identify the landing location for recovery efforts whilst also collect data throughout the entire mission. This is achieved through the development of two modules: one fitting within the designated section of the CubeSat onboard the rocket (i.e. the payload module) that collects & transmits data, and a base station on the ground responsible for collecting information from the payload module and displaying location of the payload module on a user interface akin to Google Maps functionality. The final design will be composed of a hardware and software solution that will address the inclusions stated in this section.

## Authors
* Shraddha Domdala 
* Sharla Greyvenstein 
* Kate Miller 
* Ankona Pahari
* Anusree Rejukumar
* Thomas Robertson

## Repository Structure
* 3D CAD Design: For Base Station Box and Battery Holder (payload module)
* Code: Includes pseudocode and code-flow diagrams
* Construction and Risks: Documentation on construction procedures and risk assessments associated with the project.
* Libraries: Libraries required for KiCAD to open schematics and PCB Layout
* PCB Layout: PCB Layout for base station and payload module
* Schematics: Schematics for base station and payload module
* Simulations: Simulations to test various aspects of the project

## Required Applications
* KiCAD V6 or Later
* MATLAB 2024a

## Library Installation Guide
Under Libraries
Using the *.kicad_sym file:

* Extract the content of the downloaded *.zip file.
* In KiCad, go to Preferences.
* Click on Manage Symbol Libraries.
* On the Global Libraries tab, click on Browse Libraries (the small folder icon)
* Select the .kicad_sym file, then click Open.
* The library will appear, click OK.
* Click on Symbol Editor.
* Type on the filter search field, and navigate to the symbol you imported.
* Double-click over it to open the file.

Using the *.kicad_mod file:

* Extract the content of the downloaded *.zip file.
* In KiCad, go to Preferences.
* Click on Manage Footprint Libraries.
* On the Global Libraries tab, click on Browse Libraries (the small folder icon)
* Navigate to the Folder where the .kicad_mod file is located. Then click Select Folder. (Note: You will not normally see the .kicad_mod file on this step because
  you need to select the folder where it is located.)
* The library will appear, click OK.
* Click on Footprint Editor.
* Type on the filter search field, and navigate to the footprint you imported.
* Double-click over it to open the file.

## Simulation File Installation Guide 
Files are under simulations > spice simulations
* Extract the content of the downloaded *.zip file.
* Go to the voltage regulator and right click on properties
* Then click on Simulation Model
* Click folder near the file tab
* Go to location of LM1117_N_ADJ_TRANS.LIB or TPS7A0530P_TRANS.lib depending on the file (see name of component to see which is right) - do not change anything else in that tab
* Ensure pin assignments for symbol and model pin match each other in the Simulation Model
* Click Ok in Simulation Model
* Click Ok in Properties Tab

## Acknowledgements
Would like to acknowledge the stakeholders of this project for their assistance

## Licence
This project is licensed under the CERN-OHL-P-2.0 license
