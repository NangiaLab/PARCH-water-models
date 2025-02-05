The repository contains the results of PARCH analysis conducted on fourteen proteins using the TIP3P, TIP4P, TIP4P-Ew, and TIP5P water models.

The MDP files for the equilibration and annealing process are stored under **mdp_files** folder.

The **subfolders named after the respective proteins** contain the following files in each of them:
- four PDB files of the protein tested with different water models, with PARCH values written as B-factors. 
- a CSV file summarizing the PARCH results across different water models.
- a PyMOL session file displaying the protein surface, colored (green-yellow-purple) according to PARCH values (0–1).
- the ITP file for protein
- a system_setup folder contains the structure files for PARCH annealing using different water models. (TIP4P and TIP4P-Ew share the same struture)
