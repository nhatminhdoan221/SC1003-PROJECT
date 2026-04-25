# Student Group Distribution Optimizer

## Project Overview
This repository serves as a technical showcase for an algorithmic optimization project developed during the SC1003 Mini-Project. The project automates the distribution of 6,000+ students into balanced teams based on specific academic criteria without the use of third-party libraries (pure Python implementation).

* **Note on Dataset:** The dataset provided in this repository is a **simulated test case** designed to represent the scale and complexity of the original assignment, ensuring the functionality of the algorithm is demonstrable while maintaining data privacy.
* **Note on Privacy:** This codebase contains my personal contribution. Team member identities have been anonymized to respect privacy standards.

## Project Files
* [View Source Code & Logic (Jupyter Notebook)](https://github.com/nhatminhdoan221/SC1003-PROJECT/blob/main/SC1003_Mini_Project.ipynb)

## Key Technical Implementation
* **Language:** Pure Python 3.x
* **Architecture:** Zero-dependency implementation (no Pandas or NumPy).
* **Data Structures:** Custom-defined objects, standard lists, and dictionaries for efficient memory management.
* **Performance:** Optimized logic to process 6,000+ data points effectively while adhering to strict algorithmic constraints.

## Algorithmic Approach
* **Parsing:** Custom file I/O for data ingestion and normalization.
* **Sorting:** Custom sorting logic to organize students into academic tiers.
* **Distribution:** Nested-loop assignment engine featuring a `validate_diversity()` function to enforce constraints before finalizing groups.
* **Validation:** Custom functions for quantitative metrics:
  $$\text{Variance} = \frac{\sum (x - \mu)^2}{n}$$

## Performance Metrics
* **Diversity:** Achieved 99.3% faculty representation across groups.
* **Equity:** Minimized average CGPA variance to 0.02/5.0.
* **Reliability:** Successfully enforced gender balance (2-3 members per group) using a robust constraint-checking loop.

---
*Developed by Doan Nhat Minh - Computer Engineering, NTU.*
