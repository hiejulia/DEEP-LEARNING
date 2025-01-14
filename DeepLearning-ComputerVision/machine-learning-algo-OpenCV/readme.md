# Machine Learning with Computer Vision 
## Project 1 : Detecting Pedestrians in the Wild

- Dataset 
http://cbcl.mit.edu/software-datasets/PedestrianData.html
http://cbcl.mit.edu/projects/cbcl/software-datasets/pedestrians128x64.tar.gz.
http://cvcl.mit.edu/database.htm

- Feature engineer 
    - HOG feature
    - multi-scale detection opencv
    - 64 x 128 region of interest (ROI)
    - Annotated non pedestrian from Urban and Natural Scene dataset 

- SVM 
    - Tune model performance
    - bootstrapping
    - hyperparameter tuning: kernel 
- Detect pedestrian in a larger image
- Bayesian 
    - `cv2.ml.NormalBayesClassifier_create()`

## Project 2: Classifying emails using the naive Bayes classifier
- feature : n-grams, tf-idf



- Dataset 
The Ling-Spam corpus: http://csmining.org/index.php/ling-spam-datasets.html
The Hewlett-Packard spam database: https://archive.ics.uci.edu/ml/machine-learning-databases/spambase
The Enrom-Spam dataset: http://www.aueb.gr/users/ion/data/enron-spam
The Apache SpamAssassin public corpus: http://csmining.org/index.php/spam-assassin-datasets.html



# ML 

- KNN 
    `knn = cv2.ml.KNearest_create()`
- LinearR
- LogisticsR
    `cv2.ml.LogisticRegression_create()`
- Decision Tree 
    - Hyperparam tuning
# Feature engineer
- PCA + OpenCV 
- ICA 
- NMF
- Image feature 
    - Color space
    - SIFT 
    - SURF 
- SVM 
    - `svm = cv2.ml.SVM_create()`
    - mesh grid
    - kernel trick
    - cv2.ml.SVM_LINEAR, cv2.ml.SVM_POLY, cv2.ml.SVM_RBF, cv2.ml.SVM_SIGMOID, cv2.ml.SVM_INTER
    - Tuning kernel 

- K Means
    - `cv2.KMEANS_RANDOM_CENTERS`


- Dataset : https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+(Diagnostic)





# Ref 
- https://www.researchgate.net/publication/3703226_Pedestrian_detection_using_wavelet_templates. The paper was presented at the IEEE Computer Society Conference on Computer Vision and Pattern Recognition (CVPR) in 1997 by M. Oren, P. Sinha, and T. Poggio from MIT, doi: 10.1109/CVPR.1997.609319.