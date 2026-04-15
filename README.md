# Customized Dynamic Filter Augmentation (CDFA) for Time Series Forecasting

This repository implements the **Customized Dynamic Filter Augmentation (CDFA)** method for time series forecasting. The codebase is structured to clearly separate the core algorithm from baseline models and experimental validation, ensuring reproducibility and ease of understanding.

The theoretical foundation of this work is based on the following publication:
> **Customized Dynamic Filter Augmentation**  
> *Song-Kyoo Kim*  
> IEEE Signal Processing Letters, 2026  
> [[PDF]](https://ieeexplore.ieee.org/abstract/document/11340620)

---

## 📂 Repository Structure

The project is organized into four main directories:

- **`Standard_Models/`**: Contains standard implementations of various baseline models. These are used for preliminary testing and performance comparison.
- **`Forecasting_without_CDFA/`**: Contains the complete experimental codebase. This section demonstrates the forecasting pipeline **without** integrating the core CDFA augmentation technique.
- **`CDFA/`**: Contains the **core method** implementation. This is the primary contribution of the paper, featuring the Customized Dynamic Filter Augmentation algorithm.
- **`Datasets/`**: Contains the dataset files used for training and evaluation.

---

## 📄 Paper Overview

**[To be filled in by the user]**
*This section will provide a concise introduction to the research, outlining the problem statement, objectives, and significance of the work.*

## 💡 Core Concept

**[To be filled in by the user]**
*This section will explain the fundamental principles behind the CDFA method, including the motivation for dynamic filter customization and its theoretical advantages.*

## 🔄 Methodology

**[To be filled in by the user - Include a flowchart here]**
*This section will detail the step-by-step workflow of the proposed algorithm.*

## 📊 Experimental Results

**[To be filled in by the user]**
*This section will present the quantitative and qualitative results of the experiments, comparing the performance of models with and without CDFA.*

---

## 🚀 Getting Started

**[To be filled in by the user]**
*Instructions on how to set up the environment, run the code, and reproduce the results.*

### Prerequisites
- Python 
- PyTorch

### Installation
```bash
pip install -r requirements.txt