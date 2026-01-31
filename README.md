# Data Analysis of HPGe Detector Using CERN ROOT

This project focuses on performing detailed spectral analysis of gamma-ray data obtained from a High-Purity Germanium (HPGe) detector using the CERN ROOT data analysis framework. The objective is to convert raw detector output into physical parameters through calibration, peak fitting, resolution measurement, and visualization.

## 📌 Project Overview

High-Purity Germanium (HPGe) detectors are widely used in nuclear and particle physics due to their excellent energy resolution. However, raw detector data (LLD/channel vs counts) requires proper analysis to extract meaningful physical information.

In this project, CERN ROOT is used to:
- Perform energy calibration
- Fit gamma-ray peaks using Gaussian functions
- Estimate detector energy resolution
- Visualize spectra with error bars
- Analyze statistical uncertainties

## 🛠 Tools & Technologies

- CERN ROOT Framework (C++)
- HPGe Detector Gamma-Ray Data
- Gaussian Curve Fitting
- ROOT Macros
- TGraphErrors, TF1, TCanvas
- Linux Environment

## 📊 Key Features

- Energy calibration using standard radioactive sources  
- Gaussian peak fitting with background subtraction  
- Calculation of peak parameters (mean, sigma, FWHM)  
- Energy resolution estimation  
- Error analysis using Poisson statistics  
- Publication-style plots with legends and grids   

## 🔬 Methodology

1. Import gamma-ray data from text files into ROOT.
2. Create histograms and graphs with error bars.
3. Apply Gaussian fitting to identify spectral peaks.
4. Perform linear energy calibration to map LLD/channel to energy (keV).
5. Extract peak parameters and calculate detector resolution.
6. Visualize results using ROOT canvases.

## 📈 Results

- Successfully calibrated detector energy scale.
- Identified gamma-ray peaks for different radioactive sources.
- Measured peak widths and calculated energy resolution.
- Generated fitted spectra and calibration plots.

## 🎯 Learning Outcomes

- Practical experience with CERN ROOT framework  
- Understanding of HPGe detector working and calibration  
- Hands-on exposure to curve fitting and statistical analysis  
- Improved skills in scientific data visualization  
- Experience in experimental physics data processing  

## 📷 Sample Outputs

(See included images in the repository)

## 📜 Author

Riya Kumari Karn  
M.Sc Physics  
Central University of South Bihar

---

Feel free to explore the repository and reach out for any questions or improvements.
