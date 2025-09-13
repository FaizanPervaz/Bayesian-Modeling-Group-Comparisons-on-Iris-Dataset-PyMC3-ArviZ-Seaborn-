# Bayesian-Modeling-Group-Comparisons-on-Iris-Dataset-PyMC3-ArviZ-Seaborn-
Bayesian analysis of the Iris dataset using PyMC3, comparing priors (Normal vs. Student-T) and evaluating group differences with Cohen’s d and probability of superiority.

# Bayesian Modeling & Group Comparisons on Iris Dataset  

This project applies **Bayesian inference** and **group comparison techniques** on the classic Iris dataset using **PyMC3** and supporting libraries. The primary focus is on modeling the **sepal width** feature, comparing prior distributions, and analyzing differences across iris species (Setosa, Versicolor, Virginica).  

---

## 📌 Objectives  
1. **Bayesian Prior Estimation**  
   - Define priors for the `sepal_width` column using:  
     - Normal Distribution  
     - Student-T Distribution  
   - Compare robustness of the two priors.  

2. **Group Modeling & Violin Plots**  
   - Create groups (Setosa, Versicolor, Virginica) based on `sepal_width`.  
   - Visualize groups using **violin plots**.  
   - Generate posterior samples using PyMC3 models.  

3. **Group Comparisons**  
   - Apply statistical techniques for comparing groups:  
     - **Cohen’s d**  
     - **Probability of Superiority**  
   - Use reference values for interpretation.  

---

## 🛠️ Tech Stack / Libraries  
- **PyMC3** → Bayesian modeling & inference  
- **ArviZ** → Bayesian diagnostics & visualization  
- **Seaborn & Matplotlib** → Visualization & violin plots  
- **Pandas & NumPy** → Data processing  
- **SciPy** → Statistical metrics  

---

## 📊 Workflow  
1. **Load Dataset** → `Iris.csv`  
2. **Define Bayesian Models** → Prior + Likelihood  
3. **Sample from Posterior** → MCMC sampling with PyMC3  
4. **Compare Priors** → Normal vs. Student-T robustness check  
5. **Group Analysis** → Create subsets for species  
6. **Group Comparisons** → Apply Cohen’s d & probability of superiority  
7. **Visualize Results** → Violin plots, posterior plots, statistical comparison charts  

---

## 📈 Example Outputs  
- Robustness comparison of **Normal vs. Student-T priors**  
- Violin plots of `sepal_width` across iris species  
- Posterior comparison metrics (Cohen’s d, probability of superiority)  
- Interpretation of group differences with visual + statistical evidence  

---

## 🚀 How to Run  
1. Clone this repository:  
   ```bash
   git clone https://github.com/your-username/iris-bayesian-analysis.git
   cd iris-bayesian-analysis

2. Install dependencies:
   ```bash
   pip install pymc3 arviz seaborn pandas numpy scipy matplotlib

3. Run the notebook / script to perform analysis.
