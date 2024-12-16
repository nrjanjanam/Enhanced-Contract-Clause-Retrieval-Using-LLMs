# Enhanced Contract Clause Retrieval using Divide and Conquer Strategy with LLMs


---

## Problem Statement

Contract review is a critical yet resource-intensive task in legal operations. Manual review of lengthy contracts is time-consuming, expensive, and prone to human error. This research proposes an automated system leveraging Large Language Models (LLMs) to revolutionize contract analysis through efficient clause extraction and summarization.

The system addresses the fundamental challenge of processing lengthy legal documents with LLMs, which typically have limited context windows. By implementing a divide-and-conquer strategy, the system breaks down contracts into manageable chunks, processes them in parallel, and aggregates results. The approach ensures no clause mentions are missed, targeting near-perfect recall rates.

---

## Literature Survey

- **Zhou, Z., Li, C., Chen, X., Wang, S., Chao, Y., Li, Z., Wang, H., An, R., Shi, Q., Tan, Z., Han, X., Shi, X., Liu, Z., & Sun, M. (2024).** LLMMapReduce: Simplified Long-Sequence Processing using Large Language Models. *arXiv preprint arXiv:2410.09342*

- **Brown et al. (2020).** "Language Models are Few-Shot Learners," *NeurIPS* – Highlights the use of LLMs like GPT for contextual understanding and generation.

- **Bommarito et al. (2021).** "AI for Legal Document Review: A Case Study," *AI & Law Journal* – Explores applications of AI in legal contexts, including efficiency gains.

---

## Dataset Description

We will use a combination of publicly available legal datasets such as:

- **Kaggle ContractNLI** (link)  
- **EDGAR filings**

Supplemented with synthetic datasets generated from template-based contract clauses. These datasets contain labeled sections, clause types, and page-level annotations.

---

## Model Description

The project will evaluate transformer-based architectures like GPT-4 and Llama for their capability to process legal text. We aim to fine-tune these models for specific tasks such as:

- Clause extraction  
- Summarization  
- Query-based retrieval  

The system will integrate a pipeline for token-limited inputs.

---

## Objectives and Metrics

At the end of the project, we aim to deliver a functional pipeline that automates contract review, achieving:

- **High recall (>99%)** in clause extraction  
- **Low latency**  

This system aims to significantly reduce contract review time and costs while improving accuracy. The high-recall approach ensures comprehensive clause coverage, making it particularly valuable for high-stakes legal analysis where missing critical clauses could have significant consequences.
