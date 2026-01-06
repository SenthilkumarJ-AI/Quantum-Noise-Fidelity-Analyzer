# ⚛️ Quantum Noise & Fidelity Analyzer

A **professional, UI/UX-driven quantum analysis framework** built using **Qiskit** to study the effects of quantum noise on single-qubit quantum states through fidelity metrics, measurement statistics, and Bloch sphere visualization.  
The tool is designed for **education, research, and rapid prototyping** in noise-aware quantum computing and is fully compatible with **Google Colab**.

---

## 📌 Overview

Quantum noise is one of the major challenges in near-term quantum devices.  
This project provides an **interactive, noise-aware simulation environment** that enables users to:

- Prepare arbitrary single-qubit quantum states  
- Introduce controllable depolarizing noise  
- Compare ideal and noisy measurement outcomes  
- Quantitatively evaluate **state fidelity**  
- Visually analyze quantum states using the **Bloch sphere**

The system emphasizes **clarity, reproducibility, and interactivity** without relying on external web frameworks.

---

## ✨ Key Features

- **Interactive UI/UX** using `ipywidgets`
- **Noise-aware quantum simulation** with Qiskit Aer
- **Depolarizing noise model** with adjustable strength
- **Ideal vs noisy measurement comparison**
- **Quantum state fidelity computation**
- **Bloch sphere visualization**
- **Single-cell, all-in-one Colab execution**
- No external UI frameworks (No Gradio / Streamlit)

---

## 🧠 Core Concepts Covered

- Quantum State Preparation (`RY`, `RZ`)
- Quantum Noise Modeling
- Depolarizing Error Channels
- Statevector and Density Matrix Formalism
- Quantum Measurement Statistics
- Fidelity as a Performance Metric
- Bloch Sphere Representation

---

## 🚀 Getting Started (Google Colab)

1. Open **Google Colab**
2. Upload the provided notebook
3. Run all cells (dependencies auto-install)
4. Use sliders to:
   - Configure quantum state parameters
   - Adjust noise strength
   - Select measurement shots
5. Click **Run Analysis** to visualize results

---

## 🛠 Dependencies

The following libraries are required (automatically installed in Colab):

- `qiskit`
- `qiskit-aer`
- `ipywidgets`
- `matplotlib`
- `pylatexenc`

---

## 📊 Output Visualizations

- Quantum circuit diagram
- Ideal vs noisy measurement histograms
- Fidelity score between ideal and noisy states
- Bloch sphere visualization of the ideal state

---

## 🎯 Use Cases

- Quantum Computing Education
- Noise Analysis in NISQ Devices
- Research Prototyping
- Benchmarking Quantum States
- Pre-validation of Quantum Algorithms

---

## 📂 Recommended Repository Structure

