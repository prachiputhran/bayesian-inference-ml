# Bayesian Inference for CTR Estimation

A hands-on implementation of Bayesian inference using the Beta-Binomial model to estimate click-through rate (CTR).

## 📌 Overview
This project demonstrates how Bayesian inference updates beliefs as data is observed.
Bayesian parameter estimation with conjugate priors, sequential updating, and prior sensitivity analysis using scipy.stats

We model:
- Prior beliefs using Beta distributions
- Likelihood using Binomial distribution
- Posterior using conjugate updates

## 🧠 Key Concepts
- Prior → Likelihood → Posterior
- Conjugate priors (Beta-Binomial)
- Credible intervals (uncertainty)
- Sequential Bayesian updating
- Prior sensitivity analysis

## 📊 Visualizations
The notebook generates:

- `prior.png` — different prior beliefs  
- `likelihood.png` — likelihood function  
- `bayesian_inference.png` — combined visualization  
- `sequential_update.png` — learning over time  
- `sensitivity.png` — effect of different priors  

## ⚙️ Tech Stack
- NumPy  
- SciPy  
- Matplotlib  
- Seaborn  

## ▶️ Run Locally
```bash
pip install -r requirements.txt
jupyter notebook bayesian_inference_ctr.ipynb