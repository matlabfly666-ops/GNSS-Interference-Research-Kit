# GNSS Interference Research Kit (GIRK)

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue?logo=python)](https://www.python.org/)
[![License](https://img.shields.io/github/license/Ryker-Fly/GNSS-Interference-Research-Kit)](./LICENSE)

A Python toolkit for simulating and mitigating GNSS (Global Navigation Satellite System) interference, including single-tone, narrowband interference generation, and advanced mitigation techniques such as FDPB (Frequency Domain Pulse Blanking) and IIR notch filters.

Designed for researchers and engineers working on GNSS signal integrity, this package provides modular, well-documented components to accelerate interference analysis and countermeasure development.

---

## 📦 Features

- **Interference Generation**:
  - Single-tone interference
  - Narrowband interference with configurable bandwidth and center frequency
- **Mitigation Algorithms**:
  - FDPB (Frequency Domain Pulse Blanking)
  - IIR Notch filter-based mitigation
- **Ready-to-Run Examples**:
  - Jupyter Notebooks for interactive exploration
  - Standalone Python scripts for automation
- **Modular Design**:
  - Clean separation between signal generation, interference injection, and mitigation
  - Easy to extend with new interference types or algorithms

---

## 🚀 Installation

### Prerequisites
- Python 3.8 or higher
- `git` (to clone the repository)

### Steps
```bash
# Clone the repository
git clone https://github.com/Ryker-Fly/GNSS-Interference-Research-Kit.git
cd GNSS-Interference-Research-Kit

# Create and activate a virtual environment (recommended)
python -m venv venv
source venv/bin/activate      # Linux/macOS
# or
venv\Scripts\activate        # Windows

# Install the package in editable mode
pip install -e .
