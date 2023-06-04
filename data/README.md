# Data

Data sources are listed in the referenced file `sources.md`.

Input data for Hywind_Wind_Speed_comparison.ipynb were requested from the research group ORE Catapult Limited. The file Hywind_Wind_Speed_Data.xlsx was aggregated from raw measurement data.

GEBCO input data are available online for the entire world, but for this thesis, a smaller subset for the region of analysis was requested from the website. The file is available here.
Norwegian Naturvernområder (Protected Areas) were likewise selected as a subset, which is also stored here.

During runtime, large files are created, namely data\availability__matrix\A_fow.nc respectively A_fb.nc and scripts\north-sea-region-jan21_2.nc as well as  script\north-sea-region-21-total.nc 
These are too big for GitHub and can be found upon invitation at: https://tubcloud.tu-berlin.de/f/3644480028. Nonetheless, they are created independently in the script, if not saved at the given folder path, where the script can find them. Beware: Each availability matrix takes roughly 1:30 h to compute.

The tubcloud-folder stores all of the raw data and the outputs of the auxiliary scripts in processed form. If available, using these is time-saving.

