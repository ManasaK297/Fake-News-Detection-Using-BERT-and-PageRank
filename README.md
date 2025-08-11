# 📰 Hybrid Fake News Detection Using BERT and Speaker Credibility Ranking via PageRank

This project proposes a hybrid AI framework for fake news detection, combining deep semantic modeling (BERT) with speaker credibility scoring using PageRank on a speaker-topic graph. Designed to improve classification accuracy by integrating both text content and metadata.

---

## 📌 Abstract

While most fake news detection systems rely solely on text patterns, this project introduces a hybrid method that factors in **speaker credibility**.  
- Uses **BERT embeddings** for news statements  
- Computes **credibility scores** from historical truth labels  
- Builds a **bipartite speaker-topic graph**  
- Applies **PageRank** to assess speaker influence  
- Fuses all features and classifies using a **Random Forest**  

---

## 🗂️ Project Structure  

- `Fake_News_Detection_Using_BERT_And_PageRank.ipynb` — Full code and model implementation  
- `DataSet/` — Contains `train.tsv`, `test.tsv`, `valid.tsv`  
- `Research_Paper.pdf` — Full research paper  (accepted at IEEE WorldSUAS 2025)

---

## 📊 Dataset  

- **Source:** [LIAR Fake News Dataset (Kaggle)](https://www.kaggle.com/datasets/csmalarkodi/liar-fake-news-dataset)  
- Contains over **10,000 labeled political statements** with metadata  
- Six fact-checking labels ranging from `pants-fire` to `true`  

---

## ⚙️ Tech Stack

- Python 3.x  
- Jupyter Notebook  
- BERT (HuggingFace Transformers)  
- NetworkX (for PageRank)  
- Pandas, NumPy  
- scikit-learn  

---

## 📈 Results

| Model                      | Accuracy | F1-Score |
|:---------------------------|:-----------|:------------|
| Only Metadata               | 61%       | 0.59        |
| Only BERT                   | 69%       | 0.67        |
| **BERT + Metadata (Ours)** | **75%**   | **0.74**    |

- ROC-AUC: 0.75  
- F1-Score: 0.74  
- PageRank improved credibility assessment and boosted classification accuracy  

---



## 📄 Paper Publication

 **Accepted at WorldSUAS 2025**  
 *World Skill Conference of Universal Data Analytics and Sciences (WorldSUAS 2025)*  
 *Organized by Symbiosis University of Applied Sciences, Indore*  
 **Publisher:** IEEE (Camera-ready version under preparation)  
 Paper ID: 68  
 Title: *Hybrid Fake News Detection Using BERT and Speaker Credibility Ranking via PageRank*  

---

##  Project Status

 Project Completed  
 Research Paper Accepted for Presentation  
 Camera-ready paper and eCopyright form under preparation  

---
## 📬 Contact  

- 📧 **Email:** manasakb160@gmail.com  
- 💼 **LinkedIn:** [manasa-k-08b7a9320](https://www.linkedin.com/in/manasa-k-08b7a9320/)

---
