# Offshore Wind Energy Potentials in the North Sea Region

This repository holds the code for the figures and calculations for my Master's thesis *Offshore Wind Energy Potentials in the North Sea Region*.

The main script is oweg.ipynb. Several other scripts need to be run before in order to create shapefiles that are prerequisites for oweg.ipynb.
These data processing scripts themselves make use of unedited shapefiles from external sources. These can be quite large, too large for GitHub.
A link at the top of each script and  indicates where the data can be downloaded. 
The designated folder for these files is the "data" folder.

1. Copy the folder structure onto your local machine.
2. Install the environment.yml using the anaconda command line tool.
3. Download the external shapefiles into the folder *..\data*.
4. Run the auxiliary scripts.
5. Run oweg.ipynb.

Folder paths in the scripts are relative.

Figures in oweg.ipynb are created during runtime and saved to *..\figures*.

All scripts except for oweg.ipynb are uploaded with the output displayed in the notebook. 

Hywind_wind_speed_comparison needs the .xlsx-file Hywind_Wind_Speed_Data from the folder *data* to run.
