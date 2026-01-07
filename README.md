# immune-geometry-RC3-data

RC3 Data Release: Technical Hardening, Epsilon Audit, and Observable Redesign for Geometric Constraints and Vulnerability in Immune State Geometry

## Overview

This repository contains the RC3 (Release Candidate 3) data release for the analysis of single-cell ATAC-seq immune state geometry using information geometry and topological data analysis. The data represents a comprehensive study of immune system constraints and critical transitions.

## Release Information

- **Release**: RC3
- **Date**: 2026-01-06
- **State**: IN PROGRESS
- **License**: CC0-1.0 (Public Domain)

## Components

### RC3-A: Epsilon Audit
- **Stability Sweep**: Testing with KSG k values: 5, 10, 20
- **Histogram Binning**: Tested with bins 20 and 40
- **Internal Scale**: Positive and negative controls

### RC3-B: Observable Redesign
- **Program-level MI**: PCALSI vs Totals comparison
- **Governor**: Strict audit constraints

## Data Contents

### `/data/` Directory
- **RC3A_EstimatorStress.tsv**: Stress testing results for different estimators
- **SourceData_Fig4.tsv**: Source data for Figure 4 vulnerability analysis
- **Additional TSV files**: Supporting analysis data

## Configuration Files

- **frozen_config.yaml**: Complete analytical configuration with:
  - Observable definitions (Information-theoretic measurements)
  - MI estimator parameters (KNN with k=10, histogram with 40 bins)
  - TDA parameters (bandwidth selection, grid resolution)
  - Computational resources (4 workers, 35GB memory limit)

## Analysis Methods

- **Information Geometry**: Dimensionality reduction via Information Bottleneck
- **Topological Data Analysis**: Persistence homology with Wasserstein metrics
- **Stability Analysis**: Multiple null model comparisons (nullA, nullB, nullC)
- **Critical Dynamics**: Assessment of immune state geometry constraints

## Data Preservation

- **Null Models**: A and C preserved from RC2 in read-only format
- **Artifacts**: RC2 artifacts preserved for reproducibility tracking
- **Audit Log**: Complete mapping of figures to generating scripts

## Citation

If you use this data, please cite:
```
10.5281/zenodo.18136162
```

## Reproducibility

Full reproducibility documentation available in REPRODUCIBILITY.md

## Author

Elkin Navarro Quiroz
Centro de Investigaciones en Ciencias de la Vida
Universidad Simón Bolívar
