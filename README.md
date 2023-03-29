# SOFI2D-3D
SOFI2D-3D - Input Builder and Postprocessing Tools

This Project has scripts to design JSON Files for SOFI2D and SOFI3D (you can find them at https://git.scc.kit.edu/GPIAG-Software/)

Each Jupyter Notebook is an interactive version of the JSON Design from the manuals, allowing for an easy step-by-step model design and parametrical review.

For JSON Builders:
At each step, it is possible to review parameters and effects on modeling before generating each JSON File.
After running each a script, the following outputs are expected:
- Models: P-wave velocity, S-wave velocity, Density, P-wave attenuation, S-wave attenuation as binary files
- On-the-fly models: Edited scripts to build each model (much less space!!! but still working on a stable version of this one...)
- Source: File containing sources' locations and parameters
- Receivers: File containing receivers' locations
- JSON File: File containing all parameters

If you are using SOFI2D or SOFI3D for research, please remember to cite the repository and the authors:

Bohlen, T., "Parallel 3-D viscoelastic finite difference seismic
modelling", 2002, Computers & Geosciences 28(8), pages 887-899. DOI:
10.1016/S0098-3004(02)00006-7
