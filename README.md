# JAPE-GPT: Adversarial Dataset & Detection Framework for LLM Security

##  Overview

JAPE-GPT is a security-focused dataset and machine learning framework designed to detect **prompt injection** and **jailbreak attacks** in Large Language Models (LLMs).

This project addresses critical vulnerabilities in modern AI systems by modeling adversarial behavior and enabling robust detection using feature-engineered data.

---

##  Objectives

* Build a **large-scale adversarial dataset**
* Model attacks such as:

  * Prompt Injection
  * Jailbreaks
  * Obfuscation attacks
  * Social engineering prompts
* Engineer **32+ security-aware features**
* Train ML models for:

  * Malicious prompt detection
  * Jailbreak success prediction
  * Risk scoring

---

##  Dataset

* Size: **10,263 samples**
* Categories:

  * Jailbreak
  * Prompt Injection
  * Obfuscation
  * Adversarial
  * Benign

Each sample includes:

* Prompt + Response
* Linguistic features
* Behavioral signals
* Structural attack indicators
* Outcome labels (risk, success)

---

##  Methodology

### 1. Dataset Generation

* Scenario-driven prompt engineering
* Automated LLM-based generation
* Multi-turn adversarial chaining

### 2. Feature Engineering

* Text features (TF-IDF + PCA)
* Structural features (zero-width, homoglyphs)
* Behavioral features (intent, tone)

### 3. Models Used

* Random Forest
* XGBoost
* SVM
* Neural Networks

---

##  Results

* Strong performance across multiple models
* High precision/recall for adversarial detection
* Robust handling of obfuscated attacks


---

## Future Work

* Real-time detection API
* Integration with LLM pipelines
* Transformer-based models (BERT, LLM fine-tuning)

