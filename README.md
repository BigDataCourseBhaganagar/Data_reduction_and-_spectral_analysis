# Data reduction and spectral analysis of turbulent field images
Final Project for Big Data Class - 
This code uses large jet image data set and reduces the information using a spectral filter for analysis.

This project has a two-fold approach. 
1. Handling huge image data sets and reducing matrix sizes for analysis
The first involves handling huge data sets. The data set used for this project can be downloaded from the following link (https://drive.google.com/drive/folders/1nu2r1wRfx2k63iDBfLGYdC_K0D3ZFQkS?usp=sharing) The two data sets are called Test1 and Test 2a. These data sets are made up of images of a jet flow at two different pressures. The first goal of the project is to come up with a unique way to handle large image data sets for use and analysis.

2. Spectral comparison and correlation of two separate turbulent fields.
The second goal of this project is to perform a frequency analysis on the data sets and unearth interesting similarities and trends in the turbulent field data set.

The code uploaded to this repository has several capabilities. These include reading in large data image datasets, obtaining the fluctuating properties of the datasets, perform a frequency transposition of the dataset, filter the data set based on selected frequencies, and store the data sparse arrays that reduce the memory usage of the code. Once this is performed, several frequency related analysis and correlations are performed to analyze the data.

Hypothesis - 
1. Frequency filtration of data can reduce memory usage of code the code by an order of magnitude.- This has been proven and results shown in the presentation.
2. Jets of varying pressure (ie varying Reynolds number) share some fundamental spectral content and hence can be correlated.
3. The spectral content in a turbulent Jet varies by pressure with an increase in high frequency spectral content with increased pressure.

Pandas - Pandas will be used a minimal amount due to it not being suited to handle large arrays of data. To optimize the code, the use of pandas has been restricted.

This repository will include the following.
1. Read me file 
2. Project proposal file
3. Project presentation file
4. Code
5. Link to data (https://drive.google.com/drive/folders/1nu2r1wRfx2k63iDBfLGYdC_K0D3ZFQkS?usp=sharing)
