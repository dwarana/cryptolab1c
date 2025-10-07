This is the group assignment suplementary code

A00046725@myTUDublin.ie – Warana Dissanayaka 
A00047293@myTUDublin.ie – Amal Santhosh

---

## Table of Contents

1. [Overview](#overview)  
2. [Repository Structure](#repository-structure)  
3. [Usage](#usage)  
4. [Dependencies](#dependencies)  
5. [How to Run](#how-to-run)  
6. [Test Data / Results](#test-data--results)

---

## Overview

The **CryptoLab1C** repository contains Python scripts and output data developed for a cryptography lab assignment.  
It demonstrates practical cryptanalysis techniques such as **crib dragging** and **ciphertext comparison** to study weaknesses in reused encryption keys (the Many-Time Pad problem).

The project includes:
- Python scripts for data processing and analysis.
- CSV files storing results from crib tests using different phrases.

---

## Repository Structure
cryptolab1c/
├── realtim.py
├── seperfile.py
├── crib_test_results_Building.csv
├── crib_test_results_We_are.csv
├── crib_test_results_the.csv
└── README.md


| File | Description |
|------|-------------|
| `realtim.py` | Main script for running or analyzing crib-dragging data |
| `seperfile.py` | Helper script for splitting or organizing CSV result files |
| `crib_test_results_*.csv` | Generated results for specific crib phrases |
| `README.md` | Documentation file |

---

## Usage

1. Make sure all the `.csv` files are in the same directory as the scripts.  
2. Run the scripts using Python 3:  

```bash
python3 realtim.py
python3 seperfile.py

Review the generated or existing CSV files to examine crib test outcomes and analysis.

Dependencies

You need Python 3.x and possibly a few libraries (depending on imports inside the scripts).

Common dependencies might include:

pip install pandas numpy

How to Run

Example setup:

# Clone the repository
git clone https://github.com/dwarana/cryptolab1c.git
cd cryptolab1c

# (Optional) Create and activate a virtual environment
python3 -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# Install dependencies

# Run the main analysis scripts
python3 realtim.py
python3 seperfile.py

Test Data / Results

The repository includes sample result files:

crib_test_results_Building.csv

crib_test_results_We_are.csv

crib_test_results_the.csv

Each file contains data from separate crib tests (phrases like “Building”, “We are”, “the”) used to identify possible plaintext overlaps or key recovery in reused cipher contexts.
