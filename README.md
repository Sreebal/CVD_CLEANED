# CVD_CLEANED
This repository contains Python code to build a machine learning model for predicting cardiovascular disease (CVD) using a Random Forest Classifier. The dataset used for training and testing the model is stored in an Excel file named `CVD_cleaned.xlsx`.
## Requirements
- Python 3.x
- pandas
- numpy
- matplotlib
- scikit-learn
## Setup
1. Clone this repository to your local machine.
2. Install the required Python libraries listed in the `requirements.txt` file using pip:

```bash
pip install -r requirements.txt
```
## Usage
1. Ensure you have the dataset `CVD_cleaned.xlsx` in the same directory as the Python script.
2. Run the Python script `CVD_prediction.py` to train the Random Forest Classifier model and evaluate its performance.

```bash
python CVD_prediction.py
```

3. After running the script, you will see the accuracy of the model printed on the console, along with the classification report and confusion matrix.
4. Additionally, a bar plot showing the feature importances will be displayed, indicating which features are most influential in predicting CVD.

## File Descriptions
- `CVD_cleaned.xlsx`: Excel file containing the cleaned dataset.
- `CVD_prediction.py`: Python script to train the Random Forest Classifier model and evaluate its performance.
- `README.md`: This file providing information about the project.

## Notes
- The script assumes that the target variable in the dataset is named `General_Health` and the features are all numeric.
- Missing values in the dataset are handled by replacing them with the mean of the respective column.
- Features are standardized using StandardScaler before training the model.
- The Random Forest Classifier model is trained with 100 estimators and a random state of 42 for reproducibility.

Feel free to modify the script or dataset according to your specific requirements. If you encounter any issues or have questions, please don't hesitate to contact me.
