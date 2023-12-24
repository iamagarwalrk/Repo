# Exploring Support Vector Machines (SVM) for Classification

Support Vector Machines (SVM) is a versatile machine learning algorithm widely used for classification tasks. This Jupyter Notebook aims to provide an in-depth exploration of SVM, covering fundamental concepts, data generation, visualization, and the application of different kernels.

## Overview

In this project, we follow a structured approach to understanding SVM and its applications:

1. **Data Generation:** Synthetic datasets are generated to showcase SVM's capabilities, including handling non-linear decision boundaries.

2. **Visualization:** Matplotlib and Seaborn are employed to visualize the generated datasets in 2D scatter plots, aiding in the intuitive understanding of the algorithm's behavior.

3. **DataFrame Generation:** Utilizing Pandas DataFrames, we organize and structure the data, assigning labels for training.

4. **Data Splitting:** The dataset is divided into training and testing sets using the `train_test_split` function from scikit-learn, ensuring a robust evaluation of the model.

5. **Linear Kernel SVM:** We delve into the basics of SVM by applying a linear kernel, training the classifier, and evaluating its performance using accuracy metrics.

6. **Polynomial Kernel Components:** Understanding the components of polynomial kernels by creating additional features like squared terms and cross-products, enhancing the model's capacity to capture non-linear relationships.

7. **3D Visualization:** Leveraging Plotly Express, we visualize the data and decision boundaries in 3D space, providing a deeper insight into the SVM algorithm's behavior.

8. **RBF Kernel SVM:** We extend our exploration by applying the SVM algorithm with a radial basis function (RBF) kernel, showcasing its ability to handle complex, non-linear relationships.

## Dependencies

Ensure you have the following Python libraries installed:

- pandas
- seaborn
- matplotlib
- numpy
- scikit-learn
- plotly

Feel free to run each code cell sequentially, allowing for a step-by-step exploration of SVM and its various aspects. The notebook is designed to be informative and interactive, facilitating a better understanding of Support Vector Machines in classification tasks.

Let's embark on this journey into the world of SVM!
