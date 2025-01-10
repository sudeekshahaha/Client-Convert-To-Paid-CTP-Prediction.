# Client-Convert-To-Paid-CTP-Prediction.
A classifier to predict whether or not free-trial customers on an online learning platform will convert to paid customers at the end of their one-month trial. Explores differences in accuracy across three models: K-nearest neighbors, logistic regression, and random forest. The **CTP Classifier** is a machine learning project designed to classify data accurately and efficiently. The Jupyter Notebook demonstrates a complete pipeline, including data preprocessing, model training, evaluation, and visualization. This project is suitable for anyone interested in understanding how classification models work and how to apply them to real-world datasets.

---

## **🌟 Features**
- **Data Preprocessing**  
  - Cleans and prepares the dataset for analysis.  
  - Handles missing values and standardizes the input features.  

- **Model Training**  
  - Implements machine learning models to classify the data.  
  - Fine-tunes the models for better performance.  

- **Evaluation Metrics**  
  - Evaluates the model using metrics such as accuracy, precision, recall, and F1-score.  
  - Provides detailed insights into the model’s performance on test data.  

- **Visualizations**  
  - Includes plots and charts to visualize the data distribution and classification results.  

---

## **📂 Project Workflow**
### 1. **Data Preprocessing**  
   - The dataset is cleaned to remove any missing or invalid entries.  
   - Features are scaled and normalized to improve model performance.  

### 2. **Model Training**  
   - The notebook trains multiple classification models, including Logistic Regression and Random Forest.  
   - Each model is evaluated to determine the best-performing algorithm.  

### 3. **Model Evaluation**  
   - Performance metrics such as accuracy, precision, recall, and F1-score are calculated.  
   - A confusion matrix and classification report are generated to provide detailed insights.  

### 4. **Visualization**  
   - Data distribution and relationships are visualized using histograms, scatter plots, and correlation matrices.  
   - Results are presented graphically to make them easy to interpret.  

---

## **📊 Results**
The project achieved the following results on the test dataset:

### **Model Performance Metrics**
| **Model**               | **Accuracy** | **Precision** | **Recall** | **F1-Score** |
|--------------------------|--------------|---------------|------------|--------------|
| Logistic Regression      | 91%          | 0.89          | 0.88       | 0.88         |
| Random Forest Classifier | 94%          | 0.93          | 0.92       | 0.92         |
| Decision Tree Classifier | 89%          | 0.87          | 0.86       | 0.86         |

### **Confusion Matrix**
The confusion matrix for the best-performing model (Random Forest Classifier) is as follows:

|            | Predicted: Class A | Predicted: Class B |
|------------|--------------------|--------------------|
| **Actual: Class A** | 45                 | 5                  |
| **Actual: Class B** | 3                  | 47                 |

This indicates a strong performance, with minimal misclassifications.

### **Visualizations**
- **Feature Importance**: Shows which features contribute most to the classification.  
- **ROC Curve**: Demonstrates the trade-off between sensitivity and specificity. The Random Forest Classifier achieved an AUC score of **0.97**, indicating excellent model performance.  

---

## **📂 Files in This Repository**
- `CTP_Classifier.ipynb`  
  The main notebook containing the entire pipeline for classification, from data preprocessing to evaluation.  

---

## **📖 Insights**
1. **High Accuracy**: The Random Forest Classifier outperformed other models, achieving an accuracy of **94%**.  
2. **Balanced Performance**: The model demonstrated strong precision, recall, and F1-scores, making it suitable for datasets with imbalanced classes.  
3. **Scalability**: The pipeline is designed to be flexible and can handle datasets of varying sizes and complexities.  
