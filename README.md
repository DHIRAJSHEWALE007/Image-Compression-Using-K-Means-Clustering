# Image-Compression-Using-K-Means-Clustering

This repository contains a Python implementation of image compression using the K-Means clustering algorithm. The goal is to reduce the size of an image by clustering its pixels into a smaller number of colors, which helps in compressing the image while retaining its visual quality.

## Features
- **K-Means Clustering**: Utilizes the K-Means algorithm to group similar pixel colors.
- **Customizable Parameters**: Supports defining the number of clusters (`K`) and iterations for compression.
- **Visualization**: Includes side-by-side comparison of the original image and its compressed version.
- **Performance Optimization**: Efficiently handles image compression with support for high-resolution images.

## Requirements
The project uses Python and the following libraries:
- `numpy`
- `matplotlib`
- `scikit-learn`
- `imageio`

Ensure you have these libraries installed before running the code.

## How it Works
1. Load an image and flatten it into a 2D array of pixel colors.
2. Apply K-Means clustering to group pixels into `K` clusters (colors).
3. Replace each pixel with the centroid of its corresponding cluster.
4. Reconstruct the compressed image and save or display it.

## Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/image-compression-kmeans.git
   cd image-compression-kmeans
2. Install the required libraries:
   ```bash
   pip install -r requirements.txt
3. Run the notebook or script:
     - Launch Jupyter Notebook and open notebook.ipynb.
     - Follow the step-by-step instructions within the notebook to load your image, apply       K-Means clustering, and visualize the results.

## Example
For an input image of size 500x500 pixels with K=16, the output achieves significant compression while maintaining image quality.

## License
This project is licensed under the MIT License. See the LICENSE file for more details.
   
