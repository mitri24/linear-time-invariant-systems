# Linear Time-Invariant Systems
## Lab 4 – Technical Foundations of Artificial Intelligence

This lab explores **Linear Time-Invariant (LTI) Systems** in two parts:

- **Part 1**: We perform **system identification** using a simulated RLC series circuit.
- **Part 2**: We implement **FFT filters** to build a digital crossover filter.

---

## Part 1: Simulating an RLC Series Circuit

An RLC series circuit consists of three components in series:

- **Resistor (R)** – resistance (ohmic)
- **Inductor (L)** – inductance
- **Capacitor (C)** – capacitance

### Circuit Description

The input signal is a time-varying voltage (as indicated by the +/- symbol). The **output signal** is the voltage across the capacitor, measured at its terminals. Such circuits are commonly used as **oscillators** or **filters** in radio and communication technology.

### Simulation Objective

We simulate the circuit for a duration of **10 ms**, with the input voltage defined via a Python function `input_voltage(t)`.

---

##  Dependencies

- Python 3.x
- NumPy
- SciPy
- Matplotlib

Install required packages via pip:

pip install numpy scipy matplotlib
