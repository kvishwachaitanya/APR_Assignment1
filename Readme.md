# Logistic Regression - Life Insurance Prediction

This project demonstrates a simple **Logistic Regression** model to predict whether a person will buy life insurance based on their **age**.  
It is a **binary classification problem** with two possible outcomes:
- **1** → Person buys insurance  
- **0** → Person does not buy insurance  

---

## 📂 Project Structure
- `logistic_regression.ipynb` → Jupyter Notebook containing the full code, explanations, and visualizations.  

---

## ⚙️ Technologies & Libraries Used
The project is implemented in Python using the following libraries:
- **pandas** → Data handling  
- **matplotlib** → Data visualization  
- **scikit-learn** → Model training and evaluation  

---

## 📊 Dataset
The dataset contains:
- **Age** → Independent variable (predictor)  
- **Bought Insurance** → Dependent variable (target: 0 or 1)  

It demonstrates how age influences the likelihood of purchasing insurance.

---

## 🚀 Steps Implemented
1. **Importing Libraries**  
   Load required Python libraries such as pandas, matplotlib, and scikit-learn.  

2. **Loading Dataset**  
   Read the dataset into a DataFrame for exploration.  

3. **Data Visualization**  
   Plot graphs to observe how age correlates with insurance purchases.  

4. **Data Splitting**  
   Split the dataset into **training** and **testing** sets using `train_test_split`.  

5. **Model Training**  
   Train a **Logistic Regression** model using scikit-learn.  

6. **Model Prediction**  
   Predict outcomes on the test data.  

7. **Evaluation**  
   Check model performance with accuracy metrics.  

---

## 📈 Example Visualization
The notebook includes a visualization of how the probability of buying insurance increases with age using the logistic regression curve.  

---

## ▶️ How to Run
1. Clone this repository:
   ```bash
   git clone <your_repo_link>
   cd <your_repo_name>

2. Install dependencies:
   pip install pandas matplotlib scikit-learn

3. Open the Jupyter Notebook:
   jupyter notebook logistic_regression.ipynb

4. Run all cells to reproduce results.
