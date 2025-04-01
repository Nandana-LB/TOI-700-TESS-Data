# TOI-700-TESS-Data
# TOI 700.ipynb

## Overview

This Jupyter Notebook contains an analysis of the TOI 700 exoplanetary system using data from NASA's Transiting Exoplanet Survey Satellite (TESS). The notebook primarily focuses on working with light curve data to identify planetary transits and analyze the planetary system's properties.

### Data

The data in this repository includes:
- **Target Pixel Files (TPF):** Raw TESS image data for TOI 700 from various sectors.
- **Light Curves (LC):** Extracted and cleaned light curve data used for transit analysis.

### Notebooks

The Jupyter notebooks in this repository provide the following:
1. **Data Download:** Code to fetch and inspect TESS data for TOI 700.
2. **Light Curve Analysis:** Tools to clean and visualize the light curve, and plot potential exoplanet transits.
3. **Transit Detection:** Methods to identify and analyze the transits of exoplanets around TOI 700.

### **Creating a TESSLightCurve from a TESSTargetPixelFile**

In this notebook, we will demonstrate how to create a **TESSLightCurve** from a **TESSTargetPixelFile** (TPF) using the **Lightkurve** package. Here's the general workflow for this task:

1. **Download the Target Pixel File (TPF)**:  
   First, we download the raw TESS data (TPF) for TOI 700 from a specific sector. This data contains the light curves for all stars observed in that sector.

2. **Convert TPF to Light Curve**:  
   We will convert the raw pixel data into a light curve. This involves:
   - Selecting the star of interest from the TPF.
   - Extracting the flux values over time.
   
3. **Plotting the Light Curve**:  
   We will plot the extracted light curve, showing the star's brightness variations over time.

## References

1. **NASA TESS Mission**  
   The official TESS mission page provides comprehensive information about the mission, its goals, and data products.  
   [NASA TESS Mission](https://tess.mit.edu)

2. **Lightkurve Python Package**  
   Lightkurve is a Python package designed to analyze and visualize time-series data from TESS and other missions.  
   [Lightkurve Documentation](https://docs.lightkurve.org)


