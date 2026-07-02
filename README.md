# Single Machine Scheduling — Interactive Visualization of Approximation Algorithms

## Overview

This project is an interactive web-based visualization of the **Single Machine Scheduling Problem**, a fundamental topic in **Approximation Algorithms** and **Scheduling Theory**.

The application demonstrates how different scheduling strategies affect job execution order, completion times, flow times, and lateness. By combining theoretical concepts with real-time visualizations, the project provides an intuitive understanding of scheduling algorithms and their performance characteristics.

---

## Live Demo

**Website:** https://scheduling-on-single-machine.netlify.app

---

## Problem Description

In the **Single Machine Scheduling Problem**, a set of jobs must be scheduled on a single machine, where only one job can be processed at a time.

Each job \(J_j\) is defined by:

- **Processing Time** (\(p_j\))
- **Release Time** (\(r_j\))
- **Due Date** (\(d_j\))

### Objective

Determine a schedule that optimizes performance measures such as:

- **Total Completion Time**

  \[
  \sum C_j
  \]

- **Flow Time**

  \[
  F_j = C_j - r_j
  \]

- **Maximum Lateness**

  \[
  L_{\max} = \max(C_j - d_j)
  \]

---

## Algorithms Implemented

### FCFS (First Come First Serve)

Jobs are processed in the order of their arrival.

**Characteristics:**

- Simple and fair scheduling strategy
- Easy to implement
- No approximation guarantee and may lead to suboptimal schedules

---

### SPT (Shortest Processing Time)

Selects the available job with the minimum processing time.

**Characteristics:**

- Optimal for minimizing total completion time (\(\sum C_j\)) when all release times are zero
- Acts as a heuristic when release dates are present

---

### EDD (Earliest Due Date)

Schedules jobs according to the earliest due date.

**Characteristics:**

- Minimizes maximum lateness (\(L_{\max}\)) in the classical single-machine setting
- Serves as an effective approximation strategy in several scheduling variants

---

## Features

- Interactive Gantt chart visualization
- Dynamic switching between scheduling algorithms (FCFS, SPT, EDD)
- Real-time computation of scheduling metrics:
  - Completion Time
  - Flow Time
  - Maximum Lateness
- Randomized job generation for experimentation
- Integrated theoretical explanations, pseudocode, and proofs
- Clean and responsive user interface

---

## Technology Stack

- HTML5
- CSS3
- Vanilla JavaScript

---

## Key Concepts Covered

- Single Machine Scheduling with Release Dates \((1 \mid r_j \mid \cdot)\)
- Greedy Algorithms
- Approximation Algorithms
- NP-hard Scheduling Problems

### Performance Metrics

- Total Completion Time (\(\sum C_j\))
- Maximum Lateness (\(L_{\max}\))
- Flow Time

---

## References

1. Williamson, D. P., & Shmoys, D. B. *The Design of Approximation Algorithms*. Cambridge University Press, 2011.
2. Pinedo, M. L. *Scheduling: Theory, Algorithms, and Systems*.
3. Lawler, E. L., Lenstra, J. K., Rinnooy Kan, A. H. G., & Shmoys, D. B. *Sequencing and Scheduling: Algorithms and Complexity*.

---

## Future Improvements

- Add additional scheduling algorithms such as WSPT, LPT, and SRPT
- Extend the visualization to multi-machine scheduling environments
- Allow users to define custom job sets
- Include performance comparison graphs and analytics
- Add backend support for large-scale simulations

---

## Project Highlights

- Combines theoretical foundations with practical implementation
- Provides interactive visualization for better conceptual understanding
- Designed as an educational tool for Approximation Algorithms coursework
- Bridges the gap between algorithmic analysis and real-world scheduling behavior

