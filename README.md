# AI-Driven Test Case Generation: A Comparative Study

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![Research](https://img.shields.io/badge/Research-Master's%20Thesis-green.svg)](https://is.muni.cz/)
[![Institution](https://img.shields.io/badge/Institution-Masaryk%20University-red.svg)](https://www.muni.cz/)

> **A comprehensive empirical study comparing five generative AI models (ChatGPT, Microsoft Copilot, DeepSeek, Grok, Claude) with human testers for automated test case generation from software requirements.**

---

## 🔍 Overview

This repository contains experimental data and analysis results from a master's thesis investigating the capability of generative AI models to automatically generate test cases and test management plans from Software Requirements Specification (SRS) documents.

**Institution:** Masaryk University, Faculty of Informatics  
**Programme:** Software Systems Development  
**Year:** 2024-2025

### Research Questions

1. How accurately can generative AI models interpret SRS documents to produce valid test cases?
2. What are the differences in efficiency between AI-generated and human-written test cases?
3. How do AI-generated test cases compare to human-written ones in terms of coverage and bug detection?
4. What are the key challenges and limitations of using generative AI for test case generation?

---

## 🎯 Key Findings

### Overall Performance Rankings

**Phase 1: Initial Model Comparison**
1. **ChatGPT** - Best traceability and strong coverage
2. **Microsoft Copilot** - Excellent step-wise organization
3. **Claude AI** - Clear presentation
4. **Grok AI** - Readable but weaker performance
5. **DeepSeek** - Consistently weakest

**Phase 2: Advanced Evaluation**
- **Claude AI**: 91.20/100 (exceptional completeness and quality)
- **Microsoft Copilot**: 88.94/100 (highly competitive and precise)

**Phase 3: Claude AI vs Human Testers**

| Metric | Claude AI | Human | Difference |
|--------|-----------|-------|------------|
| **Accuracy** | **96.2%** | 92.8% | **+3.4%** |
| **Completeness** | 72.8% | **87.1%** | -14.3% |
| **RTM Coverage** | **100%** | 55% | **+45%** |
| **Efficiency** | **8-10× faster** | Baseline | **+800%** |

### Statistical Significance

- **p-value**: 0.012 (statistically significant)
- **Effect Size (Cohen's d)**: 1.01 (large positive effect)
- **Inter-rater Reliability (κ)**: 0.72 (substantial agreement)

### Key Insights

✅ **AI Strengths:**
- 8-10× faster than humans
- Perfect requirements traceability (100% RTM coverage)
- Higher accuracy (96.2% vs 92.8%)
- Systematic and measurable approach

❌ **AI Limitations:**
- Lower completeness (72.8% vs 87.1%)
- Weaker at interpreting ambiguous requirements
- Requires clear, well-documented specifications

🤝 **Recommended Approach:**
Hybrid model combining AI speed and accuracy with human contextual understanding achieves 96% accuracy, 95% coverage, and 8× efficiency gain.

---

## 🔬 Methodology

### Three-Phase Experimental Design

**Phase 1: Requirement Extraction** (7 experiments)
- Evaluated each model's ability to extract functional and non-functional requirements
- Input: SRS documents, user stories, use case diagrams
- Criteria: Coverage, Clarity, Traceability, Completeness

**Phase 2: Test Generation** (10 experiments)
- Compared test case generation quality
- Eliminated underperforming models
- Advanced Claude AI and Copilot to final phase

**Phase 3: Human vs AI** (15 experiments)
- Rigorous comparison of Claude AI vs human testers
- Double-blind human validation
- Statistical analysis (t-tests, Cohen's d, Kappa)

### Models Tested
- ChatGPT (GPT-4)
- Microsoft Copilot
- DeepSeek
- Grok (xAI)
- Claude AI (3.5 Sonnet)

---

## 📊 Experimental Data

**Total Experiments:** 32
- 7 requirement extraction experiments
- 10 Phase 1 test generation experiments
- 10 Phase 2 advanced comparison experiments
- 15 Phase 3 human vs AI experiments

**Data Formats:** JSON, DOCX, CSV, PDF, TXT, XLSX

---

## 📈 Results Summary

### Requirement Extraction

| Rank | Model | Score |
|------|-------|-------|
| 1 | **Claude AI** | 93.0/100 |
| 2 | **Microsoft Copilot** | 91.5/100 |
| 3 | **ChatGPT** | 87.0/100 |
| 4 | **DeepSeek** | 84.5/100 |
| 5 | **Grok AI** | 77.5/100 |

### Test Generation Quality

```
Claude AI:      ████████████████████████████████████ 91.20/100
MS Copilot:     ██████████████████████████████████   88.94/100
ChatGPT:        ████████████████████████             85.00/100
```

---

## 📝 Citation

If you use this research or data in your work, please cite:

```bibtex
@mastersthesis{basit2025ai,
  author  = {Basit, Abdul},
  title   = {A Comparative Study of Automated and Manual Creation of 
             Test Management Plans and Test Cases},
  school  = {Masaryk University, Faculty of Informatics},
  year    = {2025},
  address = {Brno, Czech Republic},
  url     = {https://github.com/abdulawr/AI-Driven-Test-Case-Generation-A-Comparative-Study}
}
```

---

## 📜 License

This project is licensed under the MIT License.

**Data Usage:**
- ✅ Academic research and education
- ✅ Replication studies
- ✅ AI model evaluation and benchmarking

**Attribution required when using this data.**

---

## 🤝 Contributing

Contributions, suggestions, and feedback are welcome via GitHub Issues and Pull Requests.

---

## 🙏 Acknowledgements

Thanks to Masaryk University Faculty of Informatics for research support, and to all participating AI platforms and human testers.

---

**© 2024-2025 Abdul Basit, Masaryk University**  
*Master's Thesis in Software Systems Development*