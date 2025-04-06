## Radial Basis Function

An RBF network is a feedforward neural network that uses radial basis functions (like Gaussian) as activation functions in the hidden layer. It’s particularly well-suited for function approximation and regression.

It typically has three layers:
- **Input Layer**
- **RBF Hidden Layer**: Applies a Gaussian transformation to inputs
- **Output Layer**: Performs linear regression on transformed features

The hidden layer transforms the input features into a new space using radial basis functions, making it effective for capturing non-linear relationships.


## 🛌 Dataset: Sleep Time Prediction

The model uses the dataset `sleeptime_prediction_dataset.csv`, which contains data that influence sleep duration.


### Features may include:
- Screen time
- Caffeine consumption
- Physical activity
- Stress or anxiety levels
- Work hours, etc.

### Target:
- `Sleep Duration (in hours)`


## 🧰 Technologies Used

- Python
- NumPy
- Pandas
- Scikit-learn
- Matplotlib / Seaborn (for plotting)
- Custom or Scikit-learn-based RBF implementation


## 📂 Notebook Structure

1. **Importing Libraries** – Load essential libraries.
2. **Loading the Dataset** – Read and explore the dataset.
3. **Preprocessing** – Normalize features, split data into training and testing sets.
4. **RBF Network Implementation** – Define the model structure, basis functions, and trainable parameters.
5. **Training the Model** – Train the RBF network on the dataset.
6. **Evaluation** – Measure the accuracy or error of predictions.
7. **Visualization** – Plot decision boundaries, error trends, or prediction outcomes.


## 📊 Results

- Accuracy / RMSE / MAE: *[Displayed in notebook]*
- Visualizations include:
  - Model predictions vs true values for training dataset.
  - Model predictions vs true values for testing dataset.
