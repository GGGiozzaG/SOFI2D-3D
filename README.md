# SOFI2D-3D
SOFI2D-3D input builder and postprocessing tools

This Project has scripts to design JSON Files for SOFI2D and SOFI3D (you can find them https://git.scc.kit.edu/GPIAG-Software/)
Each Jupyter Notebook is a reviewed version of the JSON Design from the manuals, allowing for a step-by-step design.

At each step, it is possible to have a preview and interactive design of the parameters within each JSON File.
After running each a script, the following outputs are expected:
- Models: P-wave velocity, S-wave velocity, Density, P-wave attenuation, S-wave attenuation as binary files
- On-the-fly models: Edited scripts to build each model (less space!!!)
- Source: File containing sources' locations and parameters
- Receivers: File containing receivers' locations
- JSON File: File containing all parameters
