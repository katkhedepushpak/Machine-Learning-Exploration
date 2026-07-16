# Machine-Learning-Exploration

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-green)

A collection of machine learning implementation assignments completed as part of Oregon State University's AI534 (Machine Learning) course. The notebooks progress from foundational supervised learning techniques through unsupervised methods, with each assignment implementing core algorithms from scratch using NumPy and validating results against scikit-learn. This repository serves as a hands-on reference for classical ML workflows — data preprocessing, model training, regularization, and evaluation — applied to real-world datasets.

---

## Highlights

- **Linear Regression** — closed-form (normal equation) and gradient descent solutions for house price prediction, including feature normalization and MSE evaluation
- **Logistic Regression** — binary classification with L1 and L2 regularization, applied to cross-domain insurance purchase prediction
- **SVMs & Naive Bayes** — TF-IDF–based sentiment classification using Support Vector Machines and Multinomial Naive Bayes with comparative evaluation
- **Unsupervised Learning** — dimensionality reduction (PCA, t-SNE) and KMeans clustering on pre-trained word embeddings, with an optional extension applying embeddings to sentiment classification
- Each notebook is self-contained with exploratory data analysis, model implementation, and result visualization

---

## Tech Stack

- **Language:** Python 3
- **Notebooks:** Jupyter Notebook
- **Core Libraries:**
  - `numpy` — numerical computation and manual algorithm implementation
  - `pandas` — data loading and preprocessing
  - `matplotlib` / `seaborn` — result visualization and plotting
  - `scipy` — statistical utilities (e.g., z-score normalization)
  - `scikit-learn` — evaluation metrics, TF-IDF vectorization, cross-validation, and baseline models

---

## Repository Structure

```
Machine-Learning-Exploration/
├── IA1.ipynb   # Linear Regression — house price prediction
├── IA2.ipynb   # Logistic Regression — insurance purchase classification
├── IA3.ipynb   # SVMs & Naive Bayes — sentiment classification
└── IA4.ipynb   # Unsupervised Learning — word embeddings, PCA, t-SNE, KMeans
```

---

## Getting Started

### Prerequisites

- Python 3.8 or higher
- `pip` package manager
- Jupyter Notebook or JupyterLab

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/katkhedepushpak/Machine-Learning-Exploration.git
   cd Machine-Learning-Exploration
   ```

2. Create and activate a virtual environment (recommended):
   ```bash
   python -m venv venv
   source venv/bin/activate      # macOS / Linux
   venv\Scripts\activate         # Windows
   ```

3. Install dependencies:
   ```bash
   pip install numpy pandas matplotlib seaborn scipy scikit-learn jupyter
   ```

4. Launch Jupyter:
   ```bash
   jupyter notebook
   ```

---

## Usage

Open any notebook in Jupyter and run cells sequentially. Each notebook is self-contained and includes:

- Data loading and exploratory analysis
- Feature engineering and preprocessing
- Model implementation (from scratch and/or via scikit-learn)
- Training, validation, and performance metrics

> **Note:** Assignment notebooks (IA1–IA4) reference local CSV data files (`ia1_train.csv`, `ia1_val.csv`, etc.) that are part of the original course dataset and may not be included in the repository. Replace data-loading cells with paths to your own compatible datasets if needed.

---

## Author

Built by [Pushpak Vijay Katkhede](https://katkhedepushpak.github.io)

Software Engineer | MS Computer Science, Oregon State University | Published at ICSE 2026
