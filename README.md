Molecular Docking of XKW Ligand with 8F9Z Protein

Objective

Conducted molecular docking to dock the ligand XKW with the target protein 8F9Z using AutoDock Vina (version 1.2.7).
Tools & Skills
- AutoDock Vina (Command Line)
- PyMOL visualization
- Structure preparation (PyMOL, AutoDock Tools) for PDB/PDBQT
- Definition of a Grid Box
- Docking pose analysis
- Hydrogen bonding analysis

Docking Results
- Best binding affinity: -7.732 kcal/mol in mode 1
- Total binding modes: 10
- Exhaustiveness: 16
- Center of the grid: (−1.5, −16.7, 11.9)
- Grid size: 23 x 23 x 23 Å
- RMSD range:  0–4.347 Å (upper bound)

Visualization
Docked pose of XKW ligand inside 8F9Z protein illustrating hydrogen bonding (2.2-3.7 Å) interactions seen through PyMOL
Grid Optimization Strategy

Grid optimization
- Theoretical grid (PyMOL):  30 × 27 × 35 Å (82×73×94 points)
- Optimized grid (used): 23 × 23 × 23 Å (61×61×61 points)
- Percentage of volume reduction: 57
- Rationale: Maintained accuracy while improving computational efficiency
- Outcome: Excellent binding affinity: -7.732 kcal/mol validated the grid suitability Key Findings
   1. The best pose was chosen based on the highest binding affinity, and Mode 1 was identified.
   2. Mode 4 presents a similar structure (RMSD: 1.835 Å) with relatively good affinity (−7.518
   3. All the modes have a strong binding energy with a value less than −6.9 kcal/mol; in fact, the top 5  modes exceeding −7.5 kcal/mol.
   4. The optimized value of the grid size concentrated the searching region and produced uniform results structurally.









e 1 was identified. 2. Mode 4 presents a similar structure (RMSD: 1.835 Å) with relatively good affinity (−7.518 3. All the modes have a strong binding energy with a value less than −6.9 kcal/mol; in fact, the top 5 have a value of 4. The optimized value of the grid size concentrated the searching region and produced uniform results structurally.
