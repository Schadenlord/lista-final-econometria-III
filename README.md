# Final Problem Set – Econometria III (UDESC/ESAG)

This repository contains my solutions to the final problem set for **Econometria III (63ECON2)**, a core subject in the Economics undergraduate curriculum at **Universidade do Estado de Santa Catarina (UDESC/ESAG)**. The material here directly reflects the technical and theoretical rigor demanded by the course, and presupposes that the reader is either already versed in, or actively studying, advanced econometric methods as outlined in the syllabus below.

> **NOTE:** All code, analysis, and discussion presume a high level of familiarity with intermediate-to-advanced econometrics, including panel data, simultaneous equations, causal inference, and limited dependent variable models. This repository was developed as part of coursework and assessment for the 6th semester of the Economics program, under the instruction of Prof. Rafael Felipe Bressan.

---

## 📚 Context

- **Course**: Ciências Econômicas – Econometria III (63ECON2)
- **Department**: Ciências Econômicas, UDESC/ESAG
- **Semester**: 2025.1 (6th term)
- **Professor**: Rafael Felipe Bressan ([rafael.bressan@edu.udesc.br](mailto:rafael.bressan@edu.udesc.br))
- **Work type**: Final problem set / Lista final de exercícios (individual assessment)
- **Presumed audience**: Students and researchers with solid background in econometric theory and applied methods

---

## 🧠 Theoretical and Technical Scope

This repository addresses, in a practical and technical manner, the principal topics from the **Econometria III** syllabus, with all code and solutions written in Python (Jupyter Notebook). The exercises cover:

- **Panel Data Regression Models**: Fixed effects, random effects, intra- and inter-group variation, heterogeneity bias, and model selection (e.g., Hausman test).
- **Simultaneous Equations Models**: Identification (order and rank conditions), indirect least squares, instrumental variables (IV), Two-Stage Least Squares (2SLS), and tests for endogeneity and overidentification.
- **Causal Inference**: Rubin’s potential outcomes framework, difference-in-differences (DID, including staggered adoption), construction of treatment/control groups, and bias diagnostics.
- **Qualitative Choice Models**: Linear Probability Model (LPM), Logit, Probit, maximum likelihood estimation, interpretation of marginal effects (at the mean and average marginal effects), and model fit.
- **Generalized Method of Moments (GMM)**: Estimation and application in settings with endogeneity and overidentification.
- **Robustness and Diagnostics**: Heteroskedasticity, autocorrelation, robust standard errors, RESET and specification tests, residual analysis.
- **Python for Econometrics**: All computational work is conducted using Python, leveraging modern scientific and econometric libraries.

---

## 🗂️ Repository Structure

- `<Problem_Set_Solutions>.ipynb`: Jupyter Notebook containing all code, technical derivations, results, and commentary.
- `<Supporting_Document>.tex` (optional): LaTeX source for any mathematically formal appendices or formatted write-ups.

*File names may vary; consult the actual repository contents for specifics.*

---

## 🚀 Usage

### 1. Clone the Repository

```bash
git clone https://github.com/Schadenlord/lista-final-econometria-III.git
cd lista-final-econometria-III
```

### 2. Run the Notebook

Open the main `.ipynb` file with [JupyterLab](https://jupyter.org/), [Jupyter Notebook](https://jupyter.org/), or [VS Code](https://code.visualstudio.com/).

- Each section addresses a defined econometric challenge, with:
  - Data input and cleaning (`pandas`, `numpy`)
  - Model estimation and inference (`statsmodels`, custom implementations)
  - Specialized econometric procedures (fixed/random effects, IV/2SLS, Probit/Logit, GMM, etc.)
  - Statistical testing and model diagnostics (robust errors, Hausman, RESET, LM, etc.)
  - Visualization (`matplotlib`, `seaborn`)
  - Technical discussion with references to theory and interpretation

If included, compile `.tex` files for mathematical derivations or formatted documentation.

---

## ⚙️ Python Environment and Libraries

- Python 3.x
- [`pandas`](https://pandas.pydata.org/) (data handling)
- [`numpy`](https://numpy.org/) (numerics)
- [`statsmodels`](https://www.statsmodels.org/) (econometric estimation, diagnostics)
- [`matplotlib`](https://matplotlib.org/) & [`seaborn`](https://seaborn.pydata.org/) (visualization)
- [`notebook`](https://jupyter.org/), [`jupyterlab`](https://jupyter.org/) (interactive analysis)
- LaTeX (optional, for compiling supporting documents)

Install the main requirements with:
```bash
pip install pandas numpy statsmodels matplotlib seaborn notebook
```

---

## 📑 Course Syllabus Reference

This repository was developed for and is closely aligned with the content of **Econometria III (63ECON2)** as offered at UDESC/ESAG. Principal topics:

- Causal inference and Rubin’s framework
- Simultaneous equations, identification, IV, and 2SLS
- Panel data: fixed/random effects, heterogeneity, DID
- Qualitative choice models: LPM, Logit, Probit, MLE, marginal effects
- GMM estimation
- Applied data analysis with Python

For full details, see the official [course syllabus](https://www.udesc.br/esag) and the reference bibliography below.

---

## 📖 Core References

- Wooldridge, J. M. *Introdução à Econometria* (Cengage, 2016)
- Gujarati, D. & Porter, D. *Econometria Básica* (Amgh, 2011)
- Gertler, P. et al. *Avaliação de Impacto na Prática* (Banco Mundial, 2018)
- Cunningham, S. *Causal Inference: The Mixtape* (Yale, 2021)
- Angrist, J. & Pischke, J.-S. *Mostly Harmless Econometrics*, *Mastering’Metrics*
- Hansen, B. E. *Econometrics* (2020, manuscript)
- Python econometrics: Sheppard, Sargent & Stachurski, QuantEcon lectures

---

## 📜 License & Academic Use

This repository is for academic and educational purposes only.  
If you use or adapt any part of this material, please provide appropriate attribution and respect the original bibliographic references.

---

## 💬 Contact

For technical or academic questions, open an issue or contact via GitHub.

---
