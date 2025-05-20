# DEXA: Data Exploration via eXplanatory AI

**DEXA** (Data Exploration via eXplanatory AI) is a framework designed to translate natural language queries into safe, explainable, and executable code for dataset analysis (multimodal analysis). It leverages large language models (LLMs) alongside schema-aware prompt engineering to generate code, visualizations, and textual explanations of data.

DEXA supports both **zero-shot** and **few-shot** prompting modes, with a feedback loop for safety and interpretability. It has been evaluated on real-world datasets through both automated metrics (code execution) and human feedback using multiple LLMs (GPT-4, LLaMA-4).

---

## 📁 Repository Contents

| File | Description |
|------|-------------|
| `BostonHousing.csv` | Real-world dataset used for benchmarking (regression task). |
| `Titanic_Dataset.csv` | Real-world dataset used for benchmarking (statistics task). |
| `no_shot.ipynb` | Notebook implementing zero-shot prompting with DEXA. |
| `fewshot.ipynb` | Notebook implementing schema-guided few-shot prompting with DEXA. |
| `query_eval.csv` | Results from human evaluations across LLMs and prompting modes on both datasets. |
| `NLP Final Report DEXA.pdf` | Final report detailing methodology, experiments, and findings. |

---

## 🚀 Getting Started

1. Clone the repository:
2. Add OpenAI and Together.AI API in .env file
