# Applied Machine Learning Projects

![Python](https://img.shields.io/badge/python-3.x-blue)
![Machine Learning](https://img.shields.io/badge/machine-learning-green)

This repository contains small **applied machine learning and computational modeling projects** implemented in Python.

The goal is to explore practical ML techniques and simulation methods through **self-contained experiments**.

---

# Repository Structure

```
ML-projects
│
├── knn-song-classification
│   └── kNN.ipynb
│
├── boids-simulation
│   └── boids.ipynb
│
└── README.md
```

---

# Projects

| Project | Description | Techniques |
|------|------|------|
| **Song Classification** | Music genre classification using kNN | supervised learning, feature scaling |
| **Boids Simulation** | Agent-based simulation of flocking behavior | neighbor search, swarm modeling |

---

# Project 1 — Song Classification with k-Nearest Neighbors

Location:

```
knn-song-classification/kNN.ipynb
```

This notebook implements a **machine learning pipeline for classifying songs** based on extracted audio features.

The model uses the **k-Nearest Neighbors (kNN)** algorithm to classify songs based on similarity in feature space.

---

## Machine Learning Pipeline

The notebook demonstrates a typical ML workflow:

1. Data loading
2. Feature preprocessing
3. Feature scaling
4. Train/test split
5. Model training
6. Model evaluation

---

## Feature Scaling

The project compares several scaling techniques:

- StandardScaler
- MinMaxScaler
- RobustScaler

This allows evaluating how **feature normalization affects model performance**.

---

## Evaluation

The model is evaluated using:

- cross-validation accuracy
- confusion matrix
- classification metrics

Visualization is performed using **Matplotlib** and **Seaborn**.

---

# Dependencies

Typical dependencies include:

```
numpy
pandas
matplotlib
seaborn
scikit-learn
pygame
```

Install them with:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn pygame
```

# Project 2 — Boids Flocking Simulation

Location:

```
boids-simulation/boids.ipynb
```

This notebook implements a **Boids simulation**, an agent-based model that reproduces flocking behavior observed in birds and fish.

The model is based on three fundamental rules applied to each agent:

1. **Separation** — avoid crowding neighbors  
2. **Alignment** — match velocity with nearby agents  
3. **Cohesion** — move toward the local center of mass

These simple rules produce **emergent collective behavior**.

---

## Technologies

- Python
- NumPy
- pygame
- scikit-learn

---

## Output

The notebook produces a **visual simulation of flocking agents** evolving dynamically over time.

Such models are widely used to study:

- swarm intelligence
- collective motion
- emergent behavior

---

# Running the Projects

Run the notebooks using Jupyter:

```bash
jupyter notebook
```

Then open:

```
boids-simulation/boids.ipynb
```

or

```
knn-song-classification/kNN.ipynb
```

---

# Purpose

These projects explore:

- neighbor-based algorithms
- machine learning classification
- agent-based modeling
- data preprocessing techniques
