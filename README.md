# Iris-Classification
A supervised machine learning model to differentiate between 150 samples of iris flowers based on sepal and petal measurement 

# Introduction
This project demonstrates a basic **Machine Learning classification task** using the famous **Iris dataset**.  
The dataset contains measurements of iris flowers (sepal length, sepal width, petal length, petal width) and their species:  
- Setosa  
- Versicolor  
- Virginica  

The goal of this model is to train a model that can classify iris species based on these features.

#  Project Workflow
1. **Data Loading**  
   - Used `scikit-learn` to load the Iris dataset.  
2. **Data Exploration**  
   - Visualized relationships between features using Seaborn pairplots.  
3. **Data Splitting**  
   - Divided dataset into training (80%) and testing (20%).  
4. **Model Training**  
   - Trained a **Decision Tree Classifier**.  
5. **Evaluation**  
   - Measured accuracy, confusion matrix, and classification report.  
6. **Visualization**  
   - Plotted confusion matrix heatmap for better understanding.


# Technologies Used
- Python 3.14
- Jupyter Notebook  
- Libraries: `numpy`, `pandas`, `matplotlib`, `seaborn`, `scikit-learn`


#  Results
- **Accuracy**: 1.0
- **Confusion Matrix**:
 [[10  0  0]
 [ 0  9  0]
 [ 0  0 11]]

<img width="685" height="449" alt="image" src="https://github.com/user-attachments/assets/a1ae88e5-158e-4d82-885a-8e414cdb5b5f" />

# Future Work

- Try other models such as Random Forest and Logistic Regression.
- Make a web app to display results and make it interactive.


