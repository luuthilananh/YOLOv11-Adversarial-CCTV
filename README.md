# 🛡️ Vulnerability of YOLO Detectors to Adversarial Attacks in Real CCTV Scenarios

![Python](https://img.shields.io/badge/python-3.8%2B-blue)
![PyTorch](https://img.shields.io/badge/PyTorch-%23EE4C2C.svg?style=flat&logo=PyTorch&logoColor=white)
![YOLO](https://img.shields.io/badge/YOLO-v11m-green)
![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)

> **Official repository for the Bachelor's Thesis (MIPT - МФТИ, 2026).**  
> **Author:** Luu Thi Lan Anh (Лыу Тхи Лан Ань)

## Abstract
This project investigates the vulnerability of **YOLOv11m** "out-of-the-box" to adversarial attacks in real-world urban CCTV scenarios (snow, night, top-down angles). We compare global invisible perturbations (UAP / AO-Exp) with local patches (T-SEA) and introduce a novel **video-level evaluation metric (LES/ER)** to demonstrate the complete failure of tracking systems.

## Key Highlights & Novelty
- **Custom CCTV Dataset:** 6 real-world scenes, ~11,000 frames manually annotated (Pedestrians & Vehicles).
- **UAP vs. Patch:** Demonstrated that global UAP structurally destroys the entire Feature Pyramid Network (FPN), proving far more effective than local patches.
- **Class Asymmetry:** Discovered that pedestrians are significantly more vulnerable than heterogeneous vehicles.
- **Video-Level Analysis (LES/ER):** Shifted evaluation from frame-by-frame (SR) to continuous tracking disruption, proving tracking systems drop objects completely.

## Important Links & Materials

Here you can find all the materials related to this thesis:

* **[Full Thesis Text (PDF)](https://drive.google.com/drive/folders/1jO3SHG_Z5sQjeYv8jblvqMUmiTZagKqs?usp=sharing)**
* **[CCTV Dataset & Annotations (.zip)](https://drive.google.com/drive/folders/1jO3SHG_Z5sQjeYv8jblvqMUmiTZagKqs?usp=sharing)**
