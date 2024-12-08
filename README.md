# Predicting the Risk Probability of Developing Chronic Medical Conditions from a Depression Dataset
_Final Project for Data Science_

## 📜 Description 
**Business Problem:**
Healthcare providers face increasing challenges in managing the growing number of patients with chronic medical conditions. Prevention is more cost-effective than treatment, but identifying individuals at high risk before symptoms manifest is difficult due to the complex interplay of lifestyle, socio-economic, and genetic factors.

**The goal of this projects are:**
Predict the likelihood of developing chronic medical conditions based on individual attributes
Design personalized prevention strategies for high-risk individuals.  

## 🛠️ Tools  
- **Python**: Major programming languages.  
- **Libraries**: Pandas, NumPy, Matplotlib, Seaborn, LabelEncoder, variance_inflation_factor, train_test_split,
                 StandardScaler, accuracy_score, classification_report, confusion_matrix, make_scorer,
                 LogisticRegression, DecisionTreeClassifier, RandomForestClassifier, XGBClassifier, KNeighborsClassifier,
                 GaussianNB, GridSearchCV, cross_val_score  
- **Jupyter Notebook**: For development and documentation of analysis.  

## 📂 Project Structure 
- `FP_DS27_CahyoPrasetiyoWibowo.ipynb`: The main notebook contains analysis and results.  
- **Dataset**: Dataset used in the analysis https://www.kaggle.com/datasets/anthonytherrien/depression-dataset   
- **Visualisasi**: Graphs to support data analysis.  

## 📊 Fitur Utama  
1. **Data Preprocessing**
   - Data Understanding
   - Data Cleaning
   - Feature Engineering
   - Feature Selection  

2. **Analisis Eksplorasi Data (EDA)**  
   - Checking the distribution of target variable data "Chronic Medical Condition".
   - Checking the distribution of Income against the target variable
   - Checking the distrubution of Health Score against the target variable

3. **Visualisasi Data**  
   - The distribution target variable to show  unbalanced data with a total of 277561 for class 0, while for class 1 it has a total of 136207.
   - ![image](https://github.com/user-attachments/assets/2448c35f-21b3-49ef-a744-c5e021676eb5)



4. **Rekomendasi**  
  1. Focus on Low-Income Segments
    * Strategy:
      Prioritize low-income individuals in prevention programs, such as providing subsidized or free healthcare services.
    * Operational Recommendations:
      Launch health education programs and regular check-ups for individuals from low-income groups.
  2. Improve Health Scores through Preventive Programs
    * Strategy:
      Identify individuals with low health scores and offer data-based interventions, such as exercise programs, diets, or regular health check-ups.
    * Operational Recommendations:
      Establish partnerships with gyms, nutritionists, or health platforms to support customers in improving their health scores.
  3. Promote a Healthy Lifestyle
    * Strategy:
      A healthy lifestyle campaign, such as reducing smoking and alcohol consumption, and increasing exercise.
    * Operational Recommendations:
      Hold healthy lifestyle seminars and workshops for the community. 
