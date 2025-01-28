# Mean-Reverting Process Simulation

## Overview
This project simulates a **Mean-Reverting Process**, specifically an **Ornstein-Uhlenbeck process**, which is commonly used in financial modeling to represent asset prices that tend to revert to a long-term mean.

## Model Description
The **Ornstein-Uhlenbeck (OU) process** follows the stochastic differential equation:
\[
 dS_t = \theta (\mu - S_t) dt + \sigma dW_t
\]
where:
- \( S_t \) is the asset price at time \( t \)
- \( \theta \) is the speed of mean reversion
- \( \mu \) is the long-term mean level
- \( \sigma \) is the volatility
- \( dW_t \) represents a Wiener process (random noise)

## Implementation
The simulation is implemented in Python using **NumPy** and **Matplotlib**. The model generates multiple price paths and visualizes the mean-reverting behavior over time.

## Features
- Simulates multiple paths of a mean-reverting process.
- Adjustable parameters: \( \theta \), \( \mu \), \( \sigma \), time horizon, and time step.
- Visualizes asset price trajectories using Matplotlib.

## Installation
Clone this repository and ensure you have Python installed along with the required libraries:
```sh
pip install numpy matplotlib
```

## Usage
Run the script in a Jupyter Notebook or a Python environment:
```python
python mean_reverting_model.py
```

## Next Steps
- Extend the model to include **regime-switching behavior**.
- Compare performance with **Geometric Brownian Motion (GBM)** models.
- Apply the model to real financial data for calibration.

## License
This project is under the MIT License.

## Author
[Your Name]

