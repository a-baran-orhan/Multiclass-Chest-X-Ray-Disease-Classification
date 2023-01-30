# Multiclass Chest X-Ray Disease Classification
Implemented a nearest neighbor algorithm to detect diseases from chest X-Ray images of people using edge filters Canny, Gabor

Dataset include Chest X-Ray images for Covid, Pneumonia and Healthy (normal)
patients.

CLASSIFICATION REPORT FOR 64x64

              precision    recall  f1-score   support

           0       0.99      0.87      0.93       100
           1       0.78      0.73      0.75       100
           2       0.75      0.88      0.81       100

    accuracy                           0.83       300
   macro avg       0.84      0.83      0.83       300
weighted avg       0.84      0.83      0.83       300

-------------------------------
CLASSIFICATION REPORT FOR 32x32

              precision    recall  f1-score   support

           0       0.96      0.88      0.92       100
           1       0.74      0.75      0.75       100
           2       0.77      0.82      0.79       100

    accuracy                           0.82       300
   macro avg       0.82      0.82      0.82       300
weighted avg       0.82      0.82      0.82       300

-------------------------------
CLASSIFICATION REPORT FOR 64x64 + CANNY

              precision    recall  f1-score   support

           0       0.91      0.49      0.64       100
           1       0.54      0.54      0.54       100
           2       0.58      0.84      0.68       100

    accuracy                           0.62       300
   macro avg       0.67      0.62      0.62       300
weighted avg       0.67      0.62      0.62       300

-------------------------------
CLASSIFICATION REPORT FOR 32x32 + CANNY

              precision    recall  f1-score   support

           0       0.72      0.49      0.58       100
           1       0.45      0.45      0.45       100
           2       0.45      0.60      0.52       100

    accuracy                           0.51       300
   macro avg       0.54      0.51      0.52       300
weighted avg       0.54      0.51      0.52       300

-------------------------------
