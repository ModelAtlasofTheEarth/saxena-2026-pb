# Model Code & Inputs

## Notes:
To create the .wb files, we need information the longitude-latitude locations to define the fault trace and any information about its dip, if available. The input folder contains these files and the notebooks that are used to generate the .wb-ready input files.

The input files defining the fault geometry are from following sources:
- NUVEL plate boundary model (Argus and Gordon, 1991)
- Peter Bird plate boundary model (Bird, 2003)
- Global Earthquake model (global map of faults based on seismicity, available at https://github.com/GEMScienceTools/gem-global-active-faults)

[nuvel_plates.txt](https://github.com/user-attachments/files/26311968/nuvel_plates.txt)
[bird_gem_faults.json](https://github.com/user-attachments/files/26311967/bird_gem_faults.json)
[PB2002_steps.json](https://github.com/user-attachments/files/26311969/PB2002_steps.json)

[make_world_builder_plate_boundaries.ipynb](https://github.com/user-attachments/files/26311975/make_world_builder_plate_boundaries.ipynb)
[nuvel_world_builder.ipynb](https://github.com/user-attachments/files/26311974/nuvel_world_builder.ipynb)