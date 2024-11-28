# Sleep Related Brain Actvity
- Emma van den Brink
- Date notebook was completed: 28-11-2024
- The links to the Neurosynth pages of sleep related brain activity: https://neurosynth.org/analyses/terms/sleep/

This project uses MRI data to visualize and interpret brain activity during sleep. This project layers functional data onto anatomical brain structures to create a statistical brain map, to highlight active brain regions during sleep. Additionaly, it generates a histogram of the voxel intensity to analyze the distribution of brain acitivity during sleep. 

---

## Table of Contents

| Section                 | Description                                                                       |
|-------------------------|-----------------------------------------------------------------------------------|
| **Introduction**         | Brief overview of the project and its objectives.                                 |
| **Data Used**            | Information on the MRI data files (functional and anatomical) used in the analysis. |
| **Notebook and Scripts** | The Jupyter Notebook (`HomeAssignment.ipynb`) containing the analysis code. |
| **Outputs**              | Visual outputs generated, including a brain map and histogram of voxel intensities. |
| **Python Packages Used** | List of Python libraries used in the project.                                      |

---
## Introduction
This project visualizes brain activity during sleep by overlaying functional MRI data onto anatomical brain structures. Outputs include a statistical brain map and a histogram of voxel intensities.  

## Data Used
- Functional MRI data (`*.nii`) highlighting brain activity during sleep.  
- Anatomical MRI data (`*.nii`) used as the background structure for visualization.  

## Notebook and Scripts
The main analysis is performed in the Jupyter Notebook:  
- `HomeAssignment.ipynb`  

## Outputs
- A statistical brain map showing regions active during sleep.  
- A histogram of voxel intensities representing brain activity distribution.  

## Python Packages Used
- **`os`**: File and directory management.  
- **`glob`**: File pattern matching and searching.  
- **`nibabel`**: Loading and processing `.nii` MRI files.  
- **`nilearn`**: Visualization of brain activity (`plot_stat_map`) and computing cut coordinates.  
- **`matplotlib`**: Generating histograms and other visualizations.  

