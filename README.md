# 🧪 Data Analysis - A/A Test for Food Products

This project explores consumer behavior in an **A/A test experiment** involving food products. The primary goal is to **validate the consistency** of the experimental variants before moving on to an A/B test, ensuring that any observed differences are not simply due to chance.

---

## 📊 Project Objective

Our main objective is to analyze user behavior under two identical conditions (an A/A Test) to:

* **Validate experiment randomization**: Confirm that users are randomly assigned to groups without bias.
* **Evaluate statistical differences in behavior**: Assess if there are any inherent statistical differences between the groups, even when exposed to identical conditions.
* **Prepare for a future A/B Test**: Establish a solid baseline for more confident A/B testing in the future.

---

## 🧰 Technologies Used

This project leverages the following technologies and libraries:

* **Python 3**
* **Pandas**: For robust data manipulation and analysis.
* **NumPy**: Essential for numerical operations.
* **Seaborn & Matplotlib**: For creating informative and appealing data visualizations.
* **Scipy Stats**: For performing various statistical tests, including `t-tests` and proportion tests.

---

## 📈 Analysis Overview

The analysis involved several key steps:

* **Data Loading and Cleaning**: Initial preparation of the dataset.
* **Exploration and Visualization**: Understanding key variables through plots and summaries.
* **Statistical Comparison**: Comparing the two "A" groups statistically.
* **Conversion and Frequency Calculations**: Deriving metrics like conversion rates.
* **Hypothesis Validation**: Using statistical tests (`t-test` and proportions) to confirm hypotheses.

---

## 📊 Visualizations

The analysis includes four illustrative graphs:

1.  **Distribution of events by date**
    <p align="center">
        <img src="images/1.png"  alt="Distribución de eventos por fecha" widht = 70%>
    </p>

2.  **Conversion percentage by hour**
    <p align="center">
        <img src="images/2.png"  alt="Porcentaje de conversión por hora" widht = 70%>
    </p>

3.  **Visual comparison between the test groups**
    <p align="center">
        <img src="images/4.png"  alt="Comparación visual entre los grupos de prueba" widht = 70%>
    </p>

4.  **Relationship between event frequency and conversion**
    <p align="center">
        <img src="images/3.png"  alt="Relación entre frecuencia de eventos y conversión" widht = 70%>
    </p>

---

## 📌 Key Results

* Average conversion rates were observed in ranges such as **0.45, 0.5, and 0.7** across the analyzed events.
* Cases with **0.00% conversion** were identified, which helped validate behavioral extremes.
* Crucially, the analyzed values showed **no significant differences** between the groups, which is exactly what we expect from a successful A/A Test.

---

## ✅ Conclusion

The analyses confirm that there are **no statistically significant differences** between Group A and Group A. This validates the **correct randomization** of our experiment. The observed conversion rates are very similar, reinforcing the idea that any minor variations are simply due to chance and not systematic bias.

This successful A/A test provides a **reliable and confident foundation** for conducting future A/B experiments, knowing that our experimental setup is sound.

---