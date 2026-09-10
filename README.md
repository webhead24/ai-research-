# 🧠 AI Research & Security Engineering: AI Fundamentals & Adversarial Analysis

A technical repository documenting applied research, threat vectors, model alignment, and hands-on lab implementations across foundational machine learning and modern Large Language Model (LLM) architectures.

---

## 📌 Mission & Research Focus

As machine learning systems transition from static, isolated classifiers into autonomous agents integrated into enterprise systems, securing the boundary between probabilistic outputs and deterministic code becomes critical.

This repository tracks research across the **AI Fundamentals** phase of the AI Security pathway, evaluating how core model mechanics dictate system vulnerability profiles:
* **Taxonomy & Architecture:** Mathematical feedback loops, deep neural networks, and self-attention transformers.
* **Adversarial Exploitation:** Direct and indirect prompt injection, data poisoning, model inversion, and evasion.
* **Data Integrity & Lineage:** Supply chain security, training set integrity, and embedding space dynamics.
* **Defensive Engineering & Alignment:** RLHF calibration, guardrail models, and digital forensics in AI environments (AI DFIR).

---

## 📚 Module 1: AI Fundamentals Roadmap

A breakdown of core competencies, research topics, and write-ups aligned with the TryHackMe AI Security pathway:

| # | Room / Topic | Core Technical Scope | Status |
| :---: | :--- | :--- | :---: |
| **01** | [The Building Blocks of AI](./01-the-building-blocks-of-ai.md) | ML Optimization loops, neural network topologies, transformer mechanics, NEURON-1 training | **Completed** ✅ |
| **02** | [AI Security Threats](./02-ai-security-threats.md) | Vulnerability surfaces, model manipulation, threat classification, evasion mechanics | **Completed** ✅ |
| **03** | [AI Models & Data](./03-ai-models-and-data.md) | Training pipeline integrity, data provenance, embedding space security, model lifecycle | **Completed** ✅ |
| **04** | [Prompt Engineering](./04-prompt-engineering.md) | Tokenization, contextual processing, system instructions, adversarial testing prompts | **Completed** ✅ |
| **05** | [AI Forensics](./05-ai-forensics.md) | AI-driven DFIR, forensic log analysis, artifact recovery, threat attribution | *In Progress* 🔄 |

---

## 🔬 Core Competencies & Methodologies

* **Machine Learning Mechanics:** Supervised, Unsupervised, Semi-Supervised, and Reinforcement Learning; Gradient Descent; Backpropagation; Attention Mechanisms.
* **Adversarial Threat Modeling:** Prompt Injections (Direct/Indirect), Jailbreaking, Model Poisoning, Adversarial Evasion.
* **Defensive Architecture:** Input/Output Sanitization, Guardrail Classifiers, Least-Privilege Agent Interfaces, Secure RAG Pipelines.
* **Framework Alignment:** OWASP Top 10 for LLMs, MITRE ATLAS, NIST AI Risk Management Framework (AI RMF).

---

## 📂 Repository Structure

```text
ai-research/
├── assets/                          # Architectural diagrams, terminal outputs, and lab validation
├── 01-the-building-blocks-of-ai.md  # Foundations of ML, Neural Networks & Transformers
├── 02-ai-security-threats.md        # Threat landscape and exploit mechanics
├── 03-ai-models-and-data.md         # Data pipeline security & model architectures
├── 04-prompt-engineering.md         # Adversarial prompt design & context handling
├── 05-ai-forensics.md               # DFIR investigations in AI environments
└── README.md                        # Portfolio overview & syllabus index
