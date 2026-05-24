# Reproducible Research -  AdvVisR Reproduction in Python

![Project Status](https://img.shields.io/badge/Status-In%20Progress-orange)
![Course](https://img.shields.io/badge/Course-Reproducible%20Research-blue)
![Git](https://img.shields.io/badge/Version%20Control-Git-F05032?logo=git&logoColor=white)

## Authors
* **Aleksandra Szpakowska**
* **Weronika Mądro**
* **Wojciech Hrycenko**
* Course Year: 2025/26

## What this project does
This project is a reproduction of the **[WojciechHrycenko/AdvVisR](https://github.com/WojciechHrycenko/AdvVisR)** study. We are porting an entire analytical pipeline and advanced visualizations from **R to Python** to evaluate cross-language reproducibility. 

## Research question
How effectively can complex R-based data visualizations (like ridgeline, dumbbell, and radar plots) be reproduced in Python, and what are the primary challenges in ensuring a fully reproducible cross-language workflow?

## Motivation
The primary focus is on the process of reproduction rather than analytic correctness. We aim to document the challenges of cross-language reproduction, implement good coding practices, and collaborate effectively via Git.

## Data
The dataset consists of simulated records regarding fitness activities, nutritional habits, and physiological metrics. It is provided directly in the repository within the `Data/` directory.

## Requirements
* Python >= 3.10
* Jupyter Notebook

## Setup
It is recommended to use a virtual environment (`venv` or `conda`). To set up the environment and install dependencies:

```bash
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`
pip install pandas numpy matplotlib seaborn plotly squarify joypy scipy pyjanitor kaleido jupyter
```
*Tip: For stricter reproducibility, you can freeze these dependencies into a `requirements.txt` file.*

## How to run
Execute the complete pipeline via Jupyter Notebook:
```bash
jupyter notebook RR_final_project.ipynb
```
Run all cells from top to bottom. The notebook will automatically process the data and generate the output visualizations.

## Expected output
The notebook generates reproducible visualization charts (e.g., radar, treemap, ridgeline, dumbbell, correlation plots). All output plots are saved directly into the `outputs/figures/` directory. 

## Repository structure
```text
├── README.md               # Project description, setup, how to run
├── Data/                   # Raw datasets and custom macro script
│   ├── Final_data.csv
│   ├── Final_data_model.csv
│   ├── meal_metadata.csv
│   └── data_modelling_macros.py
├── outputs/
│   └── figures/            # Rendered visualization plots
└── RR_final_project.ipynb  # Main entry point and analysis pipeline
```

---

## Deadlines & Project Milestones

| Date | Milestone | Status |
| :--- | :--- | :--- |
| **March 28, 2026** | Send information about teams | ✅ Done |
| **April 18, 2026** | Provide the link to the team's GitHub repository | ✅ Done |
| **May 6, 2026** | Confirm project topics | ✅ Done |
| **June 13, 2026** | Repository freeze | ⏳ Pending |
