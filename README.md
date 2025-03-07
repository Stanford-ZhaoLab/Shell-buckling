# Shell buckling under combined loads
This repository contains the codebase for the numerical implementation of the Galerkin method (GM) for the buckling and post-buckling analysis of clamped-clamped cylindrical shells under combined torsional and axial loads, as studied in our paper titled “Buckling and post-buckling of cylindrical shells under combined torsional and axial loads”.  Using these codes, one can compute the critical buckling load and the corresponding circumferential wavenumber under combined compression and torsion, the force-displacement curve for post-buckling under pure compression or compression with pre-torsion, and the torque-twisting angle curve for post-buckling under pure torsion or torsion with pre-compression/tension can be calculated. 

To run these codes, Wolfram Mathematica must be installed. The code includes necessary instructions to help users understand and utilize it effectively. For critical buckling calculations, codes for both methods introduced in the main text and in Section S2 of the supplementary file are provided, and the latter method is more computationally efficient. For post-buckling calculations, the solution is highly sensitive to initial values. In the Mathematica file, selected solutions for various geometric and loading parameters are provided, which can be used as initial values for solving similar problems. 

Additionally, Abaqus input files for the finite element analyses (FEA) of Figure 6(a) & (b) and Figure 10(a) with R/h=200 are provided. Before running the input file for post-buckling analysis, first run the input file for critical buckling to generate the buckling mode, which serves as a geometric imperfection in the post-buckling analysis. In the input files, the shell thickness, Young’s modulus, imperfection amplitude, and pre-load value can be adjusted to study different cases.


![image](https://github.com/user-attachments/assets/8170fc3d-e93c-43bf-aa94-35a401d52b51)


# Citation
Lu, L., Leanza, S., Liu, Y., & Zhao, R. R. (2025). Buckling and post-buckling of cylindrical shells under combined torsional and axial loads. arXiv preprint arXiv:2501.12475.
