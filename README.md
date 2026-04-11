# Introduction
Protein aggregation into amyloid fibrils is a hallmark of numerous neurodegenerative diseases and systematic diseases. Increasing evidence indicates that many amyloid-forming proteins exhibit structural polymorphism, giving rise to distinct fibril morphologies associated with variations in aggregation kinetics and disease phenotypes. Despite extensive studies, the mechanistic origin of such polymorphism, particularly its dependence on concentration and competing aggregation pathways, remains poorly understood.
We developed a multi-pathway kinetic model to investigate amyloid aggregation and the emergence of fibril polymorphism. The model captures the time evolution of monomers, oligomer of distinct sizes, and multiple fibril species, allowing us to systemically analyze how nucleus size, oligomer stability and fibrilization barrier govern morphological selection and alter aggregation dynamics. By exploring a wide range of conditions, we reveal how competing pathways lead to concentration-dependent transitions between distinct fibril morphologies. As an extension, we further incorporate LLPS into our model to examine its modulatory role in multi-pathway aggregation.
This archive contains all simulated data and corresponding python notebooks.
# Directory Structure:
In uploaded files section, there are two zip files. They represent:
1.	Python Notebooks
2.	Data

# Python Notebooks:

This zip file contains a complete set of Jupyter notebooks used to simulate, analyze, and visualize amyloid aggregation kinetics. These notebooks are designed to be self-contained and reproducible.

Each notebook typically performs the following task:
*Simulates and plots the time evolution of key species (monomers, droplets, oligomers and fibrils).
*Saves the time evolution of fibril mass as .npy files for further analysis.
*Analyzes kinetic behavior across a range of initial protein concentration and plots half-time as a function of concentration as well as the time evolution of normalized fibril mass for the given total protein concentration. 
Parameter variation:
Each of these notebooks is labeled clearly to indicate the specific parameter or condition being varied. They are as follows:
1.	Fig_2A.ipynb → It saves the time evolution of fibril mass (Fig_2A.npy) and reproduces Fig. 2A and bottom panel of Fig. 2B for the default parameter set (Table 1).
2.	Fig_2B_top.ipynb → It reproduces top panel of Fig. 2B.
3.	Fig_2C_top1.ipynb → It reproduces top and left panel of Fig. 2C.
4.	Fig_2C_top2.ipynb → It reproduces top and right panel of Fig. 2C.
5.	Fig_2C_bottom1.ipynb → It reproduces bottom and left panel of Fig. 2C.
6.	Fig_2C_bottom2.ipynb → It reproduces bottom and right panel of Fig. 2C.
7.	Fig_3A.ipynb → It reproduces Fig. 3A (in log-linear scale) for varying fibril stability.
8.	Fig_3B.ipynb → It reproduces Fig. 3B (in both log scale) for varying fibril stability.
9.	Fig_4.ipynb → It reproduces Fig. 4A, 4B for three-parallel pathway aggregation model.
10.	Fig_5A.ipynb → It reproduces Fig. 5A for two-parallel pathway aggregation model incorporating liquid-liquid phase separation (LLPS) for more stable oligomers than droplets. 
11.	Fig_5B.ipynb → It reproduces Fig. 5B for two-parallel pathway aggregation model incorporating liquid-liquid phase separation (LLPS) for more stable droplets than oligomers. 
12.	Fig_6A.ipynb → It saves the time evolution of fibril mass (Fig_6A.npy) and reproduces Fig.6A.
13.	Fig_6B_top.ipynb → It reproduces Fig. 6B, top panel.
14.	Fig_6B_bottom.ipynb → It reproduces Fig. 6B, bottom panel.
15.	Fig_S1.ipynb  →  It reproduces Fig. S1 for varying conformation conversion barrier.

# Data:

This zip file contains ‘.npy’ files generated using the Python Notebooks. We have generated such files only for those cases in which we compute kinetic parameter such as half-time or time evolution of normalized fibril mass. Python scripts to compute kinetic parameter are also provided in the corresponding Python Notebooks. Each file represents the ‘time evolution of fibril mass’ at multiple discrete point concentrations (typically between 0.6µM to 500µM). These datasets support the figures presented in the article.

File naming and descriptions
1.	Fig_2A.npy → It reproduces Fig. 2A, bottom panel of Fig. 2B.
2.	Fig_6A.npy → It reproduces top panels of Fig. 6A.
	
All data are available on Zenodo at https://doi.org/10.5281/zenodo.19512643.
