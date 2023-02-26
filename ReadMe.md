# Molecular_docking_Vina_CPU
 Windows usage of AutoDock Vina CPU


# Usage

1. Create main folder with subfolders with protein domains (one folder per protein domain)
2. Ligands should be gathered in one excel file (*.xlsx)
3. Copy excel file with ligands to each of protein domain's directories, do the same with "Create folders for structures, 3D structures, distribute files and read results" notebook
4. Run notebook mentioned above (to get 3D structures of SMILES) 
5. Follow the description from the notebook
6. Use generated script (`Prepare_pdbqt_from_pdb.txt`) with the use of Open Babel ``https://openbabel.org`` (just copy paste it if Open Babel is installed)
7. After the ligands are prepared they can be distributed via the notebook
8. Use prompt and copy-paste created script (`to_be_executed.txt`) into it - it will do as many MDs as necessary - the number of ligands
9. Come back to the last part of the notebook to get excel sheet with results of molecular docking