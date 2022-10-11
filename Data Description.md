# Dataset Description

The Breast Cancer Wisconsin (Diagnostic) DataSet, obtained from Kaggle, contains features computed from a digitized image of a fine needle aspirate (FNA) of a breast mass and describe characteristics of the cell nuclei present in the image.

* Number of instances: 569

* Number of attributes: 32 (ID, diagnosis, 30 real-valued input features)

* Attribute information

  * ID number
  
  * Diagnosis (M = malignant, B = benign)
  
  * Ten real-valued features are computed for each cell nucleus:
  
    radius (mean of distances from center to points on the perimeter)
    texture (standard deviation of gray-scale values)
    perimeter
    area
    smoothness (local variation in radius lengths)
    compactness (perimeter^2 / area - 1.0)
    concavity (severity of concave portions of the contour)
    concave points (number of concave portions of the contour)
    symmetry
    fractal dimension ("coastline approximation" - 1)
    The mean, standard error, and "worst" or largest (mean of the three largest values) of these features were computed for each image, resulting in 30 features. For instance, field 3 is Mean Radius, field 13 is Radius SE, field 23 is Worst Radius.
