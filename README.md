# Quantum Foundations: Circuits, Bits, and Logic

This repository contains a structured collection of Jupyter notebooks that build foundational understanding in both classical and quantum computing. Through practical Python-based simulations and mathematical representations, this project bridges digital logic, linear algebra, and quantum circuit principles.

---

## 📂 Notebooks Overview

| Filename                                   | Description |
|-------------------------------------------|-------------|
| `01_SampleCircuit.ipynb`                  | Introduces a basic quantum circuit using Qiskit, demonstrating how quantum gates form entangled states and how measurement collapses superposition. |
| `02_BinaryNumbers.ipynb`                  | Explores binary representation of integers and fractional numbers using Python’s built-in conversion functions. |
| `03_BooleanLogic.ipynb`                   | Demonstrates Boolean logic (AND, OR, XOR) using bitwise operations, highlighting their logical behavior and numeric interpretation. |
| `04_BitToVectors.ipynb`                   | Maps binary digits to column vectors and interprets logic gates as matrices acting on vectorized bit representations. |
| `05_ReversibleCircuits.ipynb`             | Constructs reversible classical logic gates (e.g., Toffoli) using Qiskit’s quantum circuit model, showing how classical logic can be modeled in a quantum framework. |
| `06_ProbabilisticBitsandCircuits.ipynb`   | Simulates probabilistic bits (p-bits) and multi-bit distributions, emphasizing the non-reversible nature of probabilistic logic and its deviation from classical determinism. |

---

## 🚀 Key Concepts Covered

### 🔢 Binary Logic & Arithmetic
- Manual and programmatic base-2 computations
- Bit manipulation and formatting
- Signed vs. unsigned representations

### ⚙️ Classical Logic Gates
- Implementation and behavior of basic gates (`AND`, `OR`, `XOR`, `NOT`)
- Binary truth tables and visual evaluation of logic
- Function-based abstraction of classical gate operations

### 🧠 Quantum Gates & Circuits (Qiskit)
- Quantum circuit construction with `QuantumCircuit` and `AerSimulator`
- Use of `Statevector` for Bloch sphere visualization
- Introduction to quantum parallelism and reversibility

### 🎲 Probabilistic Computing with p-bits
- Vectorized probability distributions for binary states
- Kronecker product modeling of multi-bit systems
- Empirical sampling and frequency convergence
- Discussion of non-reversibility in p-bit logic

---

## 🛠️ Technologies Used

- Python 3.13.5
- Qiskit
- NumPy
- SymPy
- Jupyter Notebook

Install dependencies via pip:

```bash
pip install qiskit numpy sympy matplotlib
```

## 🧪 How to Run

You can run each notebook in [Jupyter Notebook](https://jupyter.org/) or [JupyterLab](https://jupyterlab.readthedocs.io/):

```bash
jupyter notebook
```

Or execute in VSCode with the Jupyter extension.

---

## 📚 References

- [Quantum Computing]([https://qiskit.org/documentation/](https://learnquantum.io/))
- [Quantum Computing using Python]([https://www.cambridge.org/9781107002173](https://www.youtube.com/playlist?list=PLhI5X1mNN8giEspGNb39R1d7ik6RlSI7l))

---



