# mri-simon-analysis

🧠 Structural MRI Analysis Practice with the SIMON Dataset

This repository documents a hands-on learning project on structural MRI analysis, using anatomical brain scans from the SIMON dataset (1000 Functional Connectomes Project – INDI).

The goal is to build a reproducible workflow for structural neuroimaging, covering image inspection, preprocessing concepts, tissue segmentation, and quantitative brain feature exploration.

🔗 Dataset: SIMON Dataset (INDI Retrospective Collection)
https://fcon_1000.projects.nitrc.org/indi/retro/SIMON.html

🎯 Project Objectives

This project focuses on developing practical skills in:

Understanding 3D MRI anatomical data

Inspecting MRI header and spatial metadata

Performing basic structural preprocessing

Exploring brain tissue characteristics

Extracting quantitative anatomical features

Building a clean and reproducible neuroimaging workflow in Python

🗂 Repository Structure

```text
mri-simon-structural-analysis/
│
├── data/                  # Raw MRI data (not uploaded)
├── notebooks/
│   ├── 01_mri_data_loading.ipynb
│   ├── 02_mri_visualization.ipynb
│   ├── 03_image_preprocessing_concepts.ipynb
│   ├── 04_tissue_intensity_analysis.ipynb
│   ├── 05_brain_masking_and_segmentation.ipynb
│   └── 06_quantitative_feature_extraction.ipynb
│
├── src/
│   ├── io_utils.py
│   ├── visualization_utils.py
│   ├── preprocessing_utils.py
│   └── feature_extraction.py
│
├── figures/
├── environment.yml / pyproject.toml
└── README.md


