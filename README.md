![Poster](https://github.com/alxfgh/BO-De-Novo-Drug-Design-Docking/blob/main/BO-De-Novo-Drug-Design-Docking-PosterPP_v2_page-0001.jpg)

This project employs Bayesian optimization using Gaussian process (GP) models with the Tanimoto kernel and fingerprint features for de novo design of selective growth factor receptor (GFR) inhibitors. GP surrogate models of docking scores will drive optimization of a docking-based objective function balancing potent target binding and minimal off-target interactions, with a drug-likeness penalty. The GP is trained on a subset of data, with new molecules proposed by a graph genetic algorithm, scored, and used to retrain the GP iteratively, aiming to identify promising selective GFR inhibitor candidates.

Building off the dockstring library (https://dockstring.github.io/)
