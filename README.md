# Beyond the teacher : Novel pipeline for Imitation Learning (IL) Method

This repository contains the code, datasets, experiments, and evaluations for a proposed method in **Beyond the Teacher*.  

| Folder          | Description                                                                 |
|-----------------|-----------------------------------------------------------------------------|
| `Demo_utility/` | Core Jupyter notebook for **demo/data utility scoring** and **demo/data cleaning pipeline**. |
| `Picknplace/`   | Implements the **Pick-and-Place task**, including datasets, models, and scoring notebooks (evaluation scripts). |
| `Weaving/`      | Implements the **Weaving task**, including datasets, models, and scoring notebooks (evaluation scripts)  |
| `Wiping/`       | Implements the **Wiping task**, including datasets, models, and scoring notebooks (evaluation scripts) |

---

## Folder Structure

### 1. Demo_utility/
Contains the core Jupyter notebook `demo_utility.ipynb`, which includes:
- **Demo/Data Utility Scoring** – Quantitative evaluation of dataset usefulness for model training.
- **Data Cleaning** – Implements the proposed data-cleaning pipeline.

### 2. Picknplace/
Implements the **Pick-and-Place task**:
- `data/` – Datasets for training and reward calculation.
- `models/` – Jupyter notebooks for training IL models and generating rollouts.
- `scoring/` – Notebooks for computing value maps and evaluating IL methods.

### 3. Weaving/
Implements the **Weaving task**:
- `data/` – Task-specific datasets.
- `models/` – Jupyter notebooks for model training and rollout generation.
- `scoring/` – Notebooks for evaluation and scoring of IL methods.

### 4. Wiping/
Implements the **Wiping task**:
- `data/` – Task-specific datasets.
- `models/` – Jupyter notebooks for training and rollout generation.
- `scoring/` – Notebooks for evaluation and scoring of IL methods.

---

