# Foam_machine_learning
This project applies machine learning techniques to predict the thermal conductivity of foam structures based on their structural parameters. It includes a series of Jupyter notebooks that detail the process of optimizing machine learning models, selecting important descriptors, and comparing different models to identify the best predictor.

## Project Structure

- `data/foam.csv`: The primary dataset containing detailed structural parameters (full names used) and measured thermal conductivity values for model training and testing.
- `data/foam1.csv`: A supplementary dataset with abbreviated structural parameter names used for additional validation of the machine learning models.

Each dataset includes various descriptors that are critical for the prediction of thermal conductivity. It is important to note that `foam.csv` uses full descriptor names, while `foam1.csv` uses abbreviated names for the same descriptors. Understanding the naming convention is crucial when analyzing the data and interpreting the results.
- `ANN_optimization.ipynb`: Optimizes hyperparameters for 2-layer and 3-layer Artificial Neural Network (ANN) models.
- `descriptor_importance.ipynb`: Calculates the importance of each descriptor using the Random Forest method.
- `descriptor_screening.ipynb`: Screens and optimizes the descriptor set using forward and backward selection methods.
- `model_comparison.ipynb`: Compares the results of six different machine learning models to select the most suitable one and outputs the fitting results.


## Getting Started

You need Python 3.x and Jupyter Notebook to run the notebooks in this project. If these are not installed on your system, please follow the instructions on the [Python website](https://www.python.org/downloads/) and the [Jupyter website](https://jupyter.org/install) to install them.

## Contact
For any queries or assistance with the project, please open an issue here on GitHub or send an email to chen.long@siat.ac.cn
