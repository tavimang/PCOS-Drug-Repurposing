
# PCOS Drug Repurposing Using Molecular Docking

## Project Overview
This project investigates the predicted binding interactions of five drug-like compounds with protein tyrosine phosphatase 1B (PTP1B), a protein involved in insulin signaling.

## Research Question
Can existing drug-like compounds demonstrate favorable predicted binding interactions with a protein involved in insulin resistance, suggesting potential candidates for further PCOS research?

## Compounds Investigated
- Empagliflozin
- Sitagliptin
- Berberine
- Pioglitazone
- Orlistat

## Computational Methods
- Protein: PTP1B (PDB ID: 1NL9)
- Molecular docking: AutoDock Vina
- Ligand preparation: RDKit and Meeko
- Analysis: Python, pandas, Biopython, SciPy
- Visualization: matplotlib

## Project Files
- `data/` - Protein structures and compound information
- `notebooks/` - Protein preparation, validation, and drug screening code
- `docking/` - Prepared receptor, ligand structures, and docking poses
- `results/` - Docking scores and interaction analysis
- `figures/` - Scientific plots
- `report/` - Final research report

## Reproducibility
1. Create the Conda environment using `environment.yml`.
2. Open the notebooks in numerical order.
3. Run the protein preparation and redocking analysis.
4. Run the five-compound screening notebook.
5. Examine the generated figures and results.

The docking experiments used a random seed of 42 and a 24 x 24 x 24 Angstrom search box centered at (33.68, 28.42, 20.58).

## Main Findings
Empagliflozin received the most favorable predicted docking score (-7.535 kcal/mol), followed by sitagliptin (-7.432 kcal/mol).

The results are exploratory and do not demonstrate experimental PTP1B inhibition or therapeutic effectiveness for PCOS.
