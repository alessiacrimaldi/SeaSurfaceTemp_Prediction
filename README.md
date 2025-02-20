# 🌊 Sea Surface Temperature Reconstruction under Cloud Occlusion

![Python](https://img.shields.io/badge/Python-3.x-blue)
![TensorFlow](https://img.shields.io/badge/TensorFlow-2.x-yellow)
![Keras](https://img.shields.io/badge/Keras-2.x-green)

## 🔎 Overview

**Sea Surface Temperature (SST)** data are mostly acquired by means of satellites detecting the infrared radiation emitted from the sea surface. This radiation can be absorbed by cloud, causing large occlusions in collected observations.

This project focuses on reconstruting SST data affected by cloud occlusion using a deep learning approach to segment occluded areas and predict the missing temperature values accurately.

## 📦 Requirements

To run this project, ensure you have the following packages installed:

- Python 3.7+
- TensorFlow
- Keras
- NumPy
- Pandas
- Matplotlib

You can install them using the following command:
```
pip install tensorflow keras numpy pandas matplotlib
```

## 🔬 Dataset

The **Moderate Resolution Imaging Spectroradiometer (MODIS)** is a key instrument aboard NASA’s Aqua satellite, designed for Earth observation.
The dataset used in this project consists of nightly Sea Surface Temperature (SST) data collected over the North Adriatic Sea, a region characterized by dynamic oceanographic conditions and frequent cloud coverage.
