# BBH Penning Trap Simulation Code (Nature Submission)

This repository contains the full code used in our Nature submission. It includes three Jupyter notebooks that reproduce the figures, simulations, and a sample dataset:

- Nature_BBH_Penning_Code_Simulation_Demonstration.ipynb  
  Main demonstration notebook showing how to set up and run the BBH Penning trap simulation, including example trajectories and parameter sweeps.

- Nature_BBH_Merger_Plots.ipynb  
  Produces the merger-related figures used in the manuscript (results section), reproducible end-to-end.

- Nature_Sample_Simulation_Data_Set_Plotting.ipynb  
  A small, fast-to-run sample dataset with plotting routines; use this to verify the environment is working.

---

## System requirements

- Python versions tested: 3.9.7, 3.10.5, 3.11.13
- Operating system tested: macOS 15.5 (24F74)
- Hardware tested: Apple M1 chip
- Non-standard hardware: none required
- Memory: runs comfortably on normal desktops/laptops; no extraordinary RAM required
- Dependencies: listed in environment.yml (conda) and requirements.txt (pip)

---

## Installation guide

### Option 1 — Conda (recommended)

    conda env create -f environment.yml
    conda activate bbh-penning
    jupyter lab

### Option 2 — pip

    python -m venv .venv
    source .venv/bin/activate    # Windows: .venv\Scripts\activate
    pip install -r requirements.txt
    jupyter lab

Typical install time on a normal desktop computer: 2–3 minutes.

---

## Demo

To quickly verify the setup, open Jupyter Lab and run the sample dataset notebook:

    jupyter lab

Then open:

    Nature_Sample_Simulation_Data_Set_Plotting.ipynb

Expected output: plots of the sample dataset with trajectories  
Expected runtime: < 1 minute on a normal desktop

---

## Instructions for use

### Run the main simulation:  
Open `Nature_BBH_Penning_Code_Simulation_Demonstration.ipynb` in Jupyter Lab. Adjust the parameter cells at the top to explore different configurations. This notebook includes the entire stand alone code to run simulations with different parameters and plot the results with demonstrations.

### Reproduce manuscript figures:  
Run `Nature_BBH_Merger_Plots.ipynb`. Output figures are written to the working directory.

### Verify installation and dependencies:  
Run `Nature_Sample_Simulation_Data_Set_Plotting.ipynb`. The full data set is available at https://drive.google.com/file/d/1r1oxAGBFeMseN_Fsc2dWuNcp-Iiw9khP/view?usp=sharing.

### Optional reproduction instructions:  
Running all three notebooks sequentially reproduces all quantitative results shown in the manuscript.

---

## License

This project is released under the MIT License (see LICENSE)

---

## Repository

Public repository link: [add GitHub URL here after upload]

