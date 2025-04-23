# 🧠 QCombDSL: A Domain-Specific Quantum Language for Combinatorial Problems

**QCombDSL** is a domain-specific programming framework designed for expressing, compiling, and solving classical combinatorial optimization problems—such as **MaxCut**, **Maximum Independent Set (MIS)**, and **TSP**—using quantum algorithms like **QAOA** and **Grover's algorithm**.

This project provides a high-level abstraction for problem modeling and execution using quantum circuits, with a modular, backend-agnostic architecture that currently supports **PennyLane** as the circuit and execution backend.

---

## 🎯 Key Features

- ✅ **Problem-centric DSL**: Express problems like MaxCut and MIS naturally via Python or YAML.
- ✅ **Automatic QUBO/Hamiltonian encoding**: Built-in encoders for graph-based combinatorial problems.
- ✅ **Cross-platform circuit execution (via PennyLane)**: Easily switch backends like Qiskit, Cirq, or AWS Braket.
- ✅ **QAOA support out of the box**: Use variational algorithms to explore quantum speedups.
- ✅ **Clean modular design**: Prepare to extend, visualize, and benchmark.

---

## 🧱 Architecture
