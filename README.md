Using Python for numerical methods in materials science.

★Project Overview

This repository contains three fundamental practice projects using Python for materials science applications. 
It covers core techniques ranging from numerical fitting and signal processing to image digitalization.

★Development Environment

- Programming Language: Python 3.14
  
- Core Libraries:
  - `numpy`: Numerical computing and matrix manipulation.
    
  - `pandas`: Data structures and tabular analysis.
    
  - `matplotlib`: Data visualization and plotting.
    
  - `scipy`: Scientific computing and signal processing (primarily for peak detection).

★Project Descriptions

01. Stress-Strain Data Analysis
   
    Goal: Calculate material elastic properties from tensile test data.
  
    - Key Features:
      - Process raw stress and strain data using Pandas DataFrames.
    
      - Filter and isolate the linear-elastic region.
      
      - Perform linear regression using`numpy.polyfit`to automatically calculate Young's Modulus ($E$).
      
02. XRD Peak Analysis
   
    Goal: Automate the detection of peaks in X-ray diffraction patterns and analyze crystalline features.
  
    - Key Features:
      - Identify peak positions and intensities using`scipy.signal`.
    
      - Calculate the Full Width at Half Maximum (FWHM), essential for grain size analysis.
    
      - Generate plots with automated annotations for peak locations and FWHM horizontal lines.
     
    ![XRD Peak Detection and FWHM Analysis](Materials-Numerical-Methods/XRD Peak Detection and FWHM Analysis.png)

    Peak 1: Position = 38.47°, FWHM = 1.0054°
    
    Peak 2: Position = 44.71°, FWHM = 1.4598°

03. Porosity and Feature Size Analysis
   
    Goal: Digitalize microscopy images using image processing techniques.
    
    - Key Features:
      - Convert image data into NumPy matrices.
      
      - Apply binarization (thresholding) to distinguish between the material matrix and pores.
      
      - Calculate the Porosity Percentage (%) automatically.
      
      - Implement edge detection logic using pixel shifting to highlight feature contours.

   ![Porosity and feature size analysis](Materials-Numerical-Methods/Porosity and feature size analysis.png)  

  Analysis Report:
   
  Total Area: 10000 pixels
  
  Pore Area: 1032 pixels
  
  Porosity: 10.32%
    
      

    
