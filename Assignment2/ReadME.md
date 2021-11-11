
# Demonstration of Dimensionality Reduction Techniques

## Image dataset 

### Digit Recognizer Image dataset from Kaggle

The dataset contains gray-scale images of hand-drawn digits from zero through nine.

Each image is 28 pixels in both width and height and has a total of 784 pixels. Pixel value ranges fromm 0-255, (higher the value , darker the pixel).

The dataset has 785 columns. 1st column is the label and the rest are the pixel values of the digit drawn by the user.
### PCA

![newplot](https://user-images.githubusercontent.com/2658837/141237648-a8dc6ce9-8b75-4113-a682-6632e1c2f3ae.png)

### SVD

![newplot (1)](https://user-images.githubusercontent.com/2658837/141237751-e0d8357e-ab79-49f6-b7fc-1517566f9350.png)

### LLE

![newplot (2)](https://user-images.githubusercontent.com/2658837/141237765-f432bdad-0ed9-450f-82d0-c52dbd09a899.png)

### T-SNE

![newplot (3)](https://user-images.githubusercontent.com/2658837/141237780-925ab8f2-ca30-4b38-815e-543c485a759b.png)

### ISOMAP

![newplot (4)](https://user-images.githubusercontent.com/2658837/141237863-854ab71e-9354-4315-93c2-51507f50b7c0.png)

### UMAP
![newplot (5)](https://user-images.githubusercontent.com/2658837/141237914-519d676d-9977-46a7-99a5-91418cbc11c8.png)

### Conclusion 

Out of all the techniques, UMAP depicts the clusters properly and is very clearly binding its data points, and can compute faster than other techniques.

## Tabular dataset

### Breast Cancer Detection

Attributes : ID number and Diagnosis

Features:
- radius (mean of distances from center to points on the perimeter)
- texture (standard deviation of gray-scale values)
- perimeter
- area
- smoothness (local variation in radius lengths)
- compactness (perimeter^2 / area - 1.0)
- concavity (severity of concave portions of the contour)
- concave points (number of concave portions of the contour)
- symmetry
- fractal dimension ("coastline approximation" - 1)

![image](https://user-images.githubusercontent.com/2658837/141238574-1646f97d-d2fd-4be2-acaf-371dd8fb8b37.png)

### Conclusion

UMAP, with highest accuracy of 0.96 , provides better vizualisation than other techniques by removing the outliers and binding the data points in proper clusters.



