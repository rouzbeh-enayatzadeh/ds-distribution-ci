[![Shipping files](https://github.com/neuefische/ds-distribution-ci/actions/workflows/workflow-02.yml/badge.svg?branch=main&event=workflow_dispatch)](https://github.com/neuefische/ds-distribution-ci/actions/workflows/workflow-02.yml)
# 📊 Distribution and Confidence Intervals

In this repo we will dive deep into statistical concepts and advanced analytics techniques. You’ll explore distribution functions, and confidence intervals

---
## Distribution Functions 📈

In the folder [1_distribution](./1_distribution/) you will find guide notebooks and exercises to help you understand distribution functions.

- **Goal**: Learn to identify and apply different distribution functions to real-world data.

---

## Confidence Intervals 🔬⚖️

In the folder [2_confidence_intervals](./2_confidence_intervals/) you will find guide notebooks and exercises to help you understand confidence intervals.

- **Goal**: Develop the skills to calculate confidence intervals.

---

## 📚 Recommended Resources**

To further your learning, explore these resources and examples for each topic:  
- 📖 [Statistical Distributions – Wikipedia](https://en.wikipedia.org/wiki/Probability_distribution)  

---

## **🌟 Key Outcomes**
By the end of this repo, you will be able to:
1. **Understand and apply distribution functions** to model data.
2. **Calculate and interpret confidence intervals** and make data-driven decisions.

---
## Environment

### **`macOS`** type the following commands :

- Install the virtual environment and the required packages by following commands:

  ```BASH
  pyenv local 3.11.3
  python -m venv .venv
  source .venv/bin/activate
  pip install --upgrade pip
  pip install -r requirements.txt
  ```

### **`WindowsOS`** type the following commands :

- Install the virtual environment and the required packages by following commands.

  For `PowerShell` CLI :

  ```PowerShell
  pyenv local 3.11.3
  python -m venv .venv
  .venv\Scripts\Activate.ps1
  python -m pip install --upgrade pip
  pip install -r requirements.txt
  ```
  For `Git-Bash` CLI :

  ```
  pyenv local 3.11.3
  python -m venv .venv
  source .venv/Scripts/activate
  python -m pip install --upgrade pip
  pip install -r requirements.txt
  ```
