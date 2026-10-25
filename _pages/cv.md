---
layout: page
permalink: /cv/
title: CV
nav: true
nav_order: 5
description: Jie Tian's academic curriculum vitae, research, teaching, and technical background.
---

[LinkedIn](https://www.linkedin.com/in/jie-tian-061054360/) · [Google Scholar](https://scholar.google.com/citations?user=zmKIB4AAAAAJ) · [GitHub](https://github.com/jietinatian0803)

## Education

**University of Nevada, Reno** — Ph.D. student in Mathematics with a specialization in Applied Mathematics, August 2024–Present. Expected graduation: May 2028. GPA: 3.930/4.0.

Completed coursework and passed qualifying exams in Real/Functional Analysis, Linear/Numerical Linear Algebra, and Nonlinear Dynamics with High Pass. Dissertation research is ongoing.

**Shanghai University** — M.Sc. in Pure Mathematics, September 2021–June 2024. Average: 91.92/100.

**Hebei University of Science and Technology** — B.Sc. in Mathematics and Applied Mathematics, September 2017–June 2021. GPA: 3.8/4.0.

## Research Interests

- Matrix theory, quaternion algebra, and tensor computation
- Numerical and randomized linear algebra, low-rank approximation, and representation learning
- Convex optimization and computational methods on manifolds
- Inverse problems and uncertainty quantification
- Stochastic processes, discrete-time and continuous-time Markov chains, and time-series analysis
- Machine learning, LLM and agent post-training, knowledge distillation, and reinforcement learning

## Research Experience

### LLM and Agent Post-Training

**LLM and Agent Post-Training Research, University of Nevada, Reno** — September 2026–Present

- Independently design and implement experiments in knowledge distillation and LLM post-training, including supervised fine-tuning (SFT), reinforcement learning with verifiable rewards (RLVR), on-policy distillation (OPD), and self-distillation.
- Develop PyTorch/Transformers training and evaluation workflows with student rollout generation, frozen-teacher scoring, sampled-token teacher–student rewards, and clipped on-policy updates.
- Build reproducible experiment controllers for multi-GPU veRL configurations, including Hydra settings, checkpointing, validation schedules, run metadata, and log parsing.
- Develop diagnostics for GPU memory, training failures, reward/KL, top-k overlap, teacher–student consistency, entropy, gradients, timing, throughput, and task accuracy; extend studies toward agentic and function-calling settings.

### Mathematical and Computational Research

**Department of Mathematics and Statistics, University of Nevada, Reno** — August 2024–Present

**Quaternionic Upper Bild Convexity and Optimization**

Study the convexity and geometric structure of quaternionic numerical ranges through constrained real optimization and manifold methods. Develop boundary characterizations and computational validation for generic and degenerate matrix cases. Manuscript in preparation.

**FFT-Based Quaternion Tensor Decomposition, PCA, and ICA**

Develop FFT-based quaternion tensor decompositions and spectral methods for image and video data, preserving coupled color-channel structure. Investigate principal component analysis (PCA), independent component analysis (ICA), and multilinear discriminant analysis for dimensionality reduction and representation learning.

**EffLoRA: Memory-Efficient PiSSA Initialization for LoRA and QLoRA**

Developed checkpoint-backed, layer-wise and streaming PiSSA initialization from safetensors checkpoints, integrating randomized SVD, residual-checkpoint generation, and PEFT adapters.

- On Qwen3-8B with an RTX A6000, streaming reduced peak PyTorch GPU allocation during preparation from **15.9 GiB to 0.18 GiB**, with preparation times of **31 s versus 21 s** for the standard PEFT procedure. These measurements cover initialization, exclude the CUDA context, and do not describe training-peak memory.
- Verified bitwise-identical output between the layer-wise fast mode and standard PEFT PiSSA for the tested Qwen3 1.7B/4B/8B models and software stack.
- In a three-seed GSM8K fine-tuning experiment using Qwen3-1.7B with NF4 quantization, mean test accuracy was **54.3% for streaming QPiSSA versus 54.6% for PEFT QPiSSA**; these results do not establish statistical equivalence.

Code forthcoming. Related CSE27 presentation submitted; ongoing work on randomized low-rank initialization and memory-efficient fine-tuning workflows.

## Selected Course Projects

**Delay-Induced Oscillations in a Logistic–Allee Model with Harvesting** — Math 721, December 2025

Analyzed stability and Hopf bifurcation using Erlang-chain approximations; derived characteristic equations, computed critical delays, and studied convergence of the approximation.

**SEQIRS and SEIR–SEI Epidemic Models via the Generalized Linear Chain Trick** — Math 722, May 2026

Modeled phase-type disease-stage durations and derived the basic reproduction number using next-generation matrices, examining quarantine and host–vector transmission.

These projects support ongoing study of discrete-time and continuous-time Markov chains, transition matrices, generators, and absorption times, including connections between continuous-time Markov chains and Erlang/phase-type distributed delays.

## Publications and Presentations

Coauthor of three peer-reviewed papers in _Symmetry_ (2022), _Computational and Applied Mathematics_ (2024), and _Mathematics_ (2024). See the [publication list]({{ '/publications/' | relative_url }}) for full citations.

Invited talks at JMM 2025/2026 and ILAS 2026; contributed talk at the SIAM Annual Meeting 2026. See [Talks]({{ '/talks/' | relative_url }}).

**Upcoming invited talk:** “So–Thompson's Proof of Upper Bild Convexity via Convex Optimization,” ILAS–JMM Special Session on Matrix Analysis and Applications, Joint Mathematics Meetings, Chicago, January 12–15, 2027.

## Teaching and Service

**University of Nevada, Reno** — Graduate Teaching Assistant / Instructor of Record, August 2024–Present

**Fall 2026 — Instructor of Record, Math 120E: Fundamentals of College Mathematics (Expanded)** (4 credits; 4 instructional hours per week).

Independently develop course materials and lesson plans, design quizzes and examinations, assess student work, and provide academic support. Topics include sets and logic, probability and statistics, consumer mathematics, variation, geometry and trigonometry for measurement, and linear, quadratic, exponential, and logarithmic functions, emphasizing problem solving and applications.

Previous teaching includes Calculus I and II and Precalculus II. See [Teaching]({{ '/teaching/' | relative_url }}).

**Shanghai University** — Teaching Assistant, September 2021–June 2023.

**Vice President, SIAM Student Chapter, UNR** — January–May 2026. Organized academic lectures and research seminars and supported interdisciplinary networking.

## Technical Skills

- **Mathematical foundation:** Convex optimization, numerical and randomized linear algebra, and computational methods on manifolds.
- **Programming:** Python (PyTorch, Transformers, NumPy, SciPy, pandas), MATLAB, R, basic C; Git, Linux, and LaTeX.
- **Research infrastructure:** veRL, vLLM, FSDP, Ray, Hydra, multi-GPU experiment configuration, checkpointing, experiment logging, monitoring, and training diagnostics.
- **Methods:** Quaternion matrix/tensor algorithms, FFT, PCA/ICA, LoRA, stochastic processes, Markov chains, and phase-type distributions.

## Certifications

- IBM Data Science Professional Certificate
- IBM AI Engineering Professional Certificate
- IBM Generative AI Engineering Professional Certificate

## Scholarships and Selected Awards

- **Aydin Arman Ozbek Ph.D. Endowment — $500**, Department of Mathematics and Statistics, University of Nevada, Reno (June 2026)
- **Ben & Beatrice Edwards Math Award — $1,800**, Department of Mathematics and Statistics, University of Nevada, Reno (June 2026)
- **Outstanding Graduate Assistant Award — $500**, College of Science, University of Nevada, Reno (May 2026)
- Second-class University Scholarship (Top 15%), Shanghai University (2022–2023)
- Song Yuqi Scholarship, College of Science, Shanghai University (2022)
- First-class University Scholarship (Top 10%), Shanghai University (2021–2022)
- National Scholarship, China (2018–2019)
- First-class Scholarship (Rank 1/33), Hebei University of Science and Technology (2019–2020)

## Travel Grants and Conference Support

- **SIAM Annual Meeting 2026:** SIAM Travel Award, **$650**, Society for Industrial and Applied Mathematics.
- **ILAS 2026:** Departmental Travel Support, **$750**, University of Nevada, Reno; ILAS Early Career NSF Conference Grant Award, **$300**.
- **Joint Mathematics Meetings 2026:** Departmental Travel Support, **$750**, and Graduate Student Association Travel Grant, **$500**, University of Nevada, Reno.
- **Joint Mathematics Meetings 2025:** Departmental Travel Support, **$750**, and Graduate Student Association Travel Grant, **$500**, University of Nevada, Reno.

## Professional Experience

**Data Analyst Intern, Shanghai Jinghe Information Technology Co., Ltd.** — January–August 2021

Conducted data scraping, cleaning, and statistical analysis to support business decisions.
