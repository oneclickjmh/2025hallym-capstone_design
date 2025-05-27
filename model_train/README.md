#Training Code Overview

This folder contains all the training scripts used in this project.

##Included Components
- `classification/` : Hair loss stage classification (Stages 1–7) based on the **Hamilton-Norwood scale**
- `segmentation/` : Hair/scalp segmentation using **YOLOv8**
- `visualization/` : CAM-based visualizations and model interpretability analysis
- `final_app/` : Final pipeline for integration with the mobile application

##Notes
- Dataset paths are **not hardcoded**. You need to specify your dataset directory before running any training.
- **Trained `.pt` model files are not included** in this repository. You must train or load your own models for inference.
- This repository contains only the source code. Model training must be performed separately.
