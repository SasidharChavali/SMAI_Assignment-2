### The tasks covered in this assignment are PCA, GMM, Hierarchical Clustering, and Image Orientation. Each task is described below.

## PCA (Principal Component Analysis)

- **Task:** Perform dimensionality reduction using PCA.
- **Description:** In the PCA task, we reduce the dimensions of a dataset and visualize the cumulative explained variance with respect to the number of principal components. We use PCA to transform the data into a lower-dimensional space and analyze the variance explained by each principal component.
- **Implementation:** Code for performing PCA and plotting the cumulative explained variance is provided. See the `pca.py` file for the PCA implementation.
- **Usage:** Run `pca.py` to perform PCA and visualize the results.

## GMM (Gaussian Mixture Model)

- **Task:** Apply Gaussian Mixture Model to dataset.
- **Description:** In the GMM task, we fit a Gaussian Mixture Model to a dataset to identify the likely Gaussian components that generate the data. The entire implementation of GMM is done from scratch
- **Implementation:** Code for fitting a GMM to a dataset and visualizing the results is provided. See the `Gmm.ipynb` file for the GMM implementation.

## Hierarchical Clustering

- **Task:** Perform hierarchical clustering on a dataset.
- **Description:** In the hierarchical clustering task, we cluster data points using a hierarchical clustering algorithm. We use dendrograms to visualize the hierarchical structure of the clusters.
- **Implementation:** Code for performing hierarchical clustering and plotting dendrograms is provided. See the `1.ipynb` file for the implementation.

## Image Orientation

- **Task:** Orient images based on templates.
- **Description:** In the image orientation task, we orient images based on template angles. The orientation is computed by finding the direction of the template and aligning images accordingly.
- **Implementation:** Code for orienting images using template angles is provided. See the `4.1.ipynb` file for the implementation.

For each task, specific code and data are provided in this repository. You can run the scripts for each task individually to perform the analysis.

## Requirements

- Python 3.6+
- Required Python libraries (NumPy, SciPy, Matplotlib, OpenCV, Scikit-Learn)
