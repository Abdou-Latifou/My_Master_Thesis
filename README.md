# 🎓 Estimation of the Extreme Value Index under Truncation

## 📘 Abstract
Estimating the Extreme Value Index (EVI) is crucial for analyzing rare events, such as extreme occurrences in finance, hydrology, or natural disasters. However, when data are truncated, classical estimators may lose their effectiveness.  
This thesis focuses on adapting the main EVI estimators — **Hill**, **Pickands**, and **Dekkers–Einmahl–de Haan (DEdH)** — in the context of truncation.

After a theoretical presentation of the estimators, we analyze the biases introduced and the Mean Squared Error (MSE) due to **left truncation** and propose specific corrections.  
Through data simulations and applications to real datasets, we evaluate the performance of these estimators in truncated scenarios.

The results show that, despite the simplicity of the classical methods, appropriate adjustments lead to more **robust and accurate estimates** under truncation.  
Finally, this work opens perspectives for extending these approaches to **multivariate** or **temporal** frameworks.

**Keywords:** Extreme Value Index, truncation, Hill estimator, Pickands estimator, DEdH estimator, rare events.

---

## 🧮 Main Objectives
- Study the impact of truncation on Extreme Value Index estimation.  
- Compare the performance of classical estimators under truncation.  
- Propose bias correction strategies and evaluate their efficiency through simulation.  
- Apply the methods to real-world datasets (e.g., hydrological or financial data).

---

## 🧠 Methodology
1. **Theoretical background** on EVT and truncation.  
2. **Implementation** of Hill, Pickands, and DEdH estimators in R.  
3. **Simulation studies** for different truncation rates and sample sizes.  
4. **Computation of bias and MSE** to evaluate estimator performance.  
5. **Application** to real data for validation.

---

## 📊 Tools and Environment
- **Language:** R  
- **Key libraries:** `evd`, `extRemes`, `ggplot2`, `truncdist`, `dplyr`  
- **Reproducible scripts:** available in the `/scripts` directory  
- **Plots and results:** in `/results`  

---

## 📂 Repository Structure


---

## 👤 Author
**Abdou-Latifou KEDJERI**  
Currently Master’s Student in Big Data and Artificial Intelligence  
[AIMS Senegal](https://aims-senegal.org) | [Université Gaston Berger](https://www.ugb.sn)  

📧 *abdou.l.kedjeri@aims-senegal.org*  
📍 *Mbour, Senegal*  

---

## 📚 Citation
If you use or reference this work, please cite as:
> Kedjeri, A.L. (2024). *Estimation of the Extreme Value Index under Truncation.* Master’s Thesis, Université Gaston Berger, Senegal.

---

## 🧾 License
This repository is distributed under the **MIT License**.  
Feel free to use, modify, and share it with proper attribution.

