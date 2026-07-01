# Rubus-caesius-Drug-Discovery
In silico analysis and molecular docking studies of Rubus caesius secondary metabolites.
# Rubus caesius Drug Discovery Project

This project focuses on the in silico analysis and molecular docking studies of secondary metabolites found in *Rubus caesius* (European Dewberry).

## Ligand Dataset (Target Compounds)

Below are the major phenolic and flavonoid compounds retrieved from PubChem using custom Python scripts (`pubchempy`):

| Compound Name | PubChem CID | SMILES Code |
| :--- | :--- | :--- |
| **Rutin** | 5280805 | C1=CC(=C(C=C1C2=C(C(=O)C3=C(C=C(C=C3O2)O)O)O[C@H]4[C@@H]([C@H]([C@@H]([C@H](O4)CO)O)O)O[C@H]5[C@@H]([C@H]([C@@H]([C@H](O5)C)O)O)O)O)O |
| **Tiliroside** | 5320701 | CC1C(C(C(C(O1)OC2=C(OC3=CC(=CC(=C3C2=O)O)O)C4=CC=C(C=C4)O)O)O)OC(=O)C=CC5=CC=C(C=C5)O |
| **Hyperoside** | 5281643 | C1=CC(=C(C=C1C2=C(C(=O)C3=C(C=C(C=C3O2)O)O)O[C@H]4[C@@H]([C@H]([C@@H](O4)CO)O)O)O)O |
| **Gallic acid** | 370 | C1=C(C=C(C(=C1O)O)O)C(=O)O |
| **Ellagic acid** | 5281855 | C1=C2C3=C(C(=C1)O)OC(=O)C4=CC(=C(C(=C43)OC2=O)O)O |

## Next Steps
*   [ ] Disease/Target protein selection from PDB (Protein Data Bank)
*   [ ] Structure preparation (Protein & Ligand minimization)
*   [ ] Molecular docking execution using AutoDock Vina
