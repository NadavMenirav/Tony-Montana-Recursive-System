# 🕶️ Tony Montana Recursive System

> "The world is yours... provided you can solve the recursion."

This repository contains a modular command-line interface (CLI) implemented in C. While the interface is designed as a criminal enterprise management system for a fictional "Boss," the underlying engine is a sophisticated demonstration of **deep recursion** and **mathematical optimization**.

## 🧠 Technical Highlights

This project demonstrates proficiency in several high-level Computer Science concepts:

* **Recursive Problem Solving:** Every task in the system is solved without iterative loops, demonstrating a strong grasp of the call stack, base cases, and recursive reduction.
* **Combinatorial Optimization:** Implementation of the **0/1 Knapsack Problem** logic to calculate optimal efficiency under constraints.
* **Pathfinding Logic:** Shortest-path calculation using recursive decision trees to find the "Optimal Escape Time" from a series of rooms.
* **Data Manipulation:** Recursive merging of sorted arrays and recursive string parity analysis.

---

## 🛠️ The System Modules

The "Tony Montana" system manages five distinct operational tasks via a central controller:

| Task Name | Algorithmic Focus | Description |
| :--- | :--- | :--- |
| **1. Merge Incomes** | **Sorted Merging** | Recursively merges two worker income arrays into a single sorted list. |
| **2. Symmetry Distance** | **String Analysis** | Calculates the "Palindrome Distance"—the number of mutations needed to reach symmetry. |
| **3. Gang Balance** | **Frequency Parity** | A recursive check to ensure 'Gang A' and 'Gang B' associations are perfectly balanced. |
| **4. Escape Route** | **Shortest Path** | Calculates the minimum steps to safety using recursive branching ($n/3$, $n/2$, or $n-1$). |
| **5. Heist Efficiency** | **0/1 Knapsack** | Finds the absolute optimal value of items that can fit within a limited weight capacity. |

---

## 🚀 Getting Started

### Prerequisites
* A C compiler (e.g., `gcc` or `clang`)

### Installation & Execution
1. **Clone the repository:**
   ```bash
   git clone [https://github.com/NadavMenirav/Tony-Montana-Recursive-System.git](https://github.com/NadavMenirav/Tony-Montana-Recursive-System.git)

2. **Compile the system:**
   gcc -o montana_system ex_3.c
   
3. **Run for the boss:**
   ./montana_system
