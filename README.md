**Predicting Antibiotic Accumulation in Pseudomonas aeruginosa**-Developing new therapeutics against Pseudomonas aeruginosa is essential in the global fight against antibiotic resistance. However, intrinsic resistance mechanisms—particularly outer membrane permeability and active efflux—remain poorly understood and significantly limit drug efficacy.

This project evaluates the ability of 300+ small molecules to accumulate inside P. aeruginosa and uses these data to build predictive machine learning models.
**Project Overview**
Compiled a dataset of experimentally measured intracellular accumulation values for >300 compounds in P. aeruginosa.

Explored multiple machine learning algorithms to model compound accumulation.

Identified Random Forest Regression as the top-performing model.

Model predictions closely matched experimental trends, particularly the observation that increasing hydrophilicity enhances antibiotic accumulation in P. aeruginosa.
**Key Findings**
Random Forest Regression outperformed linear models, SVMs, and neural networks in predicting accumulation values.

Molecular features related to polarity, hydrogen bonding, and hydrophilicity were strong predictors of uptake.

Results align with experimental evidence that hydrophilic modifications improve permeation across the outer membrane.
**Methods Used**
Data preprocessing and feature engineering

Molecular descriptor generation (e.g., RDKit)

Model training and hyperparameter tuning

Cross‑validation and performance benchmarking

Feature importance analysis
