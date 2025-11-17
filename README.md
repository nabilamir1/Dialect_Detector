# 🗣️ Arabic Dialect Identification — Dialect Classification with Transformers

![Dialect Classification](https://github.com/Nabil-a11/dialect_detector/blob/main/Screenshot%202025-11-15%20220337.png)

[![HuggingFace Space CAMeLBERT](https://img.shields.io/badge/HuggingFace--CAMeLBERT-blue?logo=huggingface)](https://huggingface.co/spaces/NvbilVmir1/Madar-CAMeLBERT)

[![HuggingFace Model](https://img.shields.io/badge/HuggingFace--Model-orange?logo=huggingface)](https://huggingface.co/spaces/NvbilVmir1/Madar)

[![MADAR Dataset](https://img.shields.io/badge/Dataset-MADAR-green?logo=kaggle)](https://www.kaggle.com/datasets/mafazachabane/madar-corpus)


*Arabic Dialect Identification* is a deep learning project that classifies Arabic text into four main dialect groups: Egyptian, Khaleeji (Gulf), Levantine, and African (Maghrebi). The models leverage transformer architectures fine-tuned on the MADAR corpus.

---

## 🎯 Project Goals

- Build robust Arabic dialect classifiers using state-of-the-art transformers.
- Compare the performance of CAMeLBERT vs AraELECTRA on the same dataset.
- Provide a reusable pipeline for Arabic dialect text preprocessing, training, and evaluation.
- Visualize classification performance via confusion matrices and detailed metrics.

---

## 🗂 Dataset

We use the **MADAR corpus**, grouped into four dialect clusters based on city:

| Dialect   | Cities Included                                    |
|-----------|---------------------------------------------------|
| Egyptian  | Alexandria, Cairo                                  |
| Levantine | Aleppo, Amman, Damascus, Jerusalem                 |
| African   | Algiers, Benghazi, Fes, Khartoum, Rabat, Sfax, Tripoli, Tunis |
| Khaleeji  | Baghdad, Doha, Jeddah, Riyadh, Sanaa               |

---

## 🔍 Models

- **CAMeLBERT**  
  Arabic BERT model pretrained for dialectal Arabic.

- **AraELECTRA**  
  ELECTRA-based Arabic language model pretrained on large Arabic corpora.

---

## 📊 Results Summary

| Dialect   | CAMeLBERT F1-score | AraELECTRA F1-score |
|-----------|--------------------|---------------------|
| African   | 0.92               | 0.91                |
| Khaleeji  | 0.83               | 0.82                |
| Levant    | 0.78               | 0.75                |
| Egyptian  | 0.85               | 0.82                |
| **Accuracy** | **0.87**           | **0.85**             |

---

## 📒 Notebooks

Explore the detailed implementation and experiments in these Google Colab notebooks:

- [Notebook 1 - CAMelBRET](https://colab.research.google.com/drive/19Jvxkr-1sXci2RXkVN6mixs9dLH2QSNG#scrollTo=O1cVjdh1VYRG)
- [Notebook 2 - AraELECTRA](https://colab.research.google.com/drive/1e-qwLiDzPk6EBaq4QfMejOSQ0KAVQhfi#scrollTo=JdkHEDLS2HR7)

---

## 👥 Team Members

- Nabil Amir  
- Fares Mohamed  
- Abdelrahman Mohamed
- Salah Eldin Mostafa
- Marwan Elgabry
- Mina Nagy

---

## 🚀 Quick Start

### 1. Clone Repository

```bash
git clone https://github.com/yourusername/arabic-dialect-id.git
cd arabic-dialect-id
