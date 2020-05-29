# CorrespondingOrbitals

A python code that biorthogonalizes the unrestricted alpha and beta orbitals and outputs the corresponding orbital basis to produce maximum alignment between the two sets of orbitals.

This program reads in canonical molecular orbital coefficient matrices from a formatted checkpoint file (.fchk) and outputs a new .fchk file with the following name <code>CorrespondingOrbitals-filename.fchk</code>.

The program will also print a summary of the results which includes the orbital number. occupancy, and the alpha-beta overlap.

**Notice**: The current version (v1.1) supports closed and open shell states. However, it only does the analysis over occupied orbitals. Keep an eye on this repository for an updated version!

**Usage**: <code> python corresponding_orbitals_v1.py filename.fchk </code> 
