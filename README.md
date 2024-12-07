# Feature Selection in Machine Learning

This project demonstrates various techniques for feature selection in machine learning using a Jupyter Notebook.

## Project Overview

The project covers the following feature selection techniques:
1. **Dropping Constant Features**:
    - Removes features with zero variance.
    - Uses `VarianceThreshold` from `sklearn`.
2. **Feature Selection on a Larger Dataset**:
    - Applies the same techniques on a larger dataset to illustrate their effectiveness.

## Dependencies

The project requires the following dependencies:
- Python 3.x
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

## Installation

1. Clone this repository:
    ```sh
    git clone https://github.com/DarkLord-13/Machine-Learning-01.git
    ```

2. Navigate to the project directory:
    ```sh
    cd Machine-Learning-01
    ```

3. Install the required packages:
    ```sh
    pip install pandas numpy scikit-learn matplotlib seaborn
    ```

4. Open the Jupyter Notebook `FeatureSelectionML.ipynb` and run the cells to execute the project steps:
    ```sh
    jupyter notebook FeatureSelectionML.ipynb
    ```

## Usage

1. **Dropping Constant Features**:
    - Load the dataset.
    - Use `VarianceThreshold` to remove features with zero variance.

2. **Feature Selection on a Larger Dataset**:
    - Apply the same technique on a larger dataset to demonstrate its effectiveness.

## Results

The project demonstrates how to remove constant features from a dataset using `VarianceThreshold`. It also shows the application of this technique on a larger dataset to highlight its practicality.

## License

This project is licensed under the MIT License.
