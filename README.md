# Mol2smiles-rdkit

This repository contains code and a Jupyter notebook for extracting SMILES (Simplified Molecular Input Line Entry System) representations of drugs listed in the DrugComb dataset. For each drug name, the code queries the PubChem REST API using the following endpoint:
https://pubchem.ncbi.nlm.nih.gov/rest/pug/compound/name/{name}/property/IsomericSMILES/TXT
The response returns the Isomeric SMILES string for the compound, which is then saved or processed as needed. 
This script is useful for researchers working with drug response data who need to integrate molecular structure information into their analyses. The approach is lightweight, requires no API key, and is ideal for quick lookups or data preprocessing tasks involving drug names.

