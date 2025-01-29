# Credit Worthiness Prediction

## Project Overview
This project aims to predict the creditworthiness of loan applicants using machine learning techniques. The dataset used is the German Credit Data, which includes various financial and demographic attributes. The objective is to develop an efficient model that can help financial institutions make informed credit decisions.

## Dataset
- **Source**: Kaggle - German Credit Data ([Dataset Link](https://www.kaggle.com/datasets/mpwolke/cusersmarildownloadsgermancsv))
- **Size**: 1000 observations, 21 attributes
- **Target Variable**: Creditability (1 - Good Credit, 0 - Bad Credit)
- **Key Features**:
  - Account Balance
  - Duration of Credit (months)
  - Payment Status of Previous Credit
  - Purpose
  - Credit Amount
  - Age, Employment Length, Housing, and more

## Methodology
1. **Data Preprocessing**:
   - Handling missing values
   - Identifying and treating outliers
   - Normalization and feature scaling
   - Data balancing check
2. **Exploratory Data Analysis (EDA)**:
   - Correlation heatmaps
   - Feature importance analysis
   - Data visualization
3. **Model Training**:
   - Logistic Regression
   - Decision Tree
   - Support Vector Machine (SVM)
   - Random Forest with Hyperparameter Tuning
4. **Evaluation Metrics**:
   - Accuracy
   - Precision, Recall, F1-score
   - Confusion Matrix
   - ROC Curve & AUC Score

## Results
| Model                | Accuracy  |
|----------------------|----------|
| Logistic Regression | 73.5%     |
| Decision Tree       | 72.5%     |
| Linear SVM         | 75.0%     |
| Sigmoid SVM        | 73.5%     |
| Polynomial SVM     | 71.0%     |
| Random Forest (Tuned) | **81.0%** |

**Best Model:** The **Random Forest model with hyperparameter tuning** achieved the highest accuracy (81%).

## Limitations & Future Improvements
- **Data Limitations**:
  - Small dataset size (1000 records)
  - Potential historical bias in the dataset
- **Model Enhancements**:
  - Further hyperparameter tuning
  - Incorporating deep learning models
  - Utilizing ensemble learning techniques
- **Real-World Adaptability**:
  - Continuous model updates with new data
  - Feature engineering for better insights
  
## Installation & Usage
1. Clone the repository:
   ```sh
   git clone https://github.com/your-username/credit-worthiness.git
   cd credit-worthiness
   ```
2. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```
3. Run the model:
   ```sh
   python train_model.py
   ```
4. Evaluate the model:
   ```sh
   python evaluate_model.py
   ```

## Contributions
Feel free to fork this repository and submit pull requests with improvements. Any feedback or suggestions are welcome!

## Author
**Praneeth Reddy Tene**  
University of Tampa, Sykes College of Business
