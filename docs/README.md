*This project has been created as part of the 42 curriculum by ravazque.*

---

## Description

ftl_quantum is an introduction to **quantum programming** with Python and Qiskit. Five exercises scale from manipulating a single qubit to implementing a full quantum search algorithm, running both on a local simulator and on real IBM quantum hardware:

- **Superposition** — put a qubit into `1/√2(|0⟩ + |1⟩)` with a Hadamard gate and measure it over 500 shots.
- **Entanglement** — build the Bell state `1/√2(|00⟩ + |11⟩)` with Hadamard + CNOT.
- **Quantum noise** — run the same entangled circuit on a real quantum computer and analyze why the results differ from the simulator (noise and decoherence).
- **Deutsch-Jozsa** — decide whether an unknown oracle is constant or balanced with a single query.
- **Search (Grover)** — a generic Grover implementation (initialization + oracle + diffuser) that works for any number of qubits, with O(√N) complexity.

Every algorithm is implemented by hand; no library function solves the problem on its own. Dependencies are listed in `requirements.txt`.
