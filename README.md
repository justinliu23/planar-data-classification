# planar-data-classification

## Table of Contents
- [Dependencies](#dependencies)
- [Usage](#usage)
  - [Running the Project](#running-the-project)
  - [Example Usage](#example-usage)

## Dependencies

The following Python libraries are required for the project:

- `numpy`: For numerical computations.
- `matplotlib`: For plotting graphs.
- `sklearn`: For implementing logistic regression and generating datasets.
- `planar_utils`: Custom utility functions for plotting decision boundaries and loading datasets.
- `testCases_v2`: Contains test cases for validating functions.
- `public_tests`: Contains additional test cases for public use.

## Usage

### Running the Project

Once the environment is set up and all dependencies are installed, you can run the Jupyter notebook:

1. Navigate to the directory containing the notebook.
2. Run `jupyter notebook` in the terminal.
3. Open `Planar_data_classification_with_one_hidden_layer.ipynb` in the browser.
4. Execute the cells in the notebook sequentially to see the output.

### Example Usage

After setting up the environment and running the notebook, you can perform the following:

- **Load the dataset**: The dataset is a simple 2D planar dataset, which will be used to demonstrate the classification tasks.

- **Train a Logistic Regression Model**: Train a logistic regression classifier and visualize the decision boundary. This serves as a baseline model.

- **Build a Neural Network Model**: A simple neural network with one hidden layer will be implemented from scratch. The model will be trained and tested on the same dataset.

- **Tune the Model**: Experiment with different hidden layer sizes to observe their impact on the decision boundary and model accuracy.
