
# 🌌 Pulsar Classification 🌌

Welcome to **Pulsar Classification** – a repository dedicated to identifying pulsars from noisy data using advanced machine learning techniques! Pulsars, the highly magnetized rotating neutron stars that emit beams of electromagnetic radiation, are rare celestial objects, and spotting them in datasets is no easy task. This repo is here to tackle that challenge! 🚀✨

![GitHub Repo Size](https://img.shields.io/github/repo-size/mohamed-moslemani/pulsar-classification)
![License](https://img.shields.io/github/license/mohamed-moslemani/pulsar-classification)
![GitHub last commit](https://img.shields.io/github/last-commit/mohamed-moslemani/pulsar-classification)

## 🌠 Project Overview

In this project, we use machine learning models to classify pulsars from a dataset of candidates by analyzing features derived from radio frequency signals. Due to the imbalance in the data (more non-pulsars than pulsars), techniques like **SMOTE (Synthetic Minority Over-sampling Technique)** are used to generate synthetic samples, helping our models improve classification accuracy.

## 🔍 Key Components

- **Data**: Preprocessed pulsar data, including synthetic samples generated with SMOTE for balanced training.
- **Models**: A variety of classifiers including Random Forest, Logistic Regression, and others implemented and tested for effectiveness.
- **RBMs (Restricted Boltzmann Machines)**: Used for feature generation and to enhance data diversity, aiding in more robust model training.

## 📄 Contents

| File/Folder       | Description                                                                 |
|-------------------|-----------------------------------------------------------------------------|
| `data/`           | Contains raw and generated data for training and testing.                   |
| `pulsar.ipynb`    | Notebook with Random Forest classification on RBM-generated data.           |
| `RBMs.ipynb`      | Implements Restricted Boltzmann Machines for feature generation.            |
| `SMOTE.ipynb`     | Applies SMOTE for data augmentation and explores classification techniques. |
| `README.md`       | The README file providing project overview and usage instructions.          |

## 📊 Features

- **Data Augmentation with SMOTE**: Enhances model training on imbalanced datasets by generating synthetic samples for minority classes.
- **Feature Engineering with RBMs**: Restricted Boltzmann Machines provide additional features, allowing models to capture more complex patterns in the data.
- **Multi-Model Classification**: Evaluate various classifiers to find the most effective method for identifying pulsars.

## 🔧 Getting Started

1. **Clone the Repository**

   ```bash
   git clone git@github.com:Mohamed-Moslemani/pulsar-classification.git
   ```

2. **Navigate to the Directory**

   ```bash
   cd pulsar-classification
   ```

3. **Install Dependencies**

   Make sure you have the required libraries installed. You can do so by running:

   ```bash
   pip install -r requirements.txt
   ```

4. **Run the Notebooks**

   Each notebook serves a specific function in the classification process. Start by running the data augmentation and RBM notebooks, then proceed to the classification notebook:

   ```bash
   jupyter notebook
   ```

## 📐 Technologies Used

- **Python**: Programming language used for all scripts and notebooks.
- **Machine Learning Libraries**: Scikit-Learn, Imbalanced-learn (for SMOTE), and PyTorch (for RBMs).
- **Data Handling**: Pandas and NumPy

## 🤔 How to Contribute

Found a way to improve pulsar detection? We’d love to see your contributions!

1. **Fork this repository**
2. **Create your branch**: `git checkout -b new-pulsar-feature`
3. **Commit your changes**: `git commit -m "Add new model for pulsar classification"`
4. **Push to the branch**: `git push origin new-pulsar-feature`
5. **Submit a pull request**

## 📝 License

This project is licensed under the MIT License. Check out the [LICENSE](LICENSE) file for more details.

## 🌌 Acknowledgments

Thanks to all contributors, the open-source community, and the developers of the tools that made this project possible. Special recognition goes to astronomers and data scientists who continue to expand our knowledge of the cosmos.

---

**Ready to find some pulsars? Let’s get classifying! 🛰️✨**

