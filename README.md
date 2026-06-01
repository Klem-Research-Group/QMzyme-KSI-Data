# QMzyme-KSI-Data
Data repository associated with "QMzyme: A Python Package for Automated and Systematic QM-based Enzyme Modeling".

# Contents
* geometry_optimizations: Contains PDB files for each KSI-19NT active site model used in this study after geometry optimization.

* MM_minimization: Contains parameterization data for equilenin (EQU), and structure preparation.

* analysis_and_plotting_scripts: Contains scripts for parsing electric field data, determining RMSD and plotting data.

* active_site_model_generation: Contains the QMzyme script used to generated KSI-19NT active site models used i this study; the starting structures used to generate the models and perform the EQU-19NT ligand replacement; the QMzyme output: .pdb files of all initial model structures (pre-optimization), .csv file containing the QMzyme.QMzymeRegion.summarize() results, and the .pkl QMzyme.GenerateModel instance for all generated models; and the QCALC subdirectory that contains all the Gaussian and Orca input files.

* ksi_composed_data_qmzyme.xlsx: Contains raw values of all the data in the paper
