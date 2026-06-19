# Incremental Stability and Cognitive Load in Natural Language

A computational framework for analyzing cross-linguistic word-order patterns through syntactic stability and cognitive processing dynamics.

---

## Overview

Natural languages exhibit recurring word-order patterns such as SVO, SOV, and VSO. This project investigates these patterns from a computational perspective by introducing quantitative measures of structural stability and cognitive load during incremental sentence processing.

The framework combines dependency parsing, prefix-tree analysis, feature engineering, and statistical modeling to study language structure across multiple typologically distinct languages.

---

## Research Objectives

- Quantify syntactic organization using interpretable computational metrics.
- Analyze cognitive load associated with dependency resolution.
- Compare structural properties across different language families.
- Recover known typological hierarchies using data-driven methods.
- Evaluate whether proposed metrics align with language-processing performance.

---

## Methodology

### Dataset

The study evaluates six typologically distinct languages:

- English
- German
- Finnish
- Korean
- Japanese
- Arabic

### Framework Components

- Dependency Parsing
- Prefix-Tree Construction
- Incremental Stability Analysis
- Cognitive Load Estimation
- Cross-Linguistic Comparison

### Feature Engineering

A set of **26 structural metrics** was designed to capture:

- Dependency organization
- Branching behavior
- Structural stability
- Processing complexity
- Syntactic efficiency

### Dimensionality Reduction

Principal Component Analysis (PCA) was applied to identify dominant structural dimensions and explain variance across languages.

---

## Key Results

- Explained approximately **79% of total structural variance** using principal components.
- Recovered established **VSO → SVO → SOV** typological hierarchies.
- Successfully classified unseen languages through zero-shot projection.
- Demonstrated strong agreement between framework predictions and parser-performance benchmarks.
- Identified interpretable relationships between syntactic structure and cognitive processing effort.

---

## Repository Structure

```text
.
├── data/
├── notebooks/
├── src/
├── results/
├── figures/
├── paper/
└── README.md
```

---

## Installation

Clone the repository:

```bash
git clone https://github.com/muditar12/Incremental-Stability-and-Cognitive-Load-in-Natural-Language.git
cd Incremental-Stability-and-Cognitive-Load-in-Natural-Language
```

Install dependencies:

```bash
pip install -r requirements.txt
```

---

## Running the Analysis

```bash
python main.py
```

---

## Contributions

This project introduces:

- A novel **Stability Index** for measuring incremental syntactic organization.
- An **Incremental Cognitive Load** metric grounded in dependency structure.
- A computational framework for cross-linguistic typological analysis.
- An interpretable methodology linking language structure and processing complexity.

