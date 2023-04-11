# ECLU
# Efficient Image Clustering Using CNN and Clustering Algorithm

## Introduction
In this project, we explore different CNN architectures and clustering algorithms to develop an efficient method for image clustering. The goal is to create a clustering method that is both accurate and efficient, particularly when dealing with large datasets.

## Methodology
We evaluated the performance of different CNN architectures, including ConvNeXtXLarge and MobileNetV2, in combination with clustering algorithms such as KMeans, MiniBatchKMeans, and BIRCH. We trained and tested our models on the STL10 dataset.

## Results
Our experiments showed that ConvNeXtXLarge with BIRCH achieved the highest accuracy of 98.3%, making it the most accurate method. However, MobileNetV2 with MiniBatchKMeans was the fastest, and MiniBatchKMeans was the most efficient in terms of RAM consumption. We also found that size of the image did not significantly affect performance, but the number of images in the dataset did.

## Conclusion
Overall, our project demonstrated that combining CNN architectures with clustering algorithms can lead to efficient and accurate image clustering. Further exploration and optimization of these methods could have practical applications in image organization and retrieval.

## Usage
To use our implementation, clone the repository and run the code in the 'image_clustering.ipynb' Jupyter notebook. Make sure to have the necessary dependencies installed, including TensorFlow, scikit-learn, and matplotlib.
