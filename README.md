# Electrochemical Sequencing Scripts

This repository contains scripts for encoding and decoding sequences via electrochemical methods. These scripts are implemented in Jupyter notebooks and are designed for use in a chemistry research setting.

## Table of Contents
- [Overview](#overview)
- [Files in This Repository](#files-in-this-repository)
- [Prerequisites and Setup](#prerequisites-and-setup)
- [Instructions for Use](#instructions-for-use)

## Overview
The **Encoding Script** and **Decoding Script** provided in this repository are used for encoding information into sequences based on the provided oligomer library and assigned ASCII characters to these oligomers, and decoding it back to retrieve the original data using DPV raw data after oligomer degradation. This system leverages specific data patterns for sequence matching and recognition.

## Files in This Repository
1. **Encoding Script.ipynb**: This script is used to encode sequences by assigning specific electrochemical signatures to unique identifiers.
2. **Decoding Script.ipynb**: This script decodes the sequences by analyzing electrochemical signatures and extracting the original encoded data.
3. **Folders for Raw and Processed data**: This repo contains all the necessary folders and subfolders as well as necessary excel files to run the sequencing script successfully. It is recommended that you follow this folder structure and naming convention for raw oligomer data for successful execution of the script as is. If you want to change the data structure and/or file types, please update the script accordingly. 

## Prerequisites and Setup
To set up the environment for running these scripts, please install the required libraries. 

### Libraries Required
The following Python libraries are needed:
- `numpy`
- `pandas`
- `matplotlib`
- `scipy`
- `sklearn`

### Installation
If you have Python installed, you can install the required libraries with the following commands:

```bash
pip install numpy pandas matplotlib scipy scikit-learn
```

Alternatively, you can create a virtual environment and install the libraries within that environment:

```bash
# Create a virtual environment
python -m venv env

# Activate the virtual environment
# On Windows
env\Scripts\activate
# On macOS/Linux
source env/bin/activate

# Install the required libraries
pip install numpy pandas matplotlib scipy scikit-learn
```

## Instructions for Use

1. **Encoding Sequence Data**
   - Open the **Encoding Script.ipynb** notebook.
   - Follow the instructions in the notebook to input your data and generate encoded sequences.
   - Run all cells in the notebook to execute the encoding steps.

2. **Decoding Sequence Data**
   - Open the **Decoding Script.ipynb** notebook.
   - Use the raw DPV data for oligomer (12 data sets after degradation per oligomers) as input for the decoding process.
   - Run all cells in the notebook to decode and retrieve the original sequence data.

---

This README provides essential details for running the encoding and decoding scripts for electrochemical sequencing. Feel free to make necessary changes for your needs. 
