# Norcia_clustering
The scripts in this repository perform the cluster analyses and the fault plane identifications presented in Piegari et al. (2025), submitted to Geophysical Research Letters. 

## Scientific publication
If you use the codes in this repository, please cite the publication: Piegari et al. (2025). Structural heterogeneities and spatial variation of seismicity drive temporal changes in the b-value. Geophys. Res. Lett. submitted. 

## Installation
To make these MATLAB scripts work on your machine you need to install the Statistics and Machine Learning Toolbox of MATLAB. 

## Modules
The MATLAB codes stored in the folder are:
- DBSCAN + PCA for identifying clusters: Norcia_clustering_subperiods.m
- OPTICS for determination of reachability plot: reachability_plot.m
- PCA analysis and fault parameter estimation: pca_planar_surface.m
- PCA analysis and fault parameter estimation: pca_valleys.m
- code that computes distances of hypocenters from the first plane: dist_first_period.m
- code that computes distances of hypocenters from the second plane: dist_second_period.m
- code that computes distances of hypocenters from the planes: dist_third_period.m
- code that computes distances of hypocenters from the planes: dist_fourth_period.m

