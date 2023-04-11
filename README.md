# ECLU
# Efficient Image Clustering Using CNN and Clustering Algorithm

## Introduction
In this project, we explore different CNN architectures and clustering algorithms to develop an efficient method for image clustering. The goal is to create a clustering method that is both accurate and efficient, particularly when dealing with large datasets.

## Methodology
We evaluated the performance of different CNN architectures, including ConvNeXtXLarge and MobileNetV2, in combination with clustering algorithms such as KMeans, MiniBatchKMeans, and BIRCH. We trained and tested our models on the STL10 dataset.

## Results
Our experiments showed that ConvNeXtXLarge with BIRCH achieved the highest accuracy of 98.3%, making it the most accurate method. However, MobileNetV2 with MiniBatchKMeans was the fastest, and MiniBatchKMeans was the most efficient in terms of RAM consumption. We also found that size of the image did not significantly affect performance, but the number of images in the dataset did.

| Model          | Accuracy |
|----------------|----------|
| M.NetV3+KM     | 70.23    |
| E.NetV2s+KM    | 94.12    |
| Resnet50+KM    | 86.21    |
| VGG+KM         | 76.6     |
| **Co.tXL+KM**      | **98.3** |
| M.NetV3+AC     | 68.43    |
| Co.tXL+AC      | 97.32    |
| E.NetV2s+AC    | 90.1     |
| Resnet50+AC    | 85.21    |
| VGG+AC         | 74.1     |
| M.NetV3+BH     | 70.1     |
| VGG+BIRCH      | 76.45    |
| Resnet50+BH    | 86.13    |
| E.NetV2s+BH    | 93.94    |
| Co.tXL+BH      | 98.23    |
| M.NetV3+MKM    | 64.23    |
| VGG+MKM        | 70.8     |
| Resnet50+MKM   | 76.32    |
| E.NetV2s+MKM   | 85.2     |
| Co.tXL+MKM     | 87.21    |


In addition to these results, the project was also successful in clustering 31,000 images from the Tibet museum dataset using the ConvNeXtXLarge CNN architecture with the BIRCH clustering algorithm. 
**This model achieved an accuracy of  98.3%% on the STL10 dataset, which beats the state-of-the-art model described in the paper with code for the STL10 dataset.**
https://paperswithcode.com/sota/image-clustering-on-stl-10

## Conclusion
Overall, our project demonstrated that combining CNN architectures with clustering algorithms can lead to efficient and accurate image clustering. Further exploration and optimization of these methods could have practical applications in image recommendation based on image feature and image dataset cleaning 

## Usage
To use our implementation, clone the repository and run the code in the 'ECLU.ipynb' Jupyter notebook. Make sure to have the necessary dependencies installed, including TensorFlow, scikit-learn, and matplotlib.

