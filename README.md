# **Target Trial Emulation with Clustering**  

## **Submitted by:**  
**Kyn R. Honoridez**  
**Al Winmon Benedict T. Montebon**  

## **Overview**  
This project explores a novel method for **Target Trial Emulation (TTE)** by integrating **clustering techniques** into an existing epidemiological framework. The goal is to enhance causal inference by reducing biases in observational studies through **K-Means** and **alternative clustering methods** such as **DBSCAN**.  

The project follows a structured workflow:
1. **Convert R code to Python** and replicate the original **TTE framework**.
2. **Integrate clustering mechanisms** to refine treatment effect estimation.
3. **Analyze the impact of clustering** on model performance and survival predictions.

## **Instructions**  

### **1. Data Extraction**  
- Access the dataset from **[this resource](https://rpubs.com/alanyang0924/TTE)**.  
- Extract the dummy data package and save it as **`data_censored.csv`**.  

### **2. Code Conversion & Replication**  
- Convert the provided **R code** into **Python** using **Jupyter Notebook**.  
- Ensure the Python implementation **replicates the same results** as the original R framework.  

### **3. Implement Clustering into TTE (Version 2 - TTE-v2)**  
- Create a new copy of your Python code and name it **TTE-v2.ipynb**.  
- Identify a suitable step in the **TTE process** where clustering can be incorporated.  
- Implement **K-Means clustering** and analyze its effect on bias correction.  
- Explore an alternative clustering method (**e.g., DBSCAN, GMM, or Hierarchical Clustering**).  

### **4. Weight Model Adjustments**  
- Integrate **cluster labels** into **treatment switching** and **censoring weight models**.  
- Compute **Inverse Probability Weights (IPWs)** while accounting for clustering effects.  

### **5. Outcome Model & Survival Prediction**  
- Fit a **logistic regression model** to predict treatment outcomes.  
- Evaluate model fit using **McFadden’s Pseudo \(R^2\)**.  
- Apply a **Marginal Structural Model (MSM)** for survival analysis.  

### **6. Model Performance Comparison**  
- Compare clustering-enhanced models using:  
  - **Akaike Information Criterion (AIC) & Bayesian Information Criterion (BIC)**.  
  - **ROC-AUC scores** for classification performance.  
  - **Cross-validation** to assess generalizability.  
- Visualize clustering results and survival predictions.  

## **Deliverables**  
- 📂 **Python implementation in Jupyter Notebook (TTE.ipynb & TTE-v2.ipynb)**  
- 📊 **Summary report** comparing different clustering methods.  
- 📜 **GitHub repository** containing all code and documentation.  

## **Deadline**  
📅 **March 9, 2025, at 11:59 PM**  

## **Collaboration Guidelines**  
👥 **Work in pairs** (preferably with your thesis partner).  
🤖 **AI assistance is allowed**, but make sure you include your prompts in the submission.  
🚀 **Push the final version to GitHub before the deadline.**  

---
