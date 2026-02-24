# mri-simon-analysis

🧠 Structural MRI Analysis Practice with the SIMON Dataset

This repository documents a hands-on learning project on structural MRI analysis, using anatomical brain scans from the SIMON dataset (1000 Functional Connectomes Project – INDI).

The goal is to build a reproducible workflow for structural neuroimaging, covering image inspection, preprocessing concepts, tissue segmentation, and quantitative brain feature exploration.

🔗 Dataset: SIMON Dataset (INDI Retrospective Collection)
https://fcon_1000.projects.nitrc.org/indi/retro/SIMON.html

[More up-to-date dataset may refer: https://staging.openneuro.org/datasets/ds001037/versions/1.0.1 for futher exploring]

🎯 Project Objectives

This project focuses on developing practical skills in:

Understanding 3D MRI anatomical data

Performing basic structural preprocessing

Exploring brain tissue characteristics

Extracting quantitative anatomical features

Building a clean and reproducible neuroimaging workflow in Python

🗂 Repository Structure

```text
mri-simon-structural-analysis/
│
├── data/                  # Raw MRI data (not uploaded)
├── notebooks/             # For learning and exploring
│   ├── 01_data_loading.ipynb
│   ├── 02_visualization.ipynb
│   ├── 03_image_preprocessing.ipynb
│   ├── 04_tissue_intensity_analysis.ipynb
│   ├── 05_brain_masking_and_segmentation.ipynb
│   └── 06_quantitative_feature_extraction.ipynb
│
├── src/                  # for reproducible workflows
│
├── figures/
└── README.md


📗 Important information

Core workflow (typically most of the time will be spending on the preprocessing of the data):
1. Brain extraction
2. Tissue Segmentation
3. Spatial Normalisation: Align different brain into nomarlized template (e.g. MNI152)
4. Smoothing: lower the noise
5. Quality Control: check results manualy
6. Feature Extraction: for example, Hippocampal Volume, Cortical Thickness.



