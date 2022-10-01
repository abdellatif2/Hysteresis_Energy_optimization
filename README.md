# Hysteresis Energy optimization

This work is part of Structural Dynamics course, Ecole Nationale Polytechnique, Algiers 2022.
![alt text](https://github.com/abdellatif2/Hysteresis_Energy_optimization/raw/main/images/dm_dds_hannachi_abdellatif_v01.gif "Structure animation")

The goal is to optimize the hysteresis energy dissipation in a steel structure subjected to a seismic event using a genetic algorithm.
![alt text](https://github.com/abdellatif2/Hysteresis_Energy_optimization/raw/main/images/beams.jpg "state 0")

Tools : 
- Python
- PyGAD library
- SAP2000 Python API

Non linear behaviour of the selected beams is modified at each iteration to improve the energy dissipation.
Initial energy dissipation (green) :
![alt text](https://github.com/abdellatif2/Hysteresis_Energy_optimization/raw/main/images/image.png "state 0")

Results after 10 generations :

![alt text](https://github.com/abdellatif2/Hysteresis_Energy_optimization/raw/main/images/Results.png "final iteration")

