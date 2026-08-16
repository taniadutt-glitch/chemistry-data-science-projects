# Advanced Computational Chemistry & Data Science Portfolio
### Tania Dutta | B.Sc. Chemistry Undergraduate

This repository houses advanced computational science projects that bridge laboratory chemistry concepts with python data structures, signal processing, and machine learning models across diverse high-impact sectors.

## 📁 Repository Directory

### 🧬 Cheminformatics & Healthcare
* **Project_1_Solubility_Predictor.ipynb**: Random Forest regression architecture evaluating structural molecular attributes to estimate aqueous solubility metrics.
* **Project_6_Cognitive_Neuro_Screening.ipynb**: In-silico molecular docking and thermodynamics screening pipeline modeling small-molecule drug interaction with cognitive neural receptors.

### 🧪 Advanced Lab Automation & Instrumentation
* **Project_2_Spectral_Parser.ipynb**: Automated noise reduction pipelines utilizing Savitzky-Golay filters alongside algorithmic peak-tracking for laboratory UV-Vis instrumentation.

### 🌿 Environmental & Renewable Energy Systems
* **Project_3_Degradation_Kinetics.ipynb**: Non-linear optimization models extracting reaction constants and environmental decay curves for chemical contaminants.
* **Project_5_Battery_Kinetics_Optimization.ipynb**: Electrochemical optimization engine modeling non-linear charge-discharge voltage degradation curves for lithium/flow battery systems.

### 🔎 Food Safety & Forensic Analytics
* **Project_4_Food_Safety_Classifier.ipynb**: Screening algorithm parsing heavy metal contamination counts against statutory FSSAI safety criteria.
* **Project_7_Forensic_Chemical_Classifier.ipynb**: Machine learning substance verification engine using infrared/raman spectroscopic fingerprint intensities to classify counterfeit compounds.
* ### 🔎 Food Safety & Forensic Analytics
* **Project_4_Food_Safety_Classifier.ipynb**: Screening algorithm parsing heavy metal contamination counts against statutory FSSAI safety criteria.
* **Project_7_Forensic_Chemical_Classifier.ipynb**: Machine learning substance verification engine using infrared/raman spectroscopic fingerprint intensities to classify counterfeit compounds.
* **Project_8_Chemical_Batch_Auditor.ipynb**: Automated Quality Assurance LIMS script parsing multi-conditional batch reports (purity, moisture, impurities) to flag structural compliance anomalies.

# Cheminformatics & AI in Pharma: Project Portfolio

Welcome to my repository showcasing the intersection of **Chemical Sciences, Artificial Intelligence, and Data Science**. As a BSc Chemistry undergraduate, I use computational tools and Machine Learning to evaluate molecular drug-likeness and predict pharmaceutical properties.

---

## 🚀 Projects Overview

### 1. Molecular Drug-Likeness Filter (Lipinski's Rule of 5)
* **Objective:** Automatically evaluate whether a chemical compound has structural properties that make it a viable orally active drug candidate in humans.
* **How it works:** The Python script screens input molecules against four strict threshold rules defined by Christopher Lipinski (Molecular Weight, LogP, Hydrogen Bond Donors, and Hydrogen Bond Acceptors). It outputs pass/fail status and flags specific boundary violations.
* **Skills Demonstrated:** Python logic, parameter validation, and conditional programming applied to pharmaceutical rules.

### 2. Predictive Chemical Solubility (LogS) Engine
* **Objective:** Use supervised Machine Learning to predict an unknown compound's aqueous solubility based on structural attributes.
* **How it works:** Built a predictive modeling engine in Python using `scikit-learn` and `pandas`. Trained a Linear Regression model on structural parameters (Molecular Weight and LogP) to approximate experimental water solubility logs (LogS).
* **Skills Demonstrated:** Data handling, training/testing splitting datasets, model performance scoring (R² Metrics), and predictive chemical modeling.

---

## 🛠️ Tech Stack & Concepts Used

* **Languages:** Python 3
* **Libraries:** Pandas, Scikit-Learn
* **Key Frameworks:** LSSSDC (National Skills Qualification Framework Level 5) - *AI in Pharma*, Cisco Certified Data Science Fundamentals.
* **Core Concepts:** Cheminformatics, Supervised Machine Learning, Molecular Evaluation, Linear Regression, Data Evaluation.

---

## 📊 Sample Execution Outputs

### Project 1: Lipinski's Rule Filter (Aspirin)
```text
--- Analyzing Compound: Aspirin ---
✅ Passed: Molecular Weight (180.16 Da) is <= 500
✅ Passed: LogP (1.2) is <= 5
✅ Passed: Hydrogen Bond Donors (1) <= 5
✅ Passed: Hydrogen Bond Acceptors (4) <= 10

Conclusion: APPROVED as a drug candidate (0 violations).
```

### Project 2: Solubility Machine Learning Model
```text
--- Model Evaluation ---
Mean Squared Error: 0.5505
R2 Score: 0.6840

Predicted LogS Solubility for Virtual Compound: -2.38
```

---

## 💡 About Me
I am a **BSc Chemistry Student** specializing in transitioning traditional chemical principles into data-driven solutions. My passion lies in utilizing Machine Learning pipelines to accelerate drug discovery pipelines and optimize digital healthcare applications.

📬 Connect with me on [LinkedIn](https://linkedin.com)

## 🛠️ Tech Stack
* **Domain Chemistry:** RDKit
* **Data Processing & Analytics:** NumPy, SciPy, Pandas
* **Modeling & Infrastructure:** Scikit-Learn, Python 3.x
* **Data Visualization:** Matplotlib, Seaborn
