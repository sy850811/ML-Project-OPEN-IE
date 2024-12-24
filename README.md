
# Project: OPEN Information Extraction (OPEN-IE)

This repository contains the implementation and analysis of models for **Open Information Extraction (Open-IE)** using advanced machine learning techniques, including RNNs, Bi-LSTMs, and baseline models. The project focuses on extracting meaningful relationships and entities from unstructured text data, leveraging curated datasets and experimentation results.

---

## Table of Contents
1. [Introduction](#introduction)
2. [Dataset Details](#dataset-details)
3. [Model Architectures](#model-architectures)
4. [Experiments and Results](#experiments-and-results)
5. [Project Structure](#project-structure)
6. [How to Run](#how-to-run)
7. [Visualizations](#visualizations)
8. [Acknowledgements](#acknowledgements)

---

## Introduction

Open Information Extraction (Open-IE) aims to identify and extract structured information from unstructured textual data. This project implements models to extract relationships between entities in sentences. The results contribute to the broader field of natural language understanding, aiding tasks such as question answering, knowledge graph construction, and summarization.

**Key Highlights:**
- Models: RNN, LSTM, and Bi-LSTM architectures.
- Datasets: Curated abstract data from Wikipedia.
- Metrics: Performance evaluation using accuracy, precision, recall, and F1-score.

---

## Dataset Details

The project utilizes multiple datasets:
1. **Abstract Training Data**
   - `Abstract_1_2_Training_Data.csv`: A training set comprising sentences and labeled entities.
2. **Wiki Sentences Data**
   - Variants: `wiki_sentences_abstract_1.csv`, `wiki_sentences_abstract_2.csv`, `wiki_sentences_abstract_3.csv`, `wiki_sentences_v2.csv`.

Each dataset contains pre-processed textual data with annotations for information extraction tasks.

---

## Model Architectures

### Recurrent Neural Network (RNN)
- Sequential processing of input sentences.
- Suitable for capturing temporal relationships.

### Long Short-Term Memory (LSTM)
- Enhanced capability to remember long-term dependencies.
- Addresses vanishing gradient issues in RNNs.

### Bidirectional LSTM (Bi-LSTM)
- Processes input sequences in both forward and backward directions.
- Provides richer context for entity and relationship extraction.

---

## Experiments and Results

Extensive experimentation was conducted to evaluate the models:
- **Baseline Models:** Serve as a benchmark.
- **LSTM Models:** Show significant improvements in capturing relationships.
- **Bi-LSTM Models:** Achieve the highest performance metrics.

Results:
- **Precision:** Measures accuracy of extracted information.
- **Recall:** Measures completeness of extracted information.
- **F1-Score:** Balances precision and recall.

---

## Project Structure

```
ML-Project-OPEN-IE-main/
├── Data/
│   ├── Abstract_1_2_Training_Data.csv
│   ├── wiki_sentences_abstract_*.csv
├── Notebooks/
│   ├── Bi-LSTM.ipynb
│   ├── ML_LSTM_Experiments.ipynb
│   ├── ML_Project_Baseline.ipynb
│   ├── RNN.ipynb
├── Docs/
│   ├── ML Report Final.docx
│   ├── Information Extraction Poster.pdf
└── README.md
```

---

## How to Run

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/your-repo/ML-Project-OPEN-IE.git
   cd ML-Project-OPEN-IE
   ```

2. **Install Dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

3. **Run Notebooks:**
   Use Jupyter Notebook to execute `.ipynb` files for training and evaluation.

---

## Acknowledgements

This project was developed as part of a machine learning coursework/project. Special thanks to the contributors and mentors who guided this research.
