<h1 align="center">Tensionflow - Intrusion Detection System (IDS)</h1>
<p align="center">
  <a href="https://weekendofcode.computercodingclub.in/">
    <img src="https://i.postimg.cc/njCM24kx/woc.jpg" height="30px">
  </a>
</p>

## Introduction

Tensionflow is a machine learning-based Intrusion Detection System (IDS) designed to accurately classify network traffic and detect various types of cyber-attacks using the NSL-KDD dataset. This project was developed as part of **Weekend of Code 9.0 - Turing's Playground**.

## Table of Contents

- [Problem Statement](#problem-statement)
- [Project Plan](#project-plan)
  - [Phase 1: Basic Analysis](#phase-1-basic-analysis)
  - [Phase 2: Advanced Analysis](#phase-2-advanced-analysis)
- [Technology Stack](#technology-stack)
- [Project Highlights](#project-highlights)
- [Future Scope](#future-scope)
- [Contributors](#contributors)

## Problem Statement

**Problem Statement ID:** M-03

**Objective:** Design a machine learning-based Intrusion Detection System (IDS) that accurately classifies network traffic and detects different types of cyber-attacks using the **NSL-KDD dataset**.

## Project Plan

### Phase 1: Basic Analysis

**Objective:** Gain insights into the NSL-KDD dataset and implement simple machine learning models for intrusion detection.

- **Data Understanding:**
  - Load and analyze the dataset's structure.
  - Identify different network traffic classes (normal vs. attack types).

- **Data Preprocessing:**
  - Handle missing values.
  - Convert categorical data into numerical format using one-hot encoding.
  - Normalize data for better model performance.

- **Model Development:**
  - Split data into training and testing sets.
  - Train basic ML models such as **Random Forest Classifier**.

- **Visualization:**
  - Use **Matplotlib** and **Seaborn** to visualize data.
  - Identify feature relationships and patterns.

- **Evaluation:**
  - Assess performance using **accuracy**.
  - Generate confusion matrices to analyze classification results.

### Phase 2: Advanced Analysis

**Objective:** Enhance the Intrusion Detection System by implementing more advanced techniques and improving accuracy.

- **Feature Engineering:**
  - Select the most important features to improve detection.
  - Create new features to capture hidden patterns.

- **Handling Class Imbalance:**
  - Apply **oversampling** or **undersampling** to balance attack types.

- **Advanced Model Development:**
  - Implement **Support Vector Machines (SVM)** for better accuracy.
  - Experiment with **ensemble methods** to boost performance.
  - Stacked **LGBM Classifier**, **SVM**, and **Random Forest Classifier** to try to achieve better accuracy.

- **Hyperparameter Tuning:**
  - Optimize model parameters using **Optuna**.

- **Evaluation:**
  - Use **cross-validation** to improve generalization.
  - Evaluate using **precision, recall, and F1-score**.

## Technology Stack

- **Python**
- **Pandas**
- **NumPy**
- **Scikit-learn**
- **Matplotlib**
- **Seaborn**
- **Optuna** *(for hyperparameter tuning)*

## Project Highlights

- **Structured Approach:** Progressive learning from basic to advanced techniques.
- **Hyperparameter Tuning:** Utilizing **Optuna** for optimal algorithm selection.

## Future Scope

- **Deep Learning Approaches:** Experimenting with CNNs & RNNs.
- **Real-time Implementation:** Deploying IDS on actual network traffic.
- **Integration with Cloud Services:** Making the IDS scalable.

## Contributors

**Team Name:** Tensionflow

- [Vatsal Kumar](https://github.com/krVatsal) *(Leader)*
- [Abhijit Saha](https://github.com/abhigit-saha)
- [Kanishk Agrawal](https://github.com/Kanishk00001)
- [Rishabh Kumar Pandey](https://github.com/rishabhkrpandey)

### Made at:

<p align="center">
  <a href="https://weekendofcode.computercodingclub.in/">
    <img src="https://i.postimg.cc/mrCCnTbN/tpg.jpg" height="30px">
  </a>
</p>
