# Iris Classification with PyTorch

This project demonstrates how to build a simple neural network using PyTorch to classify Iris flower species (Setosa, Versicolor, Virginica) based on their sepal and petal measurements.

## Project Structure

- **iris_classification.ipynb:** Jupyter Notebook containing the Python code for data loading, preprocessing, model definition, training, evaluation, and saving the model.
- **iris_model.pt:** Saved state dictionary of the trained PyTorch model.

## Requirements

- Python 3.6 or higher
- PyTorch
- Pandas
- Scikit-learn
- Matplotlib

## How to Run

1. **Install Dependencies:** Make sure you have the required libraries installed. You can use pip install torch pandas scikit-learn matplotlib
2. **Open Jupyter Notebook:** Launch Jupyter Notebook and open the `iris_classification.ipynb` file.
3. **Execute Cells:** Run all the cells in the notebook to load the data, train the model, evaluate its performance, and save the trained model.

## Model Architecture

The neural network consists of:

- Input layer (4 features: sepal length, sepal width, petal length, petal width)
- Hidden layer 1 (8 neurons) with ReLU activation
- Hidden layer 2 (9 neurons) with ReLU activation
- Output layer (3 neurons, representing the 3 Iris species)

## Dataset

The project uses the classic Iris dataset from scikit-learn, which contains 150 samples with 50 samples for each of the three Iris species.

## Results

The trained model achieves an accuracy of 93-100% on the test set depending on Random State as dataset is small.

## Contributing

Contributions are welcome! Feel free to open issues or pull requests for any improvements or bug fixes.
