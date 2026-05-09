# Build and Run Your First Quantum Program
# Work  in progress
## source : https://quantum.cloud.ibm.com/learning/en/courses/use-a-qc-today
# Use a quantum computer today

Hands-on IBM Quantum/Qiskit training material for learners who want to move from the basics of quantum computing to running their first quantum programs with Qiskit.

**Author:** Carlos Araque  
**Title:** IBM Qiskit Advocate  
**Research:** [KentryOps Quantum Research](https://kentryops.com/quantum-research)

## Course Overview

This repository contains a notebook-based learning path for building intuition, writing Qiskit circuits, running simulators, and preparing experiments for IBM Quantum systems.

The course introduces:

- Quantum computing context, scaling, error correction, and likely application areas
- Core quantum mechanics concepts used in quantum computing
- Bell state circuits and basic quantum circuit construction
- Qiskit workflows for creating, optimizing, executing, and post-processing circuits
- Simulator execution with `qiskit-aer`
- IBM Quantum Runtime workflows with `qiskit-ibm-runtime`
- A first quantum experiment using an Ising-system energy calculation

## Repository Contents

The course notebooks are in the [`Original`](Original) folder.

| Notebook | Focus |
| --- | --- |
| [`quantum-computing-context.ipynb`](Original/quantum-computing-context.ipynb) | Quantum computing applications, scaling challenges, error correction versus error mitigation, and core system components. |
| [`quantum-mechanics-basics.ipynb`](Original/quantum-mechanics-basics.ipynb) | Mathematical and physical ideas behind qubits, states, gates, and Bell-state circuits. |
| [`build-and-run-your-first-quantum-program.ipynb`](Original/build-and-run-your-first-quantum-program.ipynb) | A practical "Hello World" quantum circuit workflow using Qiskit, local simulation, and IBM Quantum execution. |
| [`your-first-quantum-experiment.ipynb`](Original/your-first-quantum-experiment.ipynb) | A guided experiment using Qiskit primitives to estimate the energy of a two-spin Ising system. |
| [`continue-your-learning-journey.ipynb`](Original/continue-your-learning-journey.ipynb) | Follow-up learning path and next steps. |

## Prerequisites

Recommended environment:

- Python 3.10 or later
- JupyterLab or Jupyter Notebook
- An IBM Quantum account for hardware/runtime execution

Install the core packages:

```bash
pip install qiskit qiskit-aer qiskit-ibm-runtime notebook
```

If you only want to run the simulator examples, an IBM Quantum account is not required. Hardware and IBM Runtime examples require valid IBM Quantum credentials.

## Getting Started

1. Clone or download this repository.
2. Create and activate a Python virtual environment.
3. Install the prerequisites listed above.
4. Start Jupyter:

```bash
jupyter notebook
```

5. Open the notebooks from the `Original` folder and work through them in order.

Suggested order:

1. `quantum-computing-context.ipynb`
2. `quantum-mechanics-basics.ipynb`
3. `build-and-run-your-first-quantum-program.ipynb`
4. `your-first-quantum-experiment.ipynb`
5. `continue-your-learning-journey.ipynb`

## IBM Quantum Setup

Some notebooks use `qiskit_ibm_runtime`. To run those sections on IBM Quantum services, save your IBM Quantum token in your local environment before running the runtime cells.

Refer to IBM Quantum Platform documentation for the current account setup and token-management workflow.

## Learning Outcomes

After completing the notebooks, learners should be able to:

- Explain where quantum computing is expected to be useful
- Describe the role of qubits, gates, circuits, measurement, and entanglement
- Build simple circuits with Qiskit
- Run circuits on a local simulator
- Understand the basic flow for running jobs through IBM Quantum Runtime
- Interpret measurement counts and estimator results from quantum experiments

## License and Attribution

This repository is intended for training and educational use. Review the source notebook material and any upstream IBM Quantum/Qiskit licensing requirements before redistributing modified course content.
