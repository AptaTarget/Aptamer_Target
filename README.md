![Github-Figure 1_0528_画板 1](https://github.com/AptaTarget/Aptamer_Target/assets/174264362/c37e2773-5300-4568-8af0-d7da962694cb)# Aptamer_Target
A high-throughput, three-stage computational framework to identify additional potent targets for aptamers

The computational screening of promiscuous binders for an aptamer consisted of three stages:

Stage 1: Ensemble docking.
Ensemble docking was employed using multiple aptamer structural models, treating each aptamer model as rigid while keeping the ligands flexible. This approach enables high-speed computation using empirical scoring function. The docked pose of L-Arm within LABA closely resembled that in the NMR structure with a root-mean-square deviation (RMSD) of 0.70 Å and a docking score of −7.46. Similarly, OTA in OBA3 achieved a docking score of −7.11.

Stage 2: Post-docking induced-fit refinement.
Post-docking induced-fit refinement was performed on residues within 6 Å of the docked target. This stage locally relaxes the predicted target-binding pose to partially mimic the induced-fit binding process, followed by Prime MM-GBSA calculations to rapidly estimate the binding energy and ligand strain energy. This method offers moderate speed with energy-based affinity predictions. The positive controls (L-Arm in LABA and OTA in OBA3) showed favorable binding energies (MMGBSA dG Bind) of −56.9 kcal/mol (Fig. 2d) and −24.5 kcal/mol, respectively.

Stage 3: Molecular dynamics (MD) simulations-based binding estimation.
All-atom MD simulations were conducted to simulate the dynamic recognition processes between aptamer and target, despite being time-consuming. This was followed by binding free energy calculations using the molecular mechanics-generalized Born surface area (MM/GBSA) and normal-mode analysis (NMA) approaches. Throughout the MD simulations, L-Arm remained consistently encapsulated within the binding site of LABA, as reflected by an excellent calculated binding free energy (∆Gtheor−GB=∆GMM/GBSA−T∆SNMA) of −24.62 kcal/mol, establishing a reliable positive control. Similarly, the predicted binding free energy of OTA to OBA3 (∆Gtheor−GB) is −6.74 kcal/mol.


![Github-Figure 1_0528_画板 1](https://github.com/AptaTarget/Aptamer_Target/assets/174264362/4cd7ce3b-3c60-43ff-9d62-6145fee4c5cb)
