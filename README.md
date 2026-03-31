# xrd-scherrer-analysis

This repository contains the custom Python code used for XRD peak fitting and Scherrer crystallite size analysis of iron oxide nanoflowers (IONFs).

Both Gaussian fitting and pseudo-Voigt fitting were applied for comparison in the analysis of the undoped IONF series.

## Contents

- `xrd_scherrer_analysis.ipynb`  
  Python notebook for Gaussian fitting of XRD peaks and Scherrer size calculation.

- `xrd_pseudovoigt_analysis.ipynb`  
  Python notebook for pseudo-Voigt fitting of XRD peaks and Scherrer size calculation.

- PDF files  
  Exported PDF versions of the analysis notebooks for viewing and reference.

## Main functions

The code includes:

- loading and cleaning XRD data
- linear baseline correction
- plotting XRD patterns
- Gaussian peak fitting
- pseudo-Voigt peak fitting
- numerical FWHM calculation
- Scherrer crystallite size calculation

## Notes

These scripts were developed for project data analysis in this work. The code is mainly intended for comparison of peak width and estimated crystallite size across different feed conditions and doped systems.

## Author

Xiaoyu Xiang
