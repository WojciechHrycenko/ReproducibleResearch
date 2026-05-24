# AdvVisR Reproduction in Python

![Project Status](https://img.shields.io/badge/Status-In%20Progress-orange)
![Course](https://img.shields.io/badge/Course-Reproducible%20Research-blue)

## Authors
* **Aleksandra Szpakowska**
* **Weronika Mądro**
* **Wojciech Hrycenko**
* Course: Reproducible Research (Year: 2025/26, Group: [Wpisz numer grupy])

## What this project does
This project evaluates cross-language reproducibility by porting an advanced data visualization pipeline from R to Python. It processes simulated fitness, nutrition, and physiological data to accurately recreate complex charts (e.g., ridgeline, dumbbell, and radar plots) using Python libraries.

## Requirements
* Python >= 3.10
* Jupyter Notebook or JupyterLab
* Git

## Setup
```bash
git clone [https://github.com/WojciechHrycenko/ReproducibleResearch.git](https://github.com/WojciechHrycenko/ReproducibleResearch.git)
cd ReproducibleResearch

# Create and activate virtual environment
python -m venv .venv

# On macOS/Linux:
source .venv/bin/activate
# On Windows:
.venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt
```
*(Note: To generate the requirements file if you haven't yet, run `pip freeze > requirements.txt` locally after installing your packages).*

## How to run
```bash
jupyter notebook RR_final_project.ipynb
```
Once Jupyter opens, select **Kernel** -> **Restart & Run All** (or use the equivalent "Run All" button). The notebook runs completely automatically.

## Expected output
The complete pipeline takes approximately **2–3 minutes** to run on a standard laptop. It will process the raw datasets and generate several advanced `.png` visualization charts. All output images are automatically saved in the `outputs/figures/` directory.

## Repository structure
```text
├── README.md               # Project description, setup, how to run
├── requirements.txt        # Pinned Python dependencies
├── Data/                   # Raw datasets and custom macro script
│   ├── Final_data.csv
│   ├── Final_data_model.csv
│   ├── meal_metadata.csv
│   └── data_modelling_macros.py
├── outputs/
│   └── figures/            # Rendered visualization plots
└── RR_final_project.ipynb  # Main entry point and analysis pipeline
```
