# PCA Image Compression and Reconstruction
This repository demonstrates Principal Component Analysis (PCA) applied to image data for dimensionality reduction, compression, and reconstruction. The code performs PCA separately on the Red, Green, and Blue (RGB) channels of an image to reduce data dimensionality while preserving most of the visual information.

# Overview

   * Resize an input image to 256x256 pixels.

    Extract and visualize each RGB channel.

    Compute PCA for each channel independently:

       Calculate covariance matrices.

       Extract eigenvalues and eigenvectors.

    Project data onto principal components.

    Reconstruct each color channel from a reduced number of principal components.

    Combine reconstructed channels into a compressed RGB image.

    Evaluate reconstruction quality using mean squared error loss.

    Visualize original, reconstructed images, and reconstruction loss curve.

This approach enables significant compression by selecting top principal components that capture most of the variance, achieving an efficient representation of the original image.

# Features
             
    Image upload support for flexible input.

    Visualization of original and reconstructed images by color channel.

    Dynamic selection of number of principal components for reconstruction.

    Reconstruction loss analysis indicating trade-off between compression and image quality.

    Intuitive plotting of PCA results for each channel.

# How to Use
     
    Run the script in a Python environment (Google Colab recommended).

    Upload the target image when prompted.

    Observe channel-wise PCA projections and reconstructed outputs.

    Analyze reconstruction loss vs number of principal components.

    Optionally upload additional images to view outputs.

# Requirements

    Python 3.x

    NumPy

    Matplotlib

    Pillow (PIL)

    Google Colab (for the upload functionality)

# File Structure

pca.py: Main script implementing PCA-based image analysis.

README.md: This document.


# PCA_-Principle_Compenent_Analysis-
Principal Component Analysis (PCA) is a widely used dimensionality reduction technique in data analysis and machine learning. It transforms a high-dimensional dataset into a smaller set of new, uncorrelated variables called principal components, which capture most of the original data's variance and important information.  
