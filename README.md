# Seismic Fragility Analysis of Atmospheric Storage Tanks

## 🎯 Project Overview

This project aims to develop a numerical framework for evaluating the seismic fragility of atmospheric storage tanks using probabilistic methods. It combines Monte Carlo simulations, Bayesian updating, and finite element modeling (via Abaqus) to estimate damage probabilities under varying ground motion parameters.

The final goal is to generate publishable results that contribute to the academic literature on structural reliability and risk assessment.

---

## 📁 Repository Structure

project-fragility-analysis/
├── README.md
├── docs/                  
│   ├── 00-outline.md
│   ├── 01-literature.md
│   ├── 02-methodology.md
│   ├── 03-weekly-log.md
├── src/                   # Python Codes
│   ├── monte_carlo.py
│   ├── bayes_update.py
├── abaqus/                # Abaqus Models
│   ├── model_1_static.inp
│   ├── model_1_results.odb 
├── figures/
├── .gitignore


---

## 🛠️ Tools & Technologies

- **Programming**: Python 3.10+, Jupyter, Pycharm
- **Modeling**: Abaqus (Windows environment)
- **Libraries**: `scipy`, `numpy`, `pymc`, `matplotlib`, `pandas`, `scikit-learn`,  `pytorch`
- **Documentation**: Markdown (.md)
- **Version control**: Git + GitHub
- **Backups** (optional): Google Drive for large output files

---

## 📌 Work Plan / TODO

- [ ] Literature summary (`docs/01-literature.md`)
- [ ] Define tank models and input parameters
- [ ] Implement Monte Carlo simulation module (`src/monte_carlo.py`)
- [ ] Abaqus modeling and sensitivity analysis
- [ ] Bayesian updating (`src/bayes_update.py`)
- [ ] Fragility curve fitting and plotting
- [ ] Prepare publication manuscript (`docs/05-paper-draft.md`)

---

## 🔄 Versioning & Contribution

This is a personal academic research project. External contributions are not expected at this stage, but feel free to browse or use the code for educational purposes.

---

## 📜 License

MIT License — feel free to reuse the code with attribution.
