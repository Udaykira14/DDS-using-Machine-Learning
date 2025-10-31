# 🚗 Driving Decision Strategy (DDS) Based on Machine Learning for Autonomous Vehicles

## 📖 Overview

The rapid growth of technology has opened up a new era of inventions designed to improve human life. One such innovation is **autonomous vehicles**, which aim to enhance driving safety and efficiency by replacing human drivers with artificial intelligence (AI).

While most current autonomous driving systems determine their driving strategies based solely on **external factors** (e.g., pedestrians, traffic, and road conditions), they often **ignore internal factors** such as the vehicle’s internal health, RPM levels, and consumable conditions.

This project introduces a novel approach — **Driving Decision Strategy (DDS)** — a machine learning–based system that optimizes the driving strategy by analyzing both **external** and **internal** vehicle conditions.

---
click to view [files](https://github.com/Udaykira14/DDS-using-Machine-Learning)
---

## 🧠 Proposed System

The **DDS algorithm** is built using a **Genetic Algorithm (GA)** framework to identify optimal “gene” values for better decision-making and prediction.

### ⚙️ Working Process

1. Sensor data from the vehicle is collected and stored in the cloud.
2. The DDS processes this data to analyze both internal and external conditions.
3. A **Genetic Algorithm** is applied to find optimal parameter values for driving decisions.
4. The system determines the **optimal driving strategy** for the autonomous vehicle.
5. The performance of DDS is compared against traditional machine learning algorithms like **Random Forest (RF)** and **Multilayer Perceptron (MLP)**.

---

## 🚀 Advantages

* ✅ **Enhanced Accuracy:** DDS with Genetic Algorithm provides better prediction accuracy compared to Random Forest and MLP.
* ✅ **Optimized Decision-Making:** Genetic optimization leads to faster and more efficient predictions.
* ✅ **Comprehensive Analysis:** Considers both external (road, traffic) and internal (engine, RPM, consumables) factors for improved driving strategies.

---

## 🧩 Technologies Used

* **Machine Learning Algorithms:** Genetic Algorithm, Random Forest, Multilayer Perceptron (MLP)
* **Data Source:** Vehicle sensor data stored in the cloud
* **Programming Language:** *[Specify language — e.g., Python / Java]*
* **Tools & Libraries:** *[e.g., NumPy, Scikit-learn, TensorFlow, etc.]*

---

## 📊 Comparison Summary

| Model              | Type              | Accuracy    | Remarks                                             |
| ------------------ | ----------------- | ----------- | --------------------------------------------------- |
| Random Forest      | Machine Learning  | Moderate    | Good for structured data but lacks adaptability     |
| MLP                | Neural Network    | High        | Effective but computationally expensive             |
| **DDS (Proposed)** | Genetic Algorithm | **Highest** | Optimized for both internal and external conditions |

---

## 🏁 Conclusion

The proposed **Driving Decision Strategy (DDS)** enhances autonomous vehicle performance by integrating both external and internal vehicle factors into its decision-making model. Through the use of **Genetic Algorithms**, DDS achieves **superior accuracy and efficiency** compared to traditional ML approaches such as Random Forest and MLP.