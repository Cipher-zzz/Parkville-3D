# Parkville-3D Dataset

[![License: CC BY 4.0](https://img.shields.io/badge/License-CC_BY_4.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.18813190.svg)](https://zenodo.org/records/18813190)

**Parkville-3D** is a 3D point cloud dataset captured in complex urban environments. It is specifically curated to support research in **semantic segmentation** and **instance segmentation**, with a particular focus on the challenges of urban infrastructure and pole-like objects.

---

## 📥 Dataset Download

The dataset is officially hosted on **Zenodo**. You can download the point cloud files and labels via the link below:

👉 **[Download Parkville-3D on Zenodo](https://zenodo.org/records/18813190)**

---

## 🖥️ Visualization & Usage

We recommend using **[CloudCompare](https://www.danielgm.net/cc/)** for high-performance viewing and basic processing of the dataset.

### 1. Selecting Scalar Fields
To view the labels, please select the appropriate **Scalar Fields** in the properties panel as shown below:

<img src="https://github.com/user-attachments/assets/36f671b4-9922-4e9a-95cb-6771847eee92" width="500" alt="CloudCompare Scalar Fields Selection" />

### 2. Viewing Labels
Once selected, you can toggle between **Class Labels** or **Instance Labels** to visualize the ground truth:

<img src="https://github.com/user-attachments/assets/8a9510ec-a4db-462e-8623-dcc23a66f327" width="500" alt="Point Cloud Label Visualization" />

---

## 📝 To-Do List

We are actively maintaining this repository to support the research community.

- [x] **Release Download Link**
- [x] **CloudCompare Usage Tutorial**
- [ ] **Python Utilities**: Scripts for data loading, `.las`/`.ply` conversion, and evaluation metrics.
- [ ] **Detailed Documentation**: Comprehensive breakdown of acquisition sensors, urban environment specifications, and label definitions.

---

## 🎓 Citation

If you use this dataset in your research, please cite our work:

```bibtex
@article{zhang2024pole,
  title={Pole-NN: Few-shot classification of pole-like objects in lidar point clouds},
  author={Zhang, Zezheng and Khoshelham, Kourosh and Shojaei, Davood},
  journal={ISPRS Annals of the Photogrammetry, Remote Sensing and Spatial Information Sciences},
  volume={10},
  pages={333--340},
  year={2024},
  publisher={Copernicus Publications G{\"o}ttingen, Germany}
}
