# Single Machine Scheduling — Approximation Algorithms

## 📖 Overview

This project is a **web-based interactive visualization** of the **Single Machine Scheduling Problem** from Approximation Algorithms.

It demonstrates how different scheduling strategies affect job execution, completion time, and lateness using **real-time animations and metrics**.

The project is implemented as a **single-page application (HTML + CSS + JavaScript)** and deployed using Netlify with **auto-deploy enabled via GitHub integration**.

---

## 🌐 Live Demo

👉 Add your Netlify link here
Example:
`https://your-site-name.netlify.app`

---

## 🎯 Problem Description

In the **Single Machine Scheduling Problem**, we are given a set of jobs where:

* Only **one job can run at a time**
* Each job has:

  * Processing time (pⱼ)
  * Release time (rⱼ)
  * Due date (dⱼ)

The goal is to determine the **execution order** that optimizes performance metrics such as:

* Total Completion Time (ΣCⱼ)
* Flow Time (Fⱼ)
* Maximum Lateness (Lₘₐₓ)

---

## 🧠 Algorithms Implemented

### 1. FCFS (First Come First Serve)

* Jobs executed in order of arrival
* Simple and fair
* ❌ No approximation guarantee (can be very inefficient)

---

### 2. SPT (Shortest Processing Time)

* Chooses job with smallest processing time
* ✅ Minimizes total completion time (ΣCⱼ) when rⱼ = 0
* ⚠️ Heuristic when release dates exist

---

### 3. EDD (Earliest Due Date)

* Chooses job with earliest due date
* ✅ Minimizes maximum lateness (Lₘₐₓ)
* 📌 Proven **2-approximation** for certain cases

---

## ⚙️ Features

* 🎬 Interactive **Gantt chart visualization**
* 🔁 Dynamic algorithm switching (FCFS, SPT, EDD)
* 📊 Real-time metrics:

  * Flow Time
  * Maximum Lateness
  * Completion Time
* 🎲 Randomized job generation
* 📚 Integrated **theory + pseudocode + proofs**
* 🎨 Clean and modern UI

---

## 🖥️ Tech Stack

* HTML5
* CSS3 (custom styling)
* Vanilla JavaScript (no frameworks)

---

## 🚀 Deployment

This project is deployed using:

* GitHub Repository
* Netlify (Auto Deploy enabled)

### 🔁 Auto Deploy Workflow:

1. Push changes to GitHub
2. Netlify automatically rebuilds and redeploys
3. Live site updates instantly

---

## ▶️ How to Run Locally

```bash
Download or clone the repository
Open index.html in your browser
```

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

* Pinedo, M. — *Scheduling: Theory, Algorithms, and Systems*
* Vazirani, V. — *Approximation Algorithms*
* Lawler et al. — *Sequencing and Scheduling*
* Jackson (1955), Smith (1956)

---

## 👨‍💻 Author

Your Name

---

## 📌 Future Improvements

* Add more algorithms (WSPT, LPT, etc.)
* Multi-machine scheduling visualization
* User input for custom job sets
* Performance comparison graphs
* Backend integration for simulations

---

## ⭐ Project Highlights

* Combines **theory + visualization + interaction**
* Designed specifically for **Approximation Algorithms coursework**
* Helps in intuitive understanding of scheduling behavior

---
