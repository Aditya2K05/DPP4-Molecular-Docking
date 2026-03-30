# Molecular Docking Study of DPP-4 Inhibitors

## Overview
Comparative docking of three approved DPP-4 inhibitors 
(alogliptin, sitagliptin, vildagliptin) against human DPP-4 
(PDB: 2ONC) using AutoDock Vina 1.2.7.

## Results Summary
| Ligand       | Binding Energy (kcal/mol) |
|--------------|--------------------------|
| Sitagliptin  | -10.11                   |
| Alogliptin   | -9.147                   |
| Vildagliptin | -7.862                   |

## Tools Used
AutoDock Vina 1.2.7 · MGLTools · PyMOL (open-source) · RDKit · Python

## Key Findings
- Sitagliptin showed highest predicted affinity, consistent with 
  published IC50 data
- Active site contacts confirmed: GLU206, SER630, TYR631, VAL207
- 4 hydrogen bonds identified (2.4–2.7 Å)
- Redocking RMSD: 2.365 Å

## Files
- /structures — prepared receptor and ligand PDBQT files
- /results — docking output files
- /figures — PyMOL visualisation images
- report.docx — full written report
