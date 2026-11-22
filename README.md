# Arabic Contract & Risk Analyzer

**Arabic NLP · LegalTech · Machine Learning · Document Intelligence**

An academic research prototype designed to analyze Saudi Arabic contracts, extract relevant clauses, and highlight provisions that may require further legal review.

**Status:** Functional Prototype — Research & Validation in Progress  
**Source Code:** Private / Not Included

## Project Overview

The project aims to make lengthy Arabic contracts easier to review by combining document processing, Arabic NLP, and explainable rule-based risk screening.

Rather than assigning a single risk score to an entire document, the prototype evaluates candidate clauses and presents relevant source text, page references, preliminary risk categories, and explanatory notes.

## Implemented Work

- Arabic PDF and DOCX text extraction, including OCR support.
- Arabic text preprocessing and clause-candidate segmentation.
- Preliminary risk rules covering penalties, termination, liabilities, and contractual obligations.
- Streamlit-based prototype with explainable Arabic reports.
- Export options for HTML, JSON, and CSV.
- Exploratory machine-learning baselines using TF-IDF and classical classifiers.

The latest project summary reports a collection of 14 Saudi Arabic contracts. An earlier documented data audit covered 12 PDF templates totaling 496 pages.

## Preliminary Research Results

An initial experiment using 30 weakly labeled examples reported:

| Metric | Result |
|---|---|
| Accuracy | 70% |
| Macro-F1 | 0.479 |
| HIGH Risk Recall | 0/3 |

These results are exploratory and do not establish reliable legal-risk classification. Independent expert-reviewed labels and stronger testing are still required.

## Current Research Focus

Improving annotation quality, preserving complete clause context, reducing data leakage between similar contract templates, and evaluating risk detection on independently reviewed documents.

## Academic Contribution

This is a three-member university project. Active development has been carried out primarily by Yasser Alassad and one teammate, with Yasser contributing substantially to the project.

Specific implementation contributions can be documented as they are confirmed.

## Disclaimer

This is a research-support prototype, not a legal advisory service. Preliminary risk indicators should not replace professional legal review.

## Developer

**Yasser Alassad**  
Computer Science — Artificial Intelligence Specialization  
Effat University

[GitHub](https://github.com/yasser1555) · [LinkedIn](https://www.linkedin.com/in/yasser-alassad/) · [Portfolio](https://yasser-alassad-portfolio.vercel.app/)
