# Vacancy-Ordered Double Perovskite Semiconductors

Repository for paper: Defect Tolerance to Intolerance in the Vacancy-Ordered Double Perovskite Semiconductors Cs<sub>2</sub>SnI<sub>6</sub> and Cs<sub>2</sub>TeI<sub>6</sub>

DOI:[10.1021/jacs.6b03207](http://pubs.acs.org/doi/abs/10.1021/jacs.6b03207)

Optimised crystal structures of Cs<sub>2</sub>SnI<sub>6</sub> and Cs<sub>2</sub>TeI<sub>6</sub> from density functional theory, calculated using the Vienna *Ab initio* Package (VASP).

Computational Details
-----------------------
The crystal structures of Cs<sub>2</sub>SnI<sub>6</sub> and Cs<sub>2</sub>TeI<sub>6</sub> obtained by Stoumpos et al.<sup>1</sup> and Manojlovic<sup>2</sup> were used as the starting point for the calculations.

We have optimised the structures using the HSE06 functional.
The final structures have been obtained following an iterative procedure where the ion positions, cell shape, and cell volume are allowed to change (`ISIF = 3` in VASP) using a Quasi-Newton algorithm.

Requirements
------
To open the .cif file, a viewer such as [VESTA](http://jp-minerals.org/vesta/en/).
To run the `POSCAR` file: a VASP license, and suitable input `INCAR`, `KPOINTS`, and `POTCAR` files.

Disclaimer
------
This file is not affiliated with VASP. Feel free to use and modify, but do so at your own risk.

References
-------
1. C. C. Stoumpos, C. D. Malliakas, and M. G. Kanatzidis, Semiconducting Tin and Lead Iodide Perovskites with Organic Cations: Phase Transitions, High Mobilities, and Near-Infrared Photoluminescent Properties, *Inorg. Chem.*, **52**, 9019–9038 (2013) doi: [10.1021/ic401215x](http://pubs.acs.org/doi/abs/10.1021/ic401215x) 
2. L. M. Manojlovic, The crystal structure of cesium hexaiodotellurite, *Bull. Inst. Nuclear Sci.*, **6**, (1956)
