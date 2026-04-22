# Tabu Search: Job Scheduling Optimization

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Algorithm](https://img.shields.io/badge/Algorithm-Tabu%20Search-brightgreen?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Completed-success?style=for-the-badge)

A Python implementation of the **Tabu Search** algorithm designed to solve a simple batch processing and job scheduling problem. 

This project was developed as an assignment for the *Optimization Algorithms* course at the **Università degli Studi di Brescia**. 

## About The Project

The goal of this repository is to demonstrate the effectiveness of heuristic algorithms in operations research. Specifically, it tackles a job scheduling problem using **Tabu Search**. 

To evaluate the algorithm's performance and accuracy, the absolute optimal solution for the scheduling problem was first computed using **Gurobi** (a mathematical optimization solver). The results from the Tabu Search were then compared against this exact Gurobi baseline to measure heuristic efficiency.

## Repository Structure

* **`Tabu_Search_exercise.py`**: The main Python script containing the logic for the Tabu Search implementation.
* **`TabuSearch_Exercise_Report.pdf`**: Comprehensive documentation detailing the homework assignment, the mathematical formulation, the algorithm's design, and a full analysis of the results.
* **`project_presentation.pdf`**: Presentation slides summarizing the project's methodology and findings.
* **`output.txt`**: Automatically generated textual output logging the steps and final results of the search process.
* **`tabu_search_progress.png`**: Automatically generated graph plotting the *Incumbent Solution* (best found so far) versus the *Current Solution* over the algorithm's iterations.

## Getting Started

### Prerequisites
To run the code, you will need Python installed on your machine, along with libraries commonly used for data visualization and numerical operations. 
* Python 3.x
* Required libraries (e.g., `matplotlib` for generating the progress graph). 

### Usage
1. Clone the repository:
   ```bash
   git clone [https://github.com/luca-pugnetti/Tabu_Search_Python.git](https://github.com/luca-pugnetti/Tabu_Search_Python.git)
