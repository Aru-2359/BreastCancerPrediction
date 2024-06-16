# Breast Cancer Prediction using Logistic Regression 🎗️🎗️

This project aims to predict breast cancer diagnosis (malignant or benign) using logistic regression. Logistic regression is a statistical model that uses a logistic function to model a binary dependent variable.

## Dataset

The dataset used in this project contains various features computed from breast mass samples, such as mean radius, texture, perimeter, area, smoothness, compactness, concavity, concave points, and symmetry.

- **Features**:
  - `radius_mean`: mean of distances from center to points on the perimeter
  - `texture_mean`: standard deviation of gray-scale values
  - `perimeter_mean`: mean size of the core tumor
  - `area_mean`: mean area of the core tumor
  - `smoothness_mean`: mean of local variation in radius lengths
  - `compactness_mean`: mean of perimeter^2 / area - 1.0
  - `concavity_mean`: mean of severity of concave portions of the contour
  - `concave points_mean`: mean for number of concave portions of the contour
  - `symmetry_mean`: mean symmetry

The target variable is binary:
- `diagnosis`: 0 = benign, 1 = malignant

## Files

- `Model.ipynb`: Jupyter notebook containing data preprocessing, model training, evaluation, and predictions.
- `Dataset.csv`: Sample dataset used in the notebook (replace with your actual dataset).

## Dependencies

Make sure you have the following libraries installed:

- Python 3.x
- NumPy
- Pandas
- Scikit-learn
 
## Usage

1. Clone the repository:

   ```bash
   git clone https://github.com/Aru-2359/BreastCancerPrediction.git
   cd BreastCancerPrediction
   ```

2. Install dependencies:

   ```bash
   pip install numpy pandas scikit-learn
   ```

3. Open and run the Jupyter notebook:

   ```bash
   jupyter notebook Model.ipynb
   ```

4. Follow the notebook instructions to:
   - Load and preprocess the dataset.
   - Train a logistic regression model.
   - Evaluate the model using appropriate metrics (accuracy, precision, recall, etc.).
   - Make predictions on new data.

## Results

The logistic regression model achieved an accuracy score of 95.61 on the test set, demonstrating its potential utility in predicting breast cancer diagnoses based on the provided features.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- This project utilizes the Wisconsin Breast Cancer dataset. Special thanks to the UCI Machine Learning Repository for providing the dataset.
