# New [M@TE](https://mate.science/)! model: 
 _we have provided a summary of your model as a starting point for the README, feel free to edit_
## Section 1: Summary of your model   

**Model Submitter:**  

Arushi Saxena ([0000-0003-2930-3497](https://orcid.org/0000-0003-2930-3497))

**Model Creator(s):**  

- Arushi Saxena ([0000-0003-2930-3497](https://orcid.org/0000-0003-2930-3497))  
- Juliane Dannberg ([0000-0003-0357-7115](https://orcid.org/0000-0003-0357-7115))  
- Rene Gassmöller ([0000-0001-7098-8198](https://orcid.org/0000-0001-7098-8198))  
- Menno Fraters ([0000-0003-0035-7723](https://orcid.org/0000-0003-0035-7723))  
- Timo Heister ([0000-0002-8137-3903](https://orcid.org/0000-0002-8137-3903))  
- Richard Styron ([0000-0002-2374-9431](https://orcid.org/0000-0002-2374-9431))  
  
**Model slug:**  

`saxena-2026-pb` 

(this will be the name of the model repository when created) 

**Model name:**  

_Global plate boundary geometry defined using the GeodynamicWorldBuilder_  

**License:**  

[Creative Commons Attribution 4.0 International]( https://creativecommons.org/licenses/by/4.0/legalcode.txt)

**Model Category:**  

- other   
  
**Model Status:**  

- completed   
  
**Associated Publication title:**  

_[High‐Resolution Mantle Flow Models Reveal Importance of Plate Boundary Geometry and Slab Pull Forces on Generating Tectonic Plate Motions](https://doi.org/10.1029/2022jb025877)_ 

**Short description:**  

Weak plate boundaries are imposed in global convection models primarily to simulate instantaneous flow fields, allowing plates to move freely relative to one another. However, these geometries can be complex including variability across both spatial and depth extents to define faults with varying dip angles. We can incorporate these geometries as initial conditions in our numerical models using GeodynamicWorldBuilder, which creates a 'world' that defines these structures and returns properties (i.e., composition, temperature, density, etc.) for every point in the model mesh.

**Abstract:**  

Global and regional mantle flow models use weak plate boundaries to generate instantaneous plate motions. However, manually including the spatial and vertical complexity of each fault feature can be challenging for geodynamic codes. In this example, we show the capability of a community code, GeodynamicWorldBuilder (GWB), to define plate boundary geometries using an input text file that follows the GWB format (.wb). The defined 'world' is then used with ASPECT to prescribe weak viscosity at the locations of plate boundaries defined in the .wb file, to allow plates to move freely relative to each other. We present four different fault database models: Nuvel (DeMets et al., 1990), Bird closed plate boundaries (Bird, 2003) (Bird-closed), the Global Earthquake Model (Pagani et al., 2018; Styron & Pagani, 2020) (GEM), and a limited subset of GEM (Bird-GEM), and the python notebooks that creates the .wb files for these models.

**Scientific Keywords:**  

- plate boundary   
- GWB   
- input conditions   
  
**Funder(s):**  
- We thank the Computational Infrastructure for Geodynamics (geodynamics.org) which is funded by the National Science Foundation under award EAR-0949446   
  
## Section 2: your model code, output data  

**No embargo on model contents requested** 

**Include model code:**   

True 

**Model code notes:**   

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

**Include model output data:**   

True 

## Section 3: software framework and compute details   
**Software Repository:**   

https://github.com/GeodynamicWorldBuilder/WorldBuilder 

**Name of primary software framework:**  

GeodynamicWorldBuilder 

**Software framework authors:**  
- Menno Fraters ([0000-0003-0035-7723](https://orcid.org/0000-0003-0035-7723))  
  
**Software & algorithm keywords:**  

- C++   
  
## Section 4: web material (for mate.science)   
**Landing page image:**  

Filename: [None]()  
Caption: Plate boundary models used in Saxena et al., (2023) and generated using the GWB.  
  
**Animation:**  

Filename: [graphics/Image.gif](https://github.com/user-attachments/assets/2e508009-f9c1-4cfe-89fc-5377fa349a09)  
Caption:   
  
**Graphic abstract:**  

Filename: [None]()  
  
**Model setup figure:**  

Filename: [None]()  
  
