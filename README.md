# Multi-Class-Land-Cover-Classification


# Multi-Class Land Cover Classification Using Hybrid Spectral-Spatial Deep Learning

This project implements a hybrid spectral-spatial deep learning approach to perform multi-class land cover classification using hyperspectral image data. The model leverages both the spectral (pixel-wise) and spatial (contextual) information from remote sensing imagery to improve classification accuracy.

## 🚀 Overview

Land cover classification is critical in applications such as urban planning, agriculture monitoring, and environmental management. Hyperspectral imaging provides rich spectral information that can be used to distinguish between land cover types. However, using only spectral information ignores the spatial relationships in the data.

In this project, we design and train a hybrid deep learning model that combines 1D CNNs for spectral feature extraction and 2D CNNs for spatial context, applied to hyperspectral image data.

## 🧠 Model Architecture

* **1D CNN** for Spectral Feature Extraction
* **2D CNN** for Spatial Context Learning
* Combined into a **Hybrid Deep Learning Framework**
* Final classification through a fully connected layer and softmax output

## 📊 Dataset

We use the **Indian Pines Hyperspectral Dataset**, which consists of 145×145 pixel images with 220 spectral bands. This dataset is commonly used in hyperspectral image classification tasks.

* Dataset Link:https://www.kaggle.com/datasets/apollo2506/eurosat-dataset?select=EuroSATallBands

> Note: You may need to preprocess the dataset into `.npy` or `.pkl` format as required by your code.

## 📁 File Structure

```
├── Code_File.ipynb        # Jupyter Notebook with model code
├── README.md              # Project overview
└── data/                  # Folder for storing dataset files
```

## 🛠️ Requirements

Install the required Python libraries:

```bash
pip install numpy scipy scikit-learn tensorflow matplotlib spectral
```

## 🔧 How to Run

1. Download and preprocess the dataset.
2. Open `Code_File.ipynb`.
3. Run each cell in order to:

   * Load data
   * Preprocess and extract patches
   * Train the model
   * Evaluate and visualize the results

## 📈 Evaluation Metrics

* Overall Accuracy (OA)
* Average Accuracy (AA)
* Kappa Coefficient
* Per-class Accuracy

## 📌 Results

Our hybrid model achieves superior performance compared to traditional methods by effectively capturing both spectral and spatial features of land cover types.

## 🤝 Contributing

Feel free to fork the repository, raise issues, or contribute new features or improvements!

## 📜 License

This project is licensed under the MIT License.
