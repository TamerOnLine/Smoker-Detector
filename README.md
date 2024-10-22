
# Smoker Detector

## Overview

This project aims to develop a **Smoker Detector** model that predicts whether a person is a smoker or not based on several health-related factors such as age, BMI, number of children, and charges. The project utilizes data preprocessing, class balancing techniques (like SMOTE and undersampling), and logistic regression to build an accurate predictive model.

## Features

- **Data Preprocessing**: Handling missing values, normalizing data, and converting categorical variables into numerical values.
- **Class Imbalance Handling**: Techniques like SMOTE and Random Undersampling are applied to address class imbalance and improve model performance.
- **Modeling**: Logistic regression model is built and trained on balanced data.
- **Evaluation**: The model is evaluated based on accuracy, recall, precision, and F1 score.

## Project Structure

- `Blanks_A_Better_Smoker_Detector.ipynb`: Jupyter notebook containing the code for data processing, modeling, and evaluation.
- `data/`: Directory containing the dataset.
- `README.md`: Documentation file.
- `requirements.txt`: List of dependencies required to run the project.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/your-repo.git
   cd your-repo
   ```

2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the Jupyter notebook:
   ```bash
   jupyter notebook Blanks_A_Better_Smoker_Detector.ipynb
   ```

## Dataset

The dataset contains the following features:

- `age`: Age of the individual.
- `sex`: Gender (Male/Female).
- `bmi`: Body Mass Index.
- `children`: Number of children.
- `smoker`: Whether the individual is a smoker or not (Yes/No).
- `region`: Region where the individual resides.
- `charges`: Medical charges billed by health insurance.

## Model Improvement

The model has been improved using the following techniques:

- **Handling Class Imbalance**: Using SMOTE and undersampling to balance the dataset and improve the model's predictive performance.
- **Model Re-training**: Logistic Regression model is re-trained on resampled data to enhance classification results.

## Results

After balancing the dataset, the model showed significant improvements in accuracy, recall, and F1-score. The scores before and after balancing the data were compared to ensure that the class imbalance handling methods were effective.

## Future Work

- Explore more advanced machine learning algorithms (e.g., Random Forest, Gradient Boosting).
- Implement hyperparameter tuning to optimize model performance further.
- Consider using more features or external data sources to improve the model's predictive accuracy.

## License

This project is licensed under the MIT License.
