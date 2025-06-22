# Neural-Computing
Version of libraries:

numpy==1.26.4

pandas==2.2.2

sklearn==1.5.1

skorch==1.1.0

matplotlib==3.9.2

torch==2.6.0

joblib==1.4.2

Setup Instructions:
To run the best models and generate at least two of the graphs that were mentioned, do the following:
1. Create a virtual environment with the above libraries and their respective versions.

Support Vector Machine Model:
1. Upload 'BEST_SVM_pkl', 'TEST_SET_SVM.csv', 'SVM_TEST_EVAL.ipynb' in the created virtual environment.
2. Select the 'SVM_TEST_EVAL' file in the environment.
3. Run the whole code.

Multilayer Perceptron Model:
1. Upload 'BEST_MLP_pkl', 'TEST_MLP_SVM.csv', 'MLP_TEST_EVAL.ipynb' in the created  virtual environment.
2. Select the 'MLP_TEST_EVAL' file in the environment.
3. Run the whole code.

Explanation of all Files:
'diabetes_binary_dataset.csv' - This is the .csv file of the whole dataset.

'SVM_MODEL.ipynb' - This is the Jupyter notebook containing all the coding steps executed for the implementation of the support vector machine model, including both training and testing of baseline, grid search and final models.

'SVM_MODEL.ipynb' - This is the Jupyter notebook containing all the coding steps executed for the implementation of the multilayer perceptron model, including both training and testing of baseline, grid search and final models.

'BEST_SVM.pkl' - This is the .pkl file containing the best trained model for the support vector machine method.

'BEST_MLP.pkl' - This is the .pkl file containing the best trained model for the multilayer perceptron method.

'TEST_SET_SVM.csv' - This is the .csv file containing just the test set for the support vector machine model.

'TEST_SET_MLP.csv' - This is the .csv file containing just the test set for the multilayer perceptron model.

'SVM_TEST_EVAL.ipynb' - This is the Jupyter notebook which will be used to evaluate the final support vector machine model's performance along with visual results, such as confusion matrix and AUC-ROC curve.

'MLP_TEST_EVAL.ipynb' - This is the Jupyter notebook which will be used to evaluate the final multilayer perceptron model's performance along with visual results, such as confusion matrix and AUC-ROC curve.

'SVM_TEST_EVAL.html' - This is the .html version of the SVM_TEST_EVAL.ipynb Jupyter notebook, which is going to be used to check reproducibility.

'MLP_TEST_EVAL.html' - This is the .html version of the MLP_TEST_EVAL.ipynb Jupyter notebook, which is going to be used to check reproducibility.
