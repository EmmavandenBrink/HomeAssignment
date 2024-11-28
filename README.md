# Home Assignment - Sleep Related Brain Activity 

- **Student**: Emma van den Brink
- **Course code**: M_PROPSY
- **Course Coordinator**: Matthias Nau
- **Teaching Assistent**: Anna van Harmelen
- **Date**: 8-11-2024
- **Link**: https://neurosynth.org/analyses/terms/sleep/ 

    - The files *Sleep: Uniformity test* and *Anatomical* were used from **Neurosynth**

This is a Home Assignment for the course *Programming For Psychologists* at the Vrije Univesiteit Amsterdam during the period sep-dec. This project uses MRI data from Neurosynth to visualize and interpret brain activity during sleep. This project layers functional data onto anatomical brain structures to create a statistical brain map and generates a histogram of the voxel intensity to analyze the distribution of brain acitivity during sleep. 

---

## Table of Contents

| Section                 | Description                                                                       |
|-------------------------|-----------------------------------------------------------------------------------|
| **Data Used**            | Information on the MRI data files (functional and anatomical) used in the analysis. |
| **Notebook and Scripts** | The Jupyter Notebook (`HomeAssignment.ipynb`) containing the analysis code. |
| **Outputs**              | Visual outputs generated, including a brain map and histogram of voxel intensities. |
| **Python Packages Used** | List of Python libraries used in the project.                                      |

---
## Data Used
- Functional MRI data (`*.nii`) highlighting brain activity during sleep.  
- Anatomical MRI data (`*.nii`) used as the background structure for visualization.
- Source: Neurosynth: Sleep, the files 'Anatomical' and 'Uniformity test' were used

## Notebook and Scripts
The main analysis is performed in the Jupyter Notebook:  
- `HomeAssignment.ipynb`  

## Outputs
- A statistical brain map showing regions active during sleep.  
- A histogram of voxel intensities representing brain activity distribution.  

## Python Packages Used [Python version 3.12.7]
- **`os`**
- **`glob`**
- **`nibabel`**
- **`nilearn`**
- **`matplotlib`**

