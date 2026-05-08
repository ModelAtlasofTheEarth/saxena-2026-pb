### -> submitter ORCID (or name)

0000-0003-2930-3497

### -> slug

saxena-2026-pb

### -> license

CC-BY-4.0

### -> alternative license URL

_No response_

### -> model category

other

### -> model status

completed

### -> associated publication DOI

https://doi.org/10.1029/2022JB025877

### -> model creators

_No response_

### -> title

Global plate boundary geometry defined using the GeodynamicWorldBuilder

### -> description

Weak plate boundaries are imposed in global convection models primarily to simulate instantaneous flow fields, allowing plates to move freely relative to one another. However, these geometries can be complex including variability across both spatial and depth extents to define faults with varying dip angles. We can incorporate these geometries as initial conditions in our numerical models using GeodynamicWorldBuilder, which creates a 'world' that defines these structures and returns properties (i.e., composition, temperature, density, etc.) for every point in the model mesh.

### -> abstract

Global and regional mantle flow models use weak plate boundaries to generate instantaneous plate motions. However, manually including the spatial and vertical complexity of each fault feature can be challenging for geodynamic codes. In this example, we show the capability of a community code, GeodynamicWorldBuilder (GWB), to define plate boundary geometries using an input text file that follows the GWB format (.wb). The defined 'world' is then used with ASPECT to prescribe weak viscosity at the locations of plate boundaries defined in the .wb file, to allow plates to move freely relative to each other. We present four different fault database models: Nuvel (DeMets et al., 1990), Bird closed plate boundaries (Bird, 2003) (Bird-closed), the Global Earthquake Model (Pagani et al., 2018; Styron & Pagani, 2020) (GEM), and a limited subset of GEM (Bird-GEM), and the python notebooks that creates the .wb files for these models.

### -> scientific keywords

plate boundary, GWB, input conditions

### -> funder

We thank the Computational Infrastructure for Geodynamics (geodynamics.org) which is funded by the National Science Foundation under award EAR-0949446, EAR-1550901, and EAR-2149126 for supporting the development of GWB and ASPECT.

### -> model embargo?

_No response_

### -> include model code ?

- [x] yes

### -> model code/inputs DOI

_No response_

### -> model code/inputs notes

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

### -> include model output data?

- [x] yes

### -> data creators

_No response_

### -> model output data DOI

_No response_

### -> model output data notes

_No response_

### -> model output data size

_No response_

### -> software framework DOI/URI

_No response_

### -> software framework source repository

https://github.com/GeodynamicWorldBuilder/WorldBuilder

### -> name of primary software framework (e.g. Underworld, ASPECT, Badlands, OpenFOAM)

GeodynamicWorldBuilder

### -> software framework authors

0000-0003-0035-7723

### -> software & algorithm keywords

C++

### -> computer URI/DOI

_No response_

### -> add landing page image and caption

<img width="3395" height="2107" alt="Image" src="https://github.com/user-attachments/assets/591d9da4-a672-47e3-a9e0-ac5b5ace887c" />
Plate boundary models used in Saxena et al., (2023) and generated using the GWB. 

### -> add an animation (if relevant)

![Image](https://github.com/user-attachments/assets/2e508009-f9c1-4cfe-89fc-5377fa349a09)

### -> add a graphic abstract figure (if relevant)

_No response_

### -> add a model setup figure (if relevant)

_No response_

### -> add a description of your model setup

_No response_

### Please provide any feedback on the model submission process?

I am unable to attach the model output files (.wb text files and .vtu files) since they are not supported. Are there any alternatives you recommend? This model is just to test the workflow for uploading a world builder model setup.