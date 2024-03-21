The study investigates what the best dimension reduction technique is for building a prosate tumor prognosis model. 
It assesses linear, kernel, sparse and robust principal component analyis as well as principle curves and clustering, 
using classification algorithms SVM-RBF Kernel, Logistic Regression and Naive Bayes. It was found that solely using 
the first principal component from linear PCA would result in the best performance metrics (the study assessed accuracy,
sensitivity and specificity).

| Feature          | Description                                                  | Type      |
|------------------|--------------------------------------------------------------|-----------|
| Radius (Mean)    | Mean of distances from the center to points on the perimeter | Continuous|
| Texture (Std Dev)| Standard deviation of grayscale values                       | Continuous|
| Perimeter        | Perimeter of the cell nucleus                                | Continuous|
| Area             | Area of the cell nucleus                                     | Continuous|
| Smoothness       | Local variation in radius lengths                            | Continuous|
| Compactness      | Measure of shape compactness ((perimeter^2 / area) - 1)      | Continuous|
| Concavity        | Severity of concave portions of the contour                  | Continuous|
| Symmetry         | Symmetry of the cell nucleus                                  | Continuous|
| Fractal Dimension| Measure of the "coastline approximation" (coastline - 1)     | Continuous|
"# STA5069Z-Final-" 
"# STA5069Z-Final-" 
