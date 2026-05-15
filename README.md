# Prototype-Guided Multi-Task Learning for HCC Postoperative Complications Prediction

## 1. Background

The **PMCP (Prototype-guided Multi-task Complication Prediction)** framework is designed to address a critical challenge in clinical research: simultaneously predicting the holistic Comprehensive Complication Index (CCI) and specific severe complications (PHLF, PNA, PE, ASC) within the 24-hour postoperative window for hepatocellular carcinoma (HCC) patients.

## 2. Model Overview

The **PMCP** model is built upon a  adaptive fusion framework that effectively integrates **time-aware structured EHR data** with LLM-summarized clinical narratives via a Gated Cross-Attention mechanism. To overcome the extreme class imbalance inherent in severe complications, the model incorporates a **Dual-Prototype Mechanism**, selectively amplifying rare high-risk signals while maintaining clear feature space separation across tasks.

## 3. Supplementary Experiments and Materials

We have provided detailed supplementary materials to validate the clinical utility, robustness, and architectural design of the PMCP framework. These materials are included in our supplementary document, **PMCP_supplementary_materials.pdf**, which contains:
- **Baseline Characteristics:** Detailed statistical comparisons of the development and evaluation cohorts (Supplementary Text S1 & Table I).
- **Human-AI Collaboration Evaluation:** Extended analysis demonstrating the model's high capacity under data sparsity and its effectiveness as an AI assistant for clinicians in predicting pulmonary outcomes like PNA and PE (Supplementary Text S2 & Fig. S2).
- **Label Dependency Analysis:** A leave-one-out ablation study on auxiliary tasks to validate that the multi-task learning gains stem from comprehensive clinical modeling rather than shortcut learning (Supplementary Text S3 & Table II).
- **Prompt Templates:** The specific LLM prompt designs used for extracting standardized risk features from complex admission and surgical records (Fig. S1).

## 4. Contact Information

If you have any questions or would like to inquire further about the model, please feel free to contact us:

- **Email:** [peggy@buaa.edu.cn]
- **Institution:** [School of Computer Science and Engineering, Beihang University]

We welcome any feedback, contributions, or collaboration inquiries.
