# MutsPPIs

## File 1: blindtest.csv

This file comprises data on protein database (PDB) files, mutation details, and related experimental outcomes. It enumerates specific mutation combinations for each PDB file, the experimentally determined changes in free energy (experimental_ddg), and the predicted changes in free energy as calculated by three distinct computational methods: foldx, discovery_studio, and mmCSM-PPI. This comprehensive dataset supports the analysis of protein structure and mutation effects, and is instrumental in validating the accuracy of computational models.

## File 2: blindtest_zemu.csv

This file provides experimental data alongside corresponding computational predictions for various mutations within different PDB files. Each record includes the PDB file identifier, mutation details, experimentally measured changes in free energy (experimental_ddg), and predicted changes in free energy using the zemu and mmCSM-PPI models. This dataset facilitates a comparative analysis of different predictive models, enabling the evaluation of their accuracy and reliability across diverse mutation scenarios.

## File 3: train_set.csv

This file serves as a training dataset, detailing PDB files, mutation information, mutation types (forward or reverse), experimentally measured changes in free energy (ddg), and predicted changes in free energy using the mmCSM-PPI model (prediction_mmCSM-PPI). This dataset is foundational for training machine learning models, supporting the development and optimization of computational methods aimed at predicting alterations in protein-protein interactions.
