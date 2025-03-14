# RAPIDS Data Processing Lab for NVIDIA AI Workbench

## Overview
This Jupyter Notebook is designed to help beginners understand how to load, clean, and process datasets using **RAPIDS cuDF** (GPU-accelerated Pandas equivalent).

## Prerequisites
- **NVIDIA AI Workbench** installed
- **NGC RAPIDS container** (`nvcr.io/nvidia/rapidsai/rapidsai:23.10-cuda11.8-runtime-ubuntu22.04`)
- **JupyterLab** (pre-installed in the RAPIDS container)

## Quick Setup in NVIDIA AI Workbench

### Option 1: One-Click GitHub Import
1. Open **NVIDIA AI Workbench**
2. Click **"New Project"** → **"Import from GitHub"**
3. Paste this repository link:
   ```
   https://github.com/YOUR_GITHUB_USERNAME/nvidia-ai-workbench-labs
   ```
4. Click **"Import"**

### Option 2: Manual Setup
1. **Launch AI Workbench**, create a new project.
2. **Add an NGC Container**
   - Go to **Containers** → **Add NGC Catalog Container**.
   - Search for **RAPIDS** and select:
     ```
     nvcr.io/nvidia/rapidsai/rapidsai:23.10-cuda11.8-runtime-ubuntu22.04
     ```
   - Click **Use Container**.
3. **Start JupyterLab**
   - Open a terminal inside the running container.
   - Run the command:
     ```bash
     jupyter-lab --ip=0.0.0.0 --allow-root --NotebookApp.token=''
     ```
4. **Upload and Run the Notebook**
   - Open **JupyterLab**.
   - Upload `data_loading_rapids.ipynb`.
   - Run all cells.

## What This Lab Covers
- Loading CSV data with **cuDF**
- Handling missing values
- Sorting and filtering
- Feature engineering
- Saving processed data

## Next Steps
- Try loading different datasets
- Experiment with cuDF transformations
- Learn about other RAPIDS libraries like **cuML** for machine learning

---
### Need Help?
For any issues, start with the **NVIDIA AI Workbench documentation** 

