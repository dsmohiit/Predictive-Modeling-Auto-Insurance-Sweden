#### **Predictive Modeling for Auto Insurance Claims – Sweden**  

This project analyzes and builds a **Simple Linear Regression model** to predict the total payment for insurance claims in Sweden based on the number of claims filed. The dataset used comes from Swedish motor insurance data.  

---

### **Dataset**  
The dataset (`swedish_insurance.csv`) consists of:  
- **`no_of_claims`**: Number of insurance claims made.  
- **`money_paid`**: Total payment for all claims (in thousands of Swedish Kronor).  

---

### **Project Workflow**  
1. **Exploratory Data Analysis (EDA)**  
   - Data inspection (`.info()`, `.describe()`)  
   - Handling missing values (if any)  
   - Visualizing distributions using **Seaborn & Matplotlib**  
   - Identifying outliers using **boxplots & histograms**  

2. **Feature Engineering**  
   - Renaming columns for clarity  
   - Checking correlation between variables  

3. **Model Development**  
   - Splitting data into training & testing sets  
   - Building a **Simple Linear Regression** model using **Scikit-Learn**  
   - Training the model and evaluating performance  

4. **Performance Evaluation**  
   - Calculating **Mean Squared Error (MSE)** & **R² Score**  
   - Plotting the **regression line** against actual data  

---

### **Technologies Used**  
- Python (Pandas, NumPy, Scikit-Learn, Matplotlib, Seaborn)  
- Google Colab Notebook  

---

### **How to Run the Project?**  
1. Clone the repository:  
   ```bash
   git clone https://github.com/your-username/insurance-prediction.git
   ```
2. Install dependencies:  
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn
   ```
3. Run the Google Colab Notebook.  
