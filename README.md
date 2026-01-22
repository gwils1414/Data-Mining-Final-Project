# Data Mining — Final Project

A concise collection of notebooks and deliverables for the Data Mining final project. This repository contains the project analysis, modeling experiments, and formal write-ups produced as part of the course.

## Overview

This project applies data mining and machine learning methods to a real-world dataset (see the project write-up). The repository includes end-to-end Jupyter notebooks with exploratory data analysis, preprocessing, model development (including a sequential neural network), evaluation, and supporting deliverables such as executive summaries and a formal write-up.

Primary language: Jupyter Notebook

## Repository contents

- [Final Project Data Mining II.ipynb](https://github.com/gwils1414/Data-Mining-Final-Project/blob/main/Final%20Project%20Data%20Mining%20II.ipynb)  
  Main analysis notebook — contains the core exploratory data analysis, feature engineering, model training and evaluation workflows for the project.

- [Sequential Neural Network.ipynb](https://github.com/gwils1414/Data-Mining-Final-Project/blob/main/Sequential%20Neural%20Network.ipynb)  
  Focused notebook with experiments using a sequential neural network architecture (model definition, training loops, metrics and visualizations).

- [Data Mining Write Up UCDP_PRIO .docx](https://github.com/gwils1414/Data-Mining-Final-Project/blob/main/Data%20Mining%20Write%20Up%20UCDP_PRIO%20.docx)  
  Formal project write-up. (Filename suggests the analysis centers on the UCDP/PRIO dataset; see the document for methodology, results, and conclusions.)

- [Executive Summary.docx](https://github.com/gwils1414/Data-Mining-Final-Project/blob/main/Executive%20Summary.docx)  
  A concise technical executive summary of the project.

- [Executive Summary - Non Technical.docx](https://github.com/gwils1414/Data-Mining-Final-Project/blob/main/Executive%20Summary%20-%20Non%20Technical.docx)  
  A non-technical summary suitable for stakeholders without a technical background.

- README.md (this file)

## How to view the materials

- Jupyter notebooks:
  - View directly on GitHub (limited interactivity) or download and open locally with Jupyter Notebook / JupyterLab.
  - To run interactively, open the notebooks in a local environment, or upload to a service such as Google Colab (you may need to convert the notebook or import from GitHub).

- DOCX files:
  - Download and open with Microsoft Word, LibreOffice, or convert to PDF for sharing.

## Quick start — run locally

1. Clone the repository:
   ```
   git clone https://github.com/gwils1414/Data-Mining-Final-Project.git
   cd Data-Mining-Final-Project
   ```

2. Create and activate a virtual environment (example using conda):
   ```
   conda create -n datamining python=3.10 -y
   conda activate datamining
   ```

3. Install typical dependencies used for data mining and notebooks:
   ```
   pip install --upgrade pip
   pip install jupyterlab numpy pandas scikit-learn matplotlib seaborn notebook
   ```
   If you plan to run the neural network experiments:
   ```
   pip install tensorflow
   ```
   Note: The notebooks may include additional or specific package versions. Check the top cells of each notebook for exact dependencies and version notes.

4. Launch JupyterLab / Notebook:
   ```
   jupyter lab
   ```
   or
   ```
   jupyter notebook
   ```

## Data and reproducibility

- The notebooks contain the code used to process and analyze the dataset(s). If the project relies on external data (for example, UCDP/PRIO), consult the write-up for data sources and instructions for obtaining the data. If any data files are not included in this repository, follow the dataset acquisition steps listed in the notebooks or the written report.

- To reproduce results end-to-end:
  - Acquire the original dataset(s) as described in the write-up.
  - Ensure dependencies and package versions match those used in the notebooks.
  - Run the notebooks in order (start with the main analysis notebook).

## Findings and deliverables

- The repository includes:
  - Code for data processing and modeling (Jupyter notebooks).
  - Technical and non-technical executive summaries for different audiences.
  - A full written report describing the methodology, experiments, results, and conclusions.

## Contact

Repository owner: [gwils1414](https://github.com/gwils1414)
