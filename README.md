# M.Sc-Dissertation
The repository contains my Dissertation that I worked on during my Master of Science in Mathematics with a specialization in Computer Science final year.

Items in the respository:
1. Presentations (Folder)
   1. Presentation on Transformers Architecture.
   2. Presentation on Bert Base uncased model.
   3. Presentation of the whole project - BERT Base Uncased Inference Workload     Characterization and Microarchitectural Exploration on Intel Skylake Processor.
2. Thesis (Folder)
    1. Thesis of the whole project - BERT Base Uncased Inference Workload     Characterization and Microarchitectural Exploration on Intel Skylake Processor.
3. Papers that I studied (Folder)

Inforamation regarding the Project:
This project focuses on the micro-architectural characterization of transformer-based deep learning models, specifically the BERT-base uncased model, running on an Intel Core Skylake CPU. The goal is to analyze and understand how such models perform at the micro-architectural level and identify opportunities for optimization and efficiency improvements.

We begin by exploring the fundamentals of transformer models and their computational demands. Recognizing that CPUs are still widely used for deep learning inference, particularly in resource-constrained or latency-sensitive environments, we aim to understand how efficiently transformer models operate on modern CPU architectures.

The project involves setting up a suitable environment with the necessary deep learning libraries and Intel VTune Profiler for performance analysis. A top-down performance analysis approach is employed to inspect the behavior of the model during inference and identify critical bottlenecks.

Through hotspot analysis and micro-architectural profiling, we pinpoint the functions and hardware components that limit performance. The study culminates in proposing a theoretical hardware enhancement—adding an execution port to address the identified bottleneck, thereby improving the overall efficiency of transformer inference on CPUs.

This research not only illuminates the interaction between transformer models and CPU hardware but also provides insights into optimizing deep learning workloads on general-purpose processors.

