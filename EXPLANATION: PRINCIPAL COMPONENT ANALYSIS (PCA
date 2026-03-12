============================================================
CODE EXPLANATION: PRINCIPAL COMPONENT ANALYSIS (PCA)
============================================================

1. DATA STANDARDIZATION:
PCA is sensitive to the scale of the data. The code first 
centers the data by subtracting the mean of each feature and 
dividing by the standard deviation. This ensures all features 
contribute equally to the analysis.

2. COVARIANCE MATRIX CALCULATION:
The code calculates the Covariance Matrix to understand how 
variables in the dataset vary from the mean with respect to 
each other. It identifies correlations between features.

3. EIGEN-DECOMPOSITION:
We compute the Eigenvalues and Eigenvectors of the covariance 
matrix. 
- Eigenvectors: Determine the directions of the new feature space.
- Eigenvalues: Determine the magnitude (amount of variance) 
  carried by each eigenvector.

4. SORTING AND SELECTION:
The eigenvalues are sorted in descending order. The top 'k' 
eigenvectors (where k is the desired number of dimensions) 
are chosen to form a "Feature Vector."

5. PROJECTING THE DATA:
Finally, we take the original standardized data and multiply 
it by the Feature Vector (matrix transformation). This 
reorients the data from the original axes to the axes 
represented by the Principal Components.

6. VISUALIZATION:
The code typically ends with a plot (usually a 2D or 3D 
scatter plot) showing the transformed data, making it 
easier to visualize clusters or patterns that were hidden 
in high-dimensional space.
============================================================
