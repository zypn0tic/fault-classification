# fault-classification

# Electrical Fault Detection and Classification

Reliable power systems depend on fast and accurate fault detection. Electrical faults—if left undetected—can damage equipment, disrupt service, and compromise safety.  
This project applies **machine learning** to detect and classify electrical faults using real-world measurement data.

The goal is simple:  
**learn fault patterns from electrical signals and classify them correctly using an interpretable ML model.**

---

## 📌 Project Overview

This repository contains a comprehensive machine learning pipeline for **electrical fault detection and classification**, emphasizing clarity, interpretability, and practical relevance.

### Key Goals
- Detect the presence of an electrical fault  
- Classify the **type of fault**  
- Understand how electrical parameters contribute to fault decisions  

A **Decision Tree Classifier** is used as the primary model due to its rule-based nature and interpretability, making it suitable for power system analysis.

---

## 📊 Dataset

- **Dataset Name:** Electrical Fault Detection and Classification  
- **Source:** Kaggle  
- **Dataset Link:**  
  https://www.kaggle.com/datasets/esathyaprakash/electrical-fault-detection-and-classification/data  

### Dataset Description
The dataset contains electrical measurements recorded under both normal and faulty operating conditions. Each sample is labeled according to the fault type.

Typical features include:
- Phase voltages and currents  
- System imbalance indicators  
- Binary and categorical fault labels  

---

## 🧠 Methodology

The project follows a standard machine learning workflow:

1. **Data Preprocessing**
   - Feature-label separation  
   - Data consistency checks  

2. **Exploratory Data Analysis (EDA)**
   - Fault distribution analysis  
   - Feature behavior inspection  

3. **Modeling**
   - Decision Tree Classifier  
   - No heavy feature scaling required  

4. **Evaluation**
   - Train-test split  
   - Accuracy and confusion matrix analysis  

---

## 🌳 Why Decision Trees?

Decision Trees are well-suited for this task because:
- They resemble traditional **rule-based fault logic**
- They handle non-linear feature interactions
- Their decisions are **easy to interpret**
- Feature importance is directly observable

This makes them an excellent baseline before exploring more complex models.

---

## 📈 Results

The trained model:
- Successfully distinguishes between normal and faulty conditions  
- Accurately classifies multiple fault types  
- Provides interpretable decision paths for analysis  

The results show that even a simple tree-based model can perform reliably on structured electrical data.

---

## 🔬 Inspiration

The following Kaggle notebook inspires this project:

- **Fault Prediction using Decision Tree Algorithm**  
  https://www.kaggle.com/code/pythonafroz/fault-prediction-using-decision-tree-algorithm  


