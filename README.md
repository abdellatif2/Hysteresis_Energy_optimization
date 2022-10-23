# Hysteresis Energy optimization

This work is part of Structural Dynamics course, Ecole Nationale Polytechnique, Algiers 2022.

![alt text](https://github.com/abdellatif2/Hysteresis_Energy_optimization/raw/main/images/dm_dds_hannachi_abdellatif_v01.gif "Structure animation")

The goal is to optimize the hysteresis energy dissipation in a steel structure subjected to a seismic event using a genetic algorithm.
<p align="center">
<img src="https://github.com/abdellatif2/Hysteresis_Energy_optimization/raw/main/images/beams.jpg" width="300" />
</p>

Tools : 

- Python
- PyGAD library
- SAP2000 Python API

Non linear behaviour of the selected beams is modified at each iteration to improve the energy dissipation.

Initial energy dissipation (green) :

<img src="https://github.com/abdellatif2/Hysteresis_Energy_optimization/raw/main/images/image.png" width="400" />

Results after 10 generations :

<img src="https://github.com/abdellatif2/Hysteresis_Energy_optimization/raw/main/images/Results.png" width="400" />


