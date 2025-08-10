# CRC-Biomarker-extract-by-NLP
# Biomedical NER Extraction Project

This repository contains the source code and documentation for extracting  biomarkers from biomedical PDF articles using NLP models.

## Overview

The project uses two main NLP tools:
- SciSpacy: A specialized model for biomedical named entity recognition.
- d4data/biomedical-ner-all: A HuggingFace transformer model for biomedical NER.

The code processes PDF files, extracts relevant text sections, and identifies biomarkers. Results are saved in Excel and CSV formats.

## Important Note

⚠️ This code is provided for demonstration and verification purposes only.  
It contains a built-in safeguard to prevent execution (raise Exception(...)).  
This ensures the intellectual property and model details are protected.

If you need to run the code, please contact the author for access to the full executable version or the API service.

## Usage

1. The main processing script is main.ipynb or main.py.  
2. Input PDF files should be placed in the designated folder (e.g., D:/P1).  
3. Running the script extracts biomarker entities and saves output files.

## Structure

- main.ipynb / main.py: Core extraction code with execution guard.  
- Extracted_Biomarkers.xlsx and Extracted_Biomarkers.csv: Sample output files.  
- README.md: This documentation.

## Contact

Thank you for reviewing this project!
