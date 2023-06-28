# Handwritten Digits Classification Using Support Vector Machine (SVM)

In this Jupyter notebook, our objective is to explore and classify handwritten digits using the popular MNIST dataset. We will build an SVM model that can correctly classify digits from 0 to 9 based on their pixel values.

## Objective

The main goal is to develop an SVM model that accurately classifies handwritten digits. This is a 10-class classification problem, as we have 10 different digits (0-9) to classify. We will use the pixel values of the images as features to train our model.

The analysis will be divided into the following parts:

1. Data Import and Understanding: We will import the dataset and gain an understanding of its structure and content.
2. Data Preparation: We will preprocess the data to make it suitable for model building.
3. Model Building: We will train an SVM model on the preprocessed data.
4. Hyperparameter Tuning: We will fine-tune the parameters of the SVM model to optimize its performance.
5. Model Evaluation: We will evaluate the trained model's performance using appropriate metrics.

## Data Import

The dataset is stored in a file named "digit_svm.csv". It contains gray-scale images of hand-drawn digits ranging from 0 to 9. Each image is represented as a 28x28 pixel grid, resulting in a total of 784 pixels. Each pixel is assigned an integer value between 0 and 255, indicating its lightness or darkness.

The dataset consists of 785 columns. The first column, labeled "label", represents the digit drawn by the user, while the remaining columns contain the pixel values of the associated image.

## Conclusion

By building an SVM model on the MNIST dataset, we aim to accurately classify handwritten digits. Through the various steps outlined above, we will preprocess the data, train the model, optimize its performance, and evaluate its accuracy.