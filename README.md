# Drug-Classification-Machine-Learning-model
Drug classification with various machine learning models project
# 1. Introduction 
<center><img src="https://images.pexels.com/photos/159211/headache-pain-pills-medication-159211.jpeg" alt="Drug Picture" width="700" height="500"></center><br>

## Data Set Problems 
*1. This dataset contains information about drug classification based on patient general information and its diagnosis. Machine learning model is needed in order **to predict the outcome of the drugs type** that might be suitable for the patient.

---

## Objectives of Project 📌
👉 **This Project aims to:**
*   Dataset exploration using various types of data visualization.
*   Build various ML models that can predict drug type.

👨‍💻 **The machine learning models used in this project are:** 
1. Linear Logistic Regression
2. Linear Support Vector Machine (SVM)
3. K Neighbours
4. Naive Bayes (Categorical & Gaussian)
5. Decision Tree
6. Random Forest

---

## Data Set Description 🧾

👉 There are **6 variables** in this data set:
*   **4 categorical** variables,and
*   **2 continuous** variables.

<br>

👉 The following is the **structure of the data set**.


<table style="width:100%">
<thead>
<tr>
<th style="text-align:center; font-weight: bold; font-size:14px">Variable Name</th>
<th style="text-align:center; font-weight: bold; font-size:14px">Description</th>
<th style="text-align:center; font-weight: bold; font-size:14px">Sample Data</th>
</tr>
</thead>
<tbody>
<tr>
<td><b>Age</b></td>
<td>Patient Age</td>
<td>23; 47; ...</td>
</tr>
<tr>
<td><b>Sex</b></td>
<td>Gender of patient <br> (male or female)</td>
<td>F; M; ...</td>
</tr>
<tr>
<td><b>BP</b></td>
<td>Levels of blood pressure <br> (high, normal, or low)</td>
<td>HIGH; NORMAL; LOW; ...</td>
</tr>
<tr>
<td><b>Cholesterol</b></td>
<td>Levels of cholesterol <br> (high or normal)</td>
<td>1.4; 1.3; ...</td>
</tr>
<tr>
<td><b>Na_to_K</b></td>
<td>Sodium to potassium ratio in blood</td>
<td>25.355; 13.093; ...</td>
</tr>
<tr>
<td><b>Drug</b></td>
<td>Type of drug</td>
<td>DrugY; drugC; ...</td>
</tr>
</tbody>
</table>

---
## Model Accuracy Comparison

Below is the comparison of accuracy scores for various models used in the project:

| Model                | Accuracy (%) |
|----------------------|--------------|
| Logistic Regression  | 85.00        |
| K Neighbors          | 85.00        |
| K Neighbors Max      | 83.33        |
| SVM                  | 83.33        |
| Categorical NB       | 81.66        |
| Gaussian NB          | 81.66        |
| Decision Tree        | 81.66        |
| Decision Tree Max    | 80.00        |
| Random Forest        | 66.66        |
| Random Forest Max    | 56.66        |

**Note:** The highest accuracy was obtained using the **Logistic Regression** model.
