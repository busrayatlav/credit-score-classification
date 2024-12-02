# Credit Score Classification

## Description
This project predicts the credit scores of individuals as `Good`, `Standard`, or `Poor` using financial and credit-related features. It employs a Random Forest Classifier to achieve accurate classification and provides insights into the factors affecting credit scores.

---

## Features
- Predicts credit scores based on financial attributes like annual income, number of bank accounts, credit card usage, and more.
- Includes data exploration to uncover trends and relationships between features and credit scores.
- Utilizes a Random Forest Classifier for robust predictions.

---

## Example Input
- Annual Income: $19,114.12  
- Monthly Inhand Salary: $1,824.84  
- Number of Bank Accounts: 2  
- Number of Credit Cards: 2  
- Interest Rate: 9%  
- Number of Loans: 2  
- Average Delay in Payments: 12 days  
- Number of Delayed Payments: 3  
- Credit Mix: 2 (`Good`)  
- Outstanding Debt: $250  
- Credit History Age: 200 months  
- Monthly Balance: $310  

### Example Output
- **Predicted Credit Score**: `Good`

---

## Results
- Random Forest Classifier achieved high accuracy in predicting credit scores.
- Data exploration revealed key insights:
  - Higher annual income and monthly salary positively affect credit scores.
  - More bank accounts and credit cards do not necessarily improve credit scores.
  - Longer credit history contributes to better scores.
  - Delayed payments negatively impact credit scores.

---

## Dependencies
- Python 3.7+
- Pandas
- NumPy
- Scikit-learn
- Plotly

---

## Future Improvements
- Include additional features like employment history and housing status.
- Experiment with other algorithms like Gradient Boosting or XGBoost.
- Deploy the model as an interactive web application using Flask or Streamlit.

---

## Usage

### Running the Project
1. Clone the repository:
    ```
    git clone https://github.com/yourusername/credit-score-classification.git
    cd credit-score-classification
    ```
2. Install dependencies:
    ```
    pip install -r requirements.txt
    ```
3. Run the script:
    ```
    python credit_score_classification.py
    ```
4. Provide input features and get predictions for credit scores.

---

## License
This project is licensed under the MIT License.

---

## Acknowledgements
- **Dataset**: Sourced from publicly available credit score data.
- **Inspiration**: Inspired by Aman Kharwal's article on credit score classification.
