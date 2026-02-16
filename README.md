# Emerging Technologies - Quantum Algorithms

Coursework exploring classical vs quantum computing approaches to the Deutsch-Jozsa problem.

## Setup

0. Prerequisites:
- Python 3.8^

1. Clone the repository:
```bash
git clone https://github.com/EricMurray-e-m-dev/emerging_tech.git
cd emerging_tech
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```


3. Run the notebook:
```bash
jupyter notebook problems.ipynb
```

## The Problems

**Problem 1: Generating Random Boolean Functions**  
Implements a Python function generator that creates random Boolean functions guaranteed to be either constant (always return the same value) or balanced (return True for exactly half the inputs). These functions serve as test cases for the quantum algorithm.

**Problem 2: Classical Testing for Function Type**  
Develops a classical algorithm to determine whether a mystery Boolean function is constant or balanced by querying it with different inputs. Analyzes the query complexity (worst case: 9 queries for 4-bit functions) to establish a baseline for quantum comparison.


### About
Module: Emerging Technologies  
Author: Eric Murray - G00423903