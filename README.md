# Erythemato Squamous Disease Detection using ensemble methods

## Dataset

(The data was gotten from UCI)[https://archive.ics.uci.edu/ml/datasets/dermatology]

## Proposed Methodology

- SVM with different kernels such as RBF, Polynomial, Sigmoid and Linear

- 4 filter FS methods such as info. gain, gain ratio, reliefF and Chi square

- 1 embedded FS method such as RFE-SVM(RBF)

- Base Classifiers: SVM[with different kernel functions]

- Ensemble methods: Stacking[with Logistic Regression as Meta Model], Bagging and Boosting

