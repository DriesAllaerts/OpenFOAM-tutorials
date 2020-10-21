# CNBL

A steady RANS simulation of a conventionally-neutral boundary layer (CNBL) in a horizontally periodic domain.

The case is horizontally homogeneous and can therefore be simulated using a single-column model (SCM) strategy. For easy of setting up the simulation, the horizontal grid size is 4x4.
The case setup represents a neutral atmospheric boundary layer developing against a stable background with a lapse rate of 10 K/km. Large-eddy simulations of this setup have been performed by Abkar & Porté-Agel (2013), Pedersen et al. (2014) and Allaerts (2016). Details of the case setup and an intercomparison between the aforementioned studies can be found in Allaerts (2016, Sect. 3.5.2).

The simulation uses [OpenFOAM-6](https://github.com/OpenFOAM/OpenFOAM-6), [SOWFA-6](https://github.com/NREL/SOWFA-6) and a number of in-house libraries and a solver called steadySolverWithoutTurbine (available upon request).

## References
- Abkar, M., Porté-Agel, F., 2013. The Effect of Free-Atmosphere Stratification on Boundary-Layer Flow and Power Output from Very Large Wind Farms. Energies 6, 2338–2361. https://doi.org/10.3390/en6052338
- Allaerts, D., 2016. Large-eddy simulation of wind farms in conventionally neutral and stable atmospheric boundary layers (PhD Thesis). KU Leuven.
- Pedersen, J.G., Gryning, S.-E., Kelly, M., 2014. On the Structure and Adjustment of Inversion-Capped Neutral Atmospheric Boundary-Layer Flows: Large-Eddy Simulation Study. Boundary-Layer Meteorol 153, 43–62. https://doi.org/10.1007/s10546-014-9937-z

