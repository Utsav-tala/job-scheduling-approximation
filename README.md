# 🎯 Single Machine Scheduling — Approximation Algorithms

## 📖 Overview

This project is an **interactive web-based visualization** of the **Single Machine Scheduling Problem**, a fundamental topic in Approximation Algorithms.

It demonstrates how different scheduling strategies affect:

* Job execution order
* Completion times
* Lateness and delays

The project combines **theoretical concepts, approximation guarantees, and real-time visualization** to provide an intuitive understanding of scheduling algorithms.

---

## 🌐 Live Demo

👉 https://scheduling-on-single-machine.netlify.app

---

## 🎯 Problem Description

In the **Single Machine Scheduling Problem**, we are given a set of jobs where:

* Only **one job can be processed at a time**
* Each job has:

  * **Processing time (pⱼ)**
  * **Release time (rⱼ)**
  * **Due date (dⱼ)**

### Objective:

Find an ordering of jobs that optimizes performance measures such as:

* Total Completion Time (ΣCⱼ)
* Flow Time (Fⱼ = Cⱼ − rⱼ)
* Maximum Lateness (Lₘₐₓ = max(Cⱼ − dⱼ))

---

## 🧠 Algorithms Implemented

### 🔹 FCFS — First Come First Serve

* Jobs are processed in order of arrival
* Simple and fair
* ❌ No approximation guarantee (can perform poorly)

---

### 🔹 SPT — Shortest Processing Time

* Selects job with minimum processing time
* ✅ Optimal for minimizing ΣCⱼ when rⱼ = 0
* ⚠️ Acts as a heuristic with release dates

---

### 🔹 EDD — Earliest Due Date

* Selects job with smallest due date
* ✅ Minimizes maximum lateness (Lₘₐₓ)
* 📌 Proven **2-approximation algorithm** for certain cases

---

## ⚙️ Features

* 🎬 Interactive **Gantt chart visualization**
* 🔁 Dynamic switching between algorithms (FCFS, SPT, EDD)
* 📊 Real-time metrics:

  * Flow Time
  * Maximum Lateness
  * Completion Time
* 🎲 Randomized job generation
* 📚 Integrated theory, pseudocode, and proofs
* 🎨 Clean and modern UI

---

## 🖥️ Tech Stack

* HTML5
* CSS3
* Vanilla JavaScript

---

## 🚀 Deployment

This project is deployed using:

* **GitHub Repository**
* **Netlify (Auto Deploy enabled)**

### 🔁 Auto Deploy Workflow

1. Code is pushed to GitHub
2. Netlify automatically builds and deploys
3. Live site updates instantly

---


## 📊 Key Concepts Covered

* Scheduling with Release Dates (1 | rⱼ | •)
* Greedy Algorithms
* Approximation Algorithms
* NP-hard Scheduling Problems
* Performance Metrics:

  * ΣCⱼ
  * Lₘₐₓ
  * Flow Time

---

## 📚 References

* Williamson, D. P., & Shmoys, D. B. (2011). *The Design of Approximation Algorithms*. Cambridge University Press.
* Pinedo, M. L. — *Scheduling: Theory, Algorithms, and Systems*
* Lawler, E. L. et al. — *Sequencing and Scheduling*

---

## 👨‍💻 Author

Your Name

---

## 📌 Future Improvements

* Add more algorithms (WSPT, LPT, etc.)
* Multi-machine scheduling visualization
* User input for custom job sets
* Performance comparison graphs
* Backend simulation support

---

## ⭐ Project Highlights

* Combines **theory + implementation + visualization**
* Designed for **Approximation Algorithms coursework**
* Helps build strong intuition for scheduling problems

---

> This project bridges the gap between theoretical analysis and practical understanding of scheduling algorithms.
