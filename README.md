# McCulloch-Pitts Neuron: AND & OR Gates

## Description
This project implements the McCulloch-Pitts (MP) Neuron model in Python to simulate fundamental logic gates: **AND** and **OR**.

Per the assignment requirements, this implementation uses the **summation of inputs** method (without distinct weights) to determine the output based on a specific threshold.

## How It Works
The MP Neuron works by summing the binary inputs ($x_1, x_2$) and comparing the total against a Threshold ($\theta$).
- **Formula:** If $(x_1 + x_2) \ge \theta$, Output is 1. Otherwise, Output is 0.

### Logic Configuration
1. **AND Gate:**
   - Threshold ($\theta$) = 2
   - The neuron fires only when both inputs are 1 ($1+1=2$).

2. **OR Gate:**
   - Threshold ($\theta$) = 1
   - The neuron fires if at least one input is 1 ($0+1=1$ or $1+1=2$).

## Requirements
* Python 3.x

## How to Run
1. Save the code in a file named `mp_neuron.py`.
2. Open your terminal or command prompt.
3. Run the following command:
   ```bash
   python mp_neuron.py
