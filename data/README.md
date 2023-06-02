# Data

Data sources are listed in the referenced file `sources.md`.

Input data for Hywind_Wind_Speed_comparison.ipynb were requested from the research group ORE Catapult Limited. The file Hywind_Wind_Speed_Data.xlsx was aggregated from raw measurement data.

During runtime, large files are created, namely data\availability__matrix\A_fow.nc respectively A_fb.nc and scripts\north-sea-region-jan21_2.nc as well as  script\north-sea-region-21-total.nc 
These are too big for GitHub and can be found upon invitation under: https://tubcloud.tu-berlin.de/f/3644480028. Still, they are created independently in the script: Each availability matrix takes roughly 1:30 h to compute.
