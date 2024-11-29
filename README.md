# Lung Cancer Prediction Model

## Overview
This project implements various machine learning models to predict lung cancer based on patient symptoms and characteristics. The models analyze different health indicators to assess the likelihood of lung cancer presence, helping in early detection and diagnosis.

## Dataset
The dataset is sourced from [Kaggle's Lung Cancer Dataset](https://www.kaggle.com/datasets/mysarahmadbhat/lung-cancer) and includes the following features:
- YELLOW_FINGERS
- ANXIETY
- FATIGUE
- WHEEZING
- COUGHING
- SHORTNESS OF BREATH
- SWALLOWING DIFFICULTY
- CHEST PAIN

## Models Implemented
Six different machine learning models were implemented and compared:
1. Decision Tree
2. Random Forest
3. Support Vector Machine (SVM)
4. K-Nearest Neighbors (KNN)
5. Logistic Regression
6. Adaptive Boosting (AdaBoost)

## Model Performance
The models were evaluated using F1 scores, with the following rankings:
1. Random Forest: 0.953
2. SVM: 0.947
3. AdaBoost: 0.947
4. KNN: 0.941
5. Logistic Regression: 0.935
6. Decision Tree: 0.881

## Features and Functionality
- Data preprocessing and normalization
- Cross-validation for robust model evaluation
- Feature importance analysis
- ROC curve and AUC score analysis
- Confusion matrix visualization
- Precision-Recall curve analysis

## Key Visualizations
The project includes various visualizations:
- Feature importance plots
- ROC curves
- Confusion matrices
- Learning curves
- Distribution of predicted probabilities

## Requirements
```python
- sklearn
- numpy
- pandas
- matplotlib
- seaborn
```

## Installation
1. Clone the repository
```bash
git clone https://github.com/[your-username]/lung-cancer-prediction.git
```

2. Install required packages
```bash
pip install -r requirements.txt
```

## Usage
1. Load the dataset
2. Run the preprocessing steps
3. Train the models
4. Evaluate performance
5. Generate visualizations

## Results
- Successfully achieved over 90% F1 score with most models
- Random Forest showed the best overall performance
- Feature importance analysis revealed key indicators for prediction
- Cross-validation confirmed model stability and reliability

## Future Improvements
- Implement deep learning models
- Collect more data for better training
- Add more features for analysis
- Optimize hyperparameters
- Create a web interface for predictions

## Contributing
Feel free to fork the project and submit pull requests. For major changes, please open an issue first to discuss what you would like to change.

## License
[MIT](https://choosealicense.com/licenses/mit/)
