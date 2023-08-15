# Fish Species Classification

This project aims to classify different fish species using machine learning techniques. The dataset used for this project is stored in the `fish.csv` file. The classification is done using both logistic regression from scikit-learn and a neural network implemented using TensorFlow.

## Libraries Used

The following libraries were used in this project:

- `numpy`: Used for numerical computations and array operations.
- `pandas`: Used for data manipulation and analysis.
- `matplotlib`: Used for data visualization and creating plots.
- `sklearn.preprocessing.StandardScaler`: Used for standardizing feature data.
- `sklearn.preprocessing.LabelEncoder`: Used for encoding categorical labels into numerical values.
- `sklearn.model_selection.train_test_split`: Used for splitting the dataset into training and testing sets.
- `sklearn.linear_model.LogisticRegression`: Used for implementing the logistic regression model.
- `tensorflow`: Used for creating and training neural networks.

## Dataset

The dataset for this project is stored in the `fish.csv` file. It contains various features describing different fish samples, along with their corresponding species labels.

## Usage

1. Make sure you have all the required libraries installed. You can install them using the following command:

```bash
pip install numpy pandas matplotlib scikit-learn tensorflow
```

Clone this repository to your local machine.

```bash
git clone https://github.com/umairrrkhan/Fish-Species-Classification.git
```
## Results

The results of the classification will be displayed in the terminal or console when you run the fish_species_classification.py script. You will see the accuracy and other relevant metrics for both the logistic regression and neural network models.

## Conclusion

This project demonstrates how to perform fish species classification using machine learning techniques. It provides insights into data preprocessing, model training, and evaluation using both logistic regression and a neural network.

Feel free to customize and extend the project to further improve the classification accuracy or explore different algorithms.
