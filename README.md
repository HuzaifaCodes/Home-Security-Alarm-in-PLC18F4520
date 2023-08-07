How to run simulation
Open PICSimLab: Launch the PICSimLab software on your computer.

Create a New Project: Click on "File" in the menu bar, then select "Load Workspace" and load "SAlarm Workspace.pzw" ,it will Load required settings and Microcontroller

Load HEX File: In the main window, click on "Microcontroller" in the menu bar, then select "Program Memory" from the drop-down menu. 
In the "Program Memory" window, click on the "Load HEX" button and browse to the location of your HEX file. 
Select the SAlarm.hex  to load into the microcontroller.

Load Configuration File : Click on "Module" in the menu bar, and select spare parts a new window will appear, Click on "File" in the menu bar of the new window
select load configuration and load "SAlarmConfig.pcf".After loading it select "SAlarm" to load pin configuration.

Simulation will start

NOTES
The program uses swithes as input from motion and magnetic door sensor and LEDs and Buzzer to mimic output.
