# Cryo-EM structures of prokaryotic ligand-gated ion channel GLIC provide insights into gating in a lipid environment

Cryo-EM structures of the GLIC in each state were embedded within bilayer membranes consisting of DOPE, POPS and POPC with 2:1:1 ratio with the CHARMM-GUI Membrane Builder in 11.6 x 11.6 x 15.8 nm3 simulation cells. 
Similar to previous studies, several acidic residues such as E26, E35, E67, E75, E82, D86, D88, E177 and E243 were protonated and H277 was doubly protonated to mimic the low pH conditions in case of the pH 4 structures.

To best preserve the conformational state of each cryo-EM structure during simulations, harmonic restraints at a force constant of 1000 kJ mol-1 nm-2 were placed on protein backbone atoms and MD simulations ran for 50 ns. 
In case of GLICpH4.0-O, the initial equilibration was extended using previously developed simulation protocol that was found to aid in the relaxation of stable open states in pentameric LGICs. 
The ion channel pore was kept open via flat-bottom harmonic cross distance position restraints between selected Cα atoms of pore-lining residues (Thr at 20', Ile at 16', Ala at 13', Ile at 9', Ser at 6', Thr at 2' and Glu at -2'). The
flat bottom potential only acts when the Cα atoms of non-adjacent pore-lining residues come closer to each other than their distance in the open-state cryo-EM structure with a force proportional to the difference in distance. 
This set-up allows the pore-lining side-chains to relax. This additional restrained simulation step with pore restraints was performed for 200 ns. 
The final frame was used as the starting configuration for three independent repeats, initiated with different velocities.

### PDB codes
- GLIC pH7.5 [8I42](https://www.rcsb.org/structure/8I42) 
- GLICpH4.0-C1 [8I48](https://www.rcsb.org/structure/8I48)
- GLICpH4.0-C2 [8WCQ](https://www.rcsb.org/structure/8WCQ)
- GLICpH4.0-O [8WCR](https://www.rcsb.org/structure/8WCR)
