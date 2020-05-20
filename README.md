# CorrespondingOrbitals

A python code that biorthogonalizes the unrestricted alpha and beta orbitals and outputs the corresponding orbital basis to produce maximum alignment between the two sets of orbitals.

This program reads in canonical molecular orbital coefficient matrices from a formatted checkpoint file (.fchk) and outputs a new .fchk file with the following name <code>CorrespondingOrbitals-filename.fchk</code>.

The program will also print a summary of the results which includes the orbital number. occupancy, and the alpha-beta overlap.

**Notice**: The current version (v1.0) only supports singlet states, keep an eye on this repository for an updated version!

**Usage**: <code> python corresponding_orbitals_v1.py filename.fchk </code>

---
**References**
1. F. Neese, "Definition of corresponding orbitals and the diradical character in broken symmetry DFT calculations on spin coupled systems", _J. Phys. Chem. Solids_ **65**, 781 (2004). DOI: [10.1016/j.jpcs.2003.11.015](https://dx.doi.org/10.1016/j.jpcs.2003.11.015)
2. A. T. Amos and G. G. Hall, "Single Determinant Wave Functions", _Proc. R. Soc. London, Ser. A_ **263**, 483-493 (1961). Online at https://www.jstor.org/stable/2414327
3. H. King and R. Stanton, "Corresponding Orbitals and the Nonorthogonality Problem in Molecular Quantum Mechanics" *J. Chem. Phys.* **47**, 1936 (1967); DOI: [10.1063/1.1712221](https://doi.org/10.1063/1.1712221)
