# Power System Forecasting and Optimization Tool

## Overview

Traditional power system planning software primarily focuses on power flow analysis based on user-defined generation dispatches and demands. However, these tools often lack the ability to forecast generation and demand while simultaneously optimizing power flow under transmission system constraints.

This project aims to develop an integrated software solution that:
- **Forecasts generation and demand**
- **Optimizes power flow** to minimize the total system production cost
- **Respects transmission system constraints** for efficient and reliable planning

This innovative tool addresses the growing need for robust, integrated solutions across jurisdictions worldwide, enabling more efficient and optimal transmission system planning.

## Project Objectives

The primary goal of this project is to create a comprehensive software tool capable of:
- Forecasting **renewable generation dispatch** (e.g., wind and solar) and **system demand** using advanced machine learning techniques.
- Performing **Security-Constrained Optimal Power Flow (SCOPF)** to minimize total production costs while adhering to system constraints.

### Forecasting Methodology
- Developed using **Python**
- Utilizes machine learning algorithms such as:
  - Random Forest
  - Gradient Boosting
  - Neural Networks
- The model selection will be based on achieving the **lowest forecast error**.

### Optimization Model
- Built using **Python** and the **Gurobi Optimizer**
- Objective: Minimize total system production cost
- Constraints:
  - DC power flow equations
  - Line thermal rating constraints
- Integration with forecasting results to dynamically incorporate predicted renewable generation and demand data

### Key Features
- **Transmission system deficiency detection** by identifying limiting transmission lines causing congestion
- **Economic impact analysis** of congestion on system costs
- **Visual representation** through a single-line diagram, created using commercially or publicly available tools

---

## Installation Guide (For Team Members)

**Prerequisite:** Ensure you have **Anaconda** or **Miniconda** installed.

1. **Create a new environment:**
   ```bash
   conda create -n <env_name> python=3.9
   ```
2. **Activate the environment:**
   ```bash
   conda activate <env_name>
   ```
3. **Install required packages:**
   ```bash
   pip install -r requirements.txt
   ```

---

## Contribution Guidelines

### Pull Request Instructions
- Push updates to your feature branch.
- If you install a new package, update the `requirements.txt`:
  ```bash
  pip freeze > requirements.txt
  ```
- Push the updated `requirements.txt` to ensure team consistency.

---

## License
This project is for educational and research purposes.

---

## Contact
For questions or contributions, please contact the project maintainer.

