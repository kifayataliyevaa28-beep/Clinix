# Clinix

A Python demonstration of clinical genomics visualization workflows, covering mutation frequency, differential expression, and multi-omics integration views.

> **Note:** This notebook uses **simulated data** to demonstrate visualization workflows. It does not contain real patient data, and the plots do not represent real clinical findings.

## What it does

- **Mutation frequency plot:** bar chart of commonly mutated cancer genes (TP53, PIK3CA, BRCA1, PTEN, EGFR, KRAS, IDH1) using illustrative counts
- **RNA-seq volcano plot:** log2 fold change vs. statistical significance (-log10 p-value), with thresholds for up- and down-regulated genes, using randomly generated values
- **Multi-omics integration view:** box and swarm plot comparing expression levels between wild-type and mutated groups (simulated)

## Requirements

- Python 3.8+
- pandas, numpy, matplotlib, seaborn

pip install pandas numpy matplotlib seaborn

## Usage

Open `clinix.ipynb` in Jupyter Notebook, JupyterLab, or VS Code and run the cell.

## Purpose

Built as a learning and prototyping exercise for clinical genomics data visualization. Real datasets (e.g., TCGA, ClinVar) can replace the simulated inputs in future versions.

## Author

Kifayat Aliyeva  
MBA (AI & Business) student, UNEC. Interested in bioinformatics and data analytics.  
[LinkedIn](https://www.linkedin.com/in/kifayat-aliyeva)
