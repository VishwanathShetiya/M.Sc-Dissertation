# 🧠 M.Sc Dissertation – BERT Inference Microarchitectural Exploration

This repository contains the dissertation work completed during my **Master of Science in Mathematics with a specialization in Computer Science**. The project focuses on the **microarchitectural characterization and optimization of transformer-based deep learning (DL) models**, specifically the **BERT Base Uncased** model, on an **Intel Skylake CPU** using **PyTorch**.

---

## 📁 Repository Structure

- [Presentations](./Presentations/)
  - [Transformers Architecture](./Presentations/Transformers_Architecture.pdf)
  - [BERT Base Uncased Model](./Presentations/BERT_Base_Uncased_Model.pdf)
  - [Final Project Presentation](./Presentations/Final_Project_Presentation.pdf)
- [Thesis](./Thesis/)
  - [Final Thesis Document](./Thesis/Thesis.pdf)
- [Papers that I Studied](./Papers_that_I_Studied/)


## 🧾 Project Overview

This project investigates the **microarchitectural behavior of transformer-based DL models**—a key class of models in modern **machine learning (ML)**—by profiling the **BERT Base Uncased** inference workload on an **Intel Skylake CPU**. The goal is to understand how efficiently these models execute on general-purpose processors and identify performance bottlenecks at the hardware level.

---

## 🔍 Key Objectives

- Explore computational patterns and resource usage of transformer DL models in ML workloads.
- Profile the inference performance of BERT Base Uncased on Intel Skylake using **PyTorch**.
- Apply **Intel VTune Profiler** with a **top-down microarchitectural analysis** methodology to identify CPU pipeline bottlenecks.
- Pinpoint hotspot functions and inefficient hardware resource utilization impacting DL inference performance.

---

## 🛠️ Tools & Methodology

- **PyTorch** deep learning framework
- **Intel VTune Profiler** for microarchitectural performance profiling
- **Top-down analysis methodology** to analyze CPU resource usage
- Intel Core **Skylake** microarchitecture as the hardware platform

---

## 📈 Findings & Contribution

- Discovered critical microarchitectural bottlenecks limiting BERT inference performance on Skylake CPUs.
- Proposed a theoretical hardware enhancement—adding an **execution port**—to improve throughput and efficiency.
- Provided insights into optimizing transformer DL workloads on CPU architectures widely used in latency-sensitive or resource-constrained ML applications.

---

## 🧩 Significance

This research deepens the understanding of DL and ML workloads on CPU architectures, offering valuable guidance for:

- Hardware-aware optimization of ML inference
- Performance tuning of transformer models in CPU environments
- Future CPU microarchitecture enhancements tailored for DL workloads
