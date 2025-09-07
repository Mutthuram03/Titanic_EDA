# Titanic EDA – Mutthuram

## 📌 Overview
This project performs **Exploratory Data Analysis (EDA)** on the Titanic dataset using **Python (Pandas, Matplotlib, Seaborn)** in Google Colab.  
The dataset contains details about passengers on the Titanic ship, including age, sex, class, fare, and survival status.  
The goal is to explore the data, identify trends and patterns, and propose a research idea based on insights.

---

## 📊 Dataset
- Source: `sns.load_dataset("titanic")` (built-in Seaborn dataset)  
- Shape: **891 rows × 15 columns**  
- Key Columns:
  - `survived`: Survival status (0 = No, 1 = Yes)  
  - `sex`: Male / Female  
  - `age`: Passenger age  
  - `class`: Passenger class (First, Second, Third)  
  - `fare`: Ticket price  
  - `embarked`: Port of boarding  

---

## 🔍 EDA Steps
1. **Data Loading**: Loaded dataset with Pandas & Seaborn.  
2. **Data Summary**: Checked shape, column types, missing values, and descriptive statistics.  
3. **Basic Statistics**:
   - Mean Age: ~29.7 years  
   - Median Age: ~28 years  
   - Maximum Fare: 512.33  
   - Minimum Fare: 0  
4. **Visualizations**:
   - Survival Count (0 vs 1)  
   - Age Distribution of Passengers  
   - Survival Rate by Gender  
   - Fare Distribution by Class  
   - Survival Rate by Class  

---

## 📈 Key Findings
- **Gender**: Females had a much higher survival rate than males.  
- **Class**: First-class passengers had better survival chances than second and third-class passengers.  
- **Age**: Younger passengers (especially children) had slightly higher survival.  
- **Fare**: Passengers who paid higher fares (wealthier passengers) were more likely to survive.  

---

## 💡 Research / Innovation Idea
### Problem  
In real-world disasters (like shipwrecks, plane crashes, or train accidents), survival rates are influenced by **demographics (gender, age) and socio-economic status (ticket class, seat location)**.  
This often leads to **unfair survival chances** for certain groups.  

### Proposed Solution  
An **AI-driven Evacuation Planning System** that:  
- Uses demographic + seating/boarding data in real-time.  
- Predicts risk patterns (who is most vulnerable).  
- Generates optimized evacuation strategies to maximize overall survival.  

### R&D Development Steps  
1. Train predictive models using historical datasets (Titanic + other disaster datasets).  
2. Simulate evacuation scenarios with different strategies.  
3. Optimize evacuation plans for fairness and efficiency.  

### Validation  
- Run simulations with and without AI-based planning.  
- Compare survival outcomes.  
- Adjust demographic weighting to ensure fairness.  

---

## ⚙️ Technologies Used
- **Python**  
- **Google Colab**  
- **Pandas** – data handling  
- **Matplotlib** & **Seaborn** – visualization  
- **GitHub** – project version control  

---

## 📂 Repository Contents
- `Titanic_EDA_Mutthuram.ipynb` → Google Colab notebook with code and plots  
- `README.md` → Project description and findings  

---

## 🚀 How to Run
1. Open [Google Colab](https://colab.research.google.com/).  
2. Upload `Titanic_EDA_Mutthuram.ipynb`.  
3. Run all cells to reproduce the analysis and plots.  

---

## ✍️ Author
**Mutthuram**  
2nd Year B.Tech CSE, SRM KTR  
