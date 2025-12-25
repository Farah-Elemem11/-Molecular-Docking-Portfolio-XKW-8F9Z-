Molecular Docking of XKW Ligand with 8F9Z Protein

Objective
Performed molecular docking of XKW ligand with 8F9Z protein using AutoDock Vina (v1.2.7) to evaluate binding affinity and possible binding modes.

Tools & Skills

* AutoDock Vina (command line)
* PyMOL visualization
*  Structure preparation (PyMOL, AutoDock Tools) for PDB/PDBQT files
* Grid box definition
* Docking pose analysis
* Hydrogen bond analysis

Docking Results

* Best binding affinity: −7.732 kcal/mol (mode 1)
* Total binding modes generated: 10
* Exhaustiveness: 16
* Grid box center: (−1.5, −16.7, 11.9)
* Grid size: 23 × 23 × 23 Å
* RMSD of other modes relative to best mode ranged from 0 Å to 4.347 Å
Mode 1 was selected as the best docking pose based on its strongest binding affinity.  
Mode 4, with an affinity of −7.518 kcal/mol and RMSD u.b. of 1.835 Å, is very similar to the best mode, indicating consistent docking results.
All modes demonstrate strong binding (< −6.9 kcal/mol), with the top 5 modes exceeding −7.5 kcal/mol, indicating high confidence in the docking prediction.
 The optimized grid size focused the search space, yielding structurally consistent results.

Visualization
![Docked pose](PyMOL_Images/result-.png)
Docked pose of XKW ligand in 8F9Z protein showing hydrogen bond interactions (2.2–3.3 Å) visualized using PyMOL.

---
