# Quantum Circuit Benchmarking: Performance of Qulacs vs PennyLane vs Qiskit

This repository contains performance benchmarking for **Quantum Neural Networks (QNNs)** using **Qulacs**, **PennyLane**, and **Qiskit** on different quantum simulators and backends. The primary goal is to compare the **execution times** of quantum circuits on **CPU** vs **GPU** setups, with varying qubit counts.

The benchmark compares:
- **Qulacs (CPU and GPU)**  
- **PennyLane (default.qubit and lightning.qubit)**  
- **Qiskit Aer (CPU and GPU)**

### 🚀 **Project Overview**

This benchmarking project evaluates the performance of quantum neural networks (QNNs) for different quantum simulators and backends using a **Variational Quantum Circuit (VQC)**. Execution time measurements are plotted for a variety of **quantum backends** in CPU and GPU configurations, providing insights into their relative performance.

The dataset includes results for different configurations with **6 to 18 qubits**, demonstrating **quantum circuit performance** in training steps (using the **parameter-shift rule** and **finite-difference gradients**).

### 🛠️ **Technologies & Tools Used**

- **Qulacs**: High-performance quantum circuit simulator (CPU & GPU support).
- **PennyLane**: Quantum machine learning library for building QNNs.
- **Qiskit**: Quantum computing framework with simulators for benchmarking.

### 📊 **Benchmark Results**

The following plots show the execution times for the different quantum simulators and backends across **multiple steps**:

1. **Qulacs CPU vs. GPU Performance**
2. **PennyLane (default.qubit and lightning.qubit) Performance**
3. **Comparison of Qulacs, PennyLane, and Qiskit on CPU & GPU**

### 📂 **Project Files**

- `benchmark_graph1.png`: Qulacs CPU vs Qulacs GPU
- `benchmark_graph2.png`: Qulacs CPU vs PennyLane CPU (default and lightning)
- `benchmark_graph3.png`: Qulacs CPU vs PennyLane CPU vs Qiskit CPU/GPU

### ⚙️ **How to Run**

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/quantum-circuit-benchmarking.git
   cd quantum-circuit-benchmarking
