# 🌙 QIAS 2026 – Islamic Inheritance Reasoning

[QIAS 2026](https://sites.google.com/view/qias2026/) is the new edition of the **QIAS Shared Task** series, dedicated to evaluating Large Language Models (LLMs) in the domain of Islamic studies.
   
This edition focuses on **Islamic inheritance reasoning (ʿIlm al-Mawārīth)** through **realistic, end-to-end problem solving**, moving beyond multiple-choice evaluation toward full legal reasoning.

---

## 📖 Citation

If you use this dataset or code in your research, please cite:

```bibtex
@article{bouchekif2026mawarith,
  title={MAWARITH: A Dataset and Benchmark for Legal Inheritance Reasoning with LLMs},
  author={Bouchekif, Abdessalam and Gaben, Shahd and Rashwani, Samer and Eltanbouly, Somaya and Al-Khatib, Mutaz and Sbahi, Heba and Ghaly, Mohammed and Mohamed, Emad},
  journal={arXiv preprint arXiv:2603.07539},
  year={2026}
}
```




## 🧭 Background: From MCQs to Full Reasoning

In the previous edition ([QIAS 2025](https://https://sites.google.com/view/qias2025)), LLMs were evaluated using **multiple-choice questions (MCQs)** covering:
- Islamic inheritance reasoning
- General Islamic knowledge

Models selected **one correct answer among six options**, but were **not evaluated on**:
- The validity of their **intermediate reasoning**
- The correctness of the **jurisprudential justification**

---

## 🚀 What’s New in QIAS 2026

**QIAS 2026** introduces a **single, significantly more challenging task**:

> **End-to-end Islamic inheritance reasoning**

Instead of selecting an answer, models must:
- Explicitly generate **intermediate reasoning steps**
- Correctly **apply Islamic legal rules**
- Accurately **compute final inheritance shares**

This setup evaluates not only *what* the model answers, but *how* it reasons.

---

## 🧠 Task Description

### 🔍 End-to-End Islamic Inheritance Problem Solving

Given a **natural language description** of:
- An estate
- Surviving relatives

Systems are required to:

1. Identify **eligible and ineligible heirs**
2. Apply the **correct jurisprudential rules**
3. Compute the **exact numerical shares** according to Islamic inheritance law

This task mirrors **real-world inheritance problem solving** in Islamic jurisprudence.

---

## 🌍 Open & Inclusive Evaluation

QIAS 2026 places a strong emphasis on:
- Supporting **open-source Arabic LLMs**
- Encouraging **transparent and reproducible research**

At the same time, the shared task is **open to all approaches**, including:
- Commercial models
- Open-source models
- Prompting-based or trained systems

---
