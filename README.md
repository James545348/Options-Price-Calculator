# Black-Scholes Option Pricing Calculator

A Python implementation of the Black-Scholes model for European options pricing with Greeks calculation.

## Features
- Calculates call/put option prices
- Computes all major Greeks (Delta, Gamma, Vega, Theta, Rho)
- Interactive input prompts
- Clear output formatting
- 
## 📋 Requirements

### Core Dependencies
| Package | Version | Purpose |
|---------|---------|---------|
| [Python](https://www.python.org/) | 3.6+ | Base programming language |
| [NumPy](https://numpy.org/) | ≥1.20 | Mathematical operations |
| [SciPy](https://www.scipy.org/) | ≥1.7 | Statistical functions (norm.cdf/norm.pdf) |

### Development/Jupyter
| Package | Version | Purpose |
|---------|---------|---------|
| [Jupyter](https://jupyter.org/) | ≥1.0 | Interactive notebook environment |
| [matplotlib](https://matplotlib.org/) | ≥3.0 | (Optional) For visualization features |

### Installation
```bash
# Minimal installation (core functionality only)
pip install numpy scipy

# Full installation (including Jupyter for development)
pip install -r requirements.txt
## Usage
1. Run in Jupyter Notebook:
```python
calculate_option_price()
