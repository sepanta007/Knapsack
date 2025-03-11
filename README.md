# Bounded Knapsack Problem Solver

## 📜 Description

This project implements a solution to the **Bounded Knapsack Problem**, where a set of items, each with a specific value, weight, and limited quantity, must be optimally packed into a knapsack with a given capacity to maximize total value.

## 📌 Problem Definition

Given:

- **Items Set:** A finite set of `n` items.
- **Item Properties:**
  - `v_i`: Value (profit) of item `i`.
  - `w_i`: Weight of item `i`.
  - `b_i`: Maximum number of times item `i` can be selected.
- **Knapsack Capacity:** A total weight limit `W`.

**Goal:** Find a combination of items that maximizes the total value while keeping the total weight within `W`.

## 🛠️ Features

- Implements a **dynamic programming** approach for optimal selection.
- Supports different item configurations with varying weights, values, and quantity limits.
- Includes **unit tests** to validate correctness.

## 📚 License

This project is licensed under the [MIT](https://github.com/sepanta007/Knapsack/blob/master/LICENSE) License.  
