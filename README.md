# Hi, I’m Suchita Kulkarni

 I am a machine learning engineer with a background in theoretical physics, focused on models that integrate structure, constraints, and domain knowledge into learning systems.

My work sits at the intersection of machine learning, dynamical systems, and scientific modeling, with an emphasis on robustness, interpretability, and generalisation.

---

## Core interests

- Physics-informed and structure-aware machine learning  
- Time-series modeling and dynamical systems  
- Generative models with inductive bias  
- Bridging scientific modeling and production ML

---

## Selected projects


### 🔹 Physics-Informed Time-Series Modeling and Anomaly Detection

Comparative study of physics-informed LSTM and purely data-driven LSTM models for oscillatory time-series analysis and anomaly detection.

The work favours physics-informed constraints to stabilise detection performance under stricter decision thresholds, trading raw flexibility for more consistent behaviour.

Focus: modeling assumptions, robustness, diagnostics
  
Implementation: LSTM architectures, physics-informed loss terms, threshold-based evaluation
  - [Code](https://github.com/suchitakulkarni/anomaly_classification)
  - [Streamlit interface exploring hyperparameter importance on a simpler signal](https://pinnlearning.streamlit.app/)
---
### 🔹 Digital surrogate for TCAD Semiconductor Device Simulator and framework for deployment criteria

A digital surrogate to explore semiconductor device characteristics across various device lengths and doping concentration for a 1D diode

The work establishes a deployment criteria for the surrogate, which depends on simulation complexity and surrogate inference time.
  
Implementation: PINN architectures, physics-informed loss terms
  - [Code](https://github.com/suchitakulkarni/DevSim_public)
---

### 🔹 Physics-Inspired protein conformations
Comparative study of physics-inspired VAE and purely data-driven VAE models for protein conformations 

The work shows that it is 3 times more likely to generate Lovell viable protein conformations in the Ramchandran plane. 
Implementation: VAE architectures, physics-inspired density landscape from Top500 dataset.
- [Code](https://github.com/suchitakulkarni/Ramchandran_dashboard)
- [Streamlit interface](https://github.com/suchitakulkarni/Ramchandran_dashboard)

---

### 🔹 Remaining Useful Life predictions on NASA turbofan dataset

Remaining useful life estimation on the NASA turbofan dataset under heterogeneous operating conditions, with explicit uncertainty quantification.

The model emphasises calibrated uncertainty over sharp point estimates, accepting wider intervals to reduce overconfident end-of-life failures.

Focus: uncertainty quantification, robustness, representation learning
  
Implementation: random forests, uncertainty calibration, hyperparameter optimisation
  - [Code](https://github.com/suchitakulkarni/NASA_RUL_Predictions)
---

### 🔹  Physics-Informed Latency Prediction and Anomaly Detection

Physics-aware anomaly detection for networked systems, where available data is sparse and reliable extrapolation is required.

The model prioritises physically meaningful anomalies over purely data-driven sensitivity, favouring stability and interpretability under limited observability.

Focus: interpretable modeling, robustness, uncertainty estimation
  
Implementation: linear regression, probabilistic anomaly detection
  - [Code](https://github.com/suchitakulkarni/Physics_informed_latenty_prediction)
  - [Streamlit interface](https://physics-informed-latency-pred.streamlit.app/)

---

## Background

- PhD and habilitation in theoretical physics  
- Experience leading research projects  
- Strong focus on principled modeling and clean software design

---

## Tools & stack

**Languages**
- Python (primary)
- Bash / shell scripting

**ML & scientific computing**
- PyTorch, NumPy, SciPy
- Custom Physics-informed ML frameworks

**Data & systems**
- Linux-based workflows
- Experiment tracking and reproducibility
- Version control with Git
 
---
## Contact

- GitHub: https://github.com/suchitakulkarni
- LinkedIn: https://www.linkedin.com/in/suchitakulkarni/
