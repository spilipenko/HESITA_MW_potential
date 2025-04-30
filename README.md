# HESITA_MW_potential
Results of multipole expansion of gravitational potential of Milky Way analogues from HESTIA simulations.

HESTIA is a set of cosmological simulations made under observational constraints to reproduce the Local Group of galaxies in a realistic environment. The project website is [https://hestia.aip.de/](https://hestia.aip.de/).

This repository contains the results of multipole expansion of gravitational potential of Milky Way analogues from this simulation suite computed in the paper [https://arxiv.org/abs/2412.18880](https://arxiv.org/abs/2412.18880). The expansion coeffitients were computed by the [AGAMA](https://github.com/GalacticDynamics-Oxford/Agama) code and can be easily read by it with the agama.potential() method. Coefficients can be used to e.g. compute trajectories of stars, globular clusters, etc. 

These data cover the last 6 Gyr of time and are stored as snapshots with numbers from 91 to 127 (what corresponds to snapshot numbers in the original HESTIA data). A file with snapshot scale factors is provided. There are 14 realizations of Milky Way analogues with lower resolution, called "4k", and 3 realizations with higher resolution, called "8k".

File names:
* NN_MM are Local Group analogue codes
* Rmax or Rvir correspond to two types of data used to build the multipole expansion: Rmax is for all particles up to 3 Mpc from MW center, Rvir is up to the virial radius.
* pot means potential
* Bar / DM / sum are for baryonic matter, dark matter, and all matter
* nnn is snapshot number


When using this data, please, cite the following papers:
Libeskind et al. [https://doi.org/10.1093/mnras/staa2541](https://doi.org/10.1093/mnras/staa2541)
Arakelyan et al. [https://arxiv.org/abs/2412.18880](https://arxiv.org/abs/2412.18880)
