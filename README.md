# matrix-properties-calculator
A Python tool to read numeric matrices from CSV files and compute their rank, determinant, inverse, and eigenvalues/eigenvectors. Supports both square and non-square matrices. Ideal for learning linear algebra and matrix operations programmatically.
# Matrix Analyzer

A simple Python project to analyze numeric matrices. The program reads data from a CSV file, converts it to a matrix, and computes key properties including:

- Rank
- Determinant (if square)
- Inverse (if square and non-singular)
- Eigenvalues and Eigenvectors (if square)

## Features

1. Supports CSV input for numeric data.
2. Handles non-square matrices gracefully.
3. Prints the matrix and computed properties in a readable format.
4. Modular design with functions for each calculation.

## Usage

1. Place your matrix data in a CSV file (numbers only, comma-separated).
2. Update the `data = pd.read_csv("data.csv")` line with your file name.
3. Run the script in Python 3.x or Google Colab.

```bash
python matrix_analyzer.py
