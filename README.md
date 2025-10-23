# Stochastic Process Simulation

A Python simulation and visualization of a stationary stochastic process with random lognormal amplitude and uniformly distributed phase.

---

## 📊 Overview

The simulated process is defined as:

\[
X(t) = A \cdot \cos(2\pi f_0 t + \phi)
\]

where:

- \( A \) is a **lognormally distributed amplitude** with mean `A_mean` and variance `sigma_squared`.
- \( \phi \) is a **uniformly distributed random phase** in \([0, 2\pi]\).
- \( f_0 \) is the **frequency** of the process.

The script:
- Generates multiple realizations of the process.
- Computes and plots the **ensemble mean**, **variance**, and **covariance function**.
- Visualizes sample realizations to demonstrate the stationary nature of the process.

---

## ⚙️ Features

- Simulates multiple realizations of a stationary stochastic process.
- Plots realizations, mean, and variance envelopes.
- Computes and visualizes the covariance function.
- Uses simple and efficient NumPy and Matplotlib-based implementation.

---

## ▶️ Usage

Clone the repository and run the simulation script:

```bash
git clone https://github.com/<your-username>/stochastic-process-simulation.git
cd stochastic-process-simulation
python stochastic_process_simulation.py

## 📁 File Structure

stochastic-process-simulation/
│
├── stochastic_process_simulation.py # Main simulation script
├── README.md # Documentation
└── requirements.txt # Dependencies (optional)
## ▶️ Usage

Clone the repository and run the simulation script:

```bash
git clone https://github.com/<your-username>/stochastic-process-simulation.git
cd stochastic-process-simulation


python stochastic_process_simulation.py

---

### ⚙️ **Requirements**
- Lists the Python packages people need before running the script.
- Prevents “module not found” errors.

## ▶️ Usage

Clone the repository and run the simulation script:

```bash
git clone https://github.com/<your-username>/stochastic-process-simulation.git
cd stochastic-process-simulation
python stochastic_process_simulation.py

---

### ⚙️ **Requirements**
- Lists the Python packages people need before running the script.
- Prevents “module not found” errors.


```
## 📦 Requirements

Make sure you have the following Python packages installed:

```bash
pip install numpy matplotlib


open and run the notebook directly via Colab: Open in Colab
