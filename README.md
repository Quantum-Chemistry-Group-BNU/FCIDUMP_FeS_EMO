
# FCIDUMP file for iron-sulfur clusters in the entanglement-minmized orbitals

The active space is the same as before defined by localized molecular orbitals (LMOs) [see below],
but the one-particle basis functions are now the entanglement-minmized orbitals (EMOs) obtained with a randomized orbital optimization using spin-adapted matrix product states with bond dimension D=100 in Z. Li, Phys. Rev. Lett. 135, 210601 (2025) [https://journals.aps.org/prl/abstract/10.1103/bwvc-z9hz]. The corresponding energies can be found in the Supplemental Meterial of this paper, where the core energies are also provided.

The unitary transformation from LMO to EMO basis is contained in urot.txt (obtained with oo_maxiter=50). For Fe8S7 (oo_maxiter=100) and FeMoco (oo_maxiter=150), the unitaries need to be multiplied together (for example, urot_final = urot*urot_b for Fe8S7).

To compare with the configurations (determinants or configuration state functions) in the paper, one need to take care of the orbital orderings (contained in the file topo), which record the one-dimensional ordering of orbitals for matrix product states.

## Previous FCIDUMP in the LMO basis can be found here:

Fe2S2 and Fe4S4:
https://github.com/zhendongli2008/Active-space-model-for-Iron-Sulfur-Clusters

Fe8S7 (P-cluster):
https://github.com/zhendongli2008/Active-space-model-for-PClusters

FeMoco:
https://github.com/zhendongli2008/Active-space-model-for-FeMoco

