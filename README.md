# 📰 Hybrid Fake News Detection Using BERT and Speaker Credibility Ranking via PageRank

A hybrid AI framework that enhances fake news detection by integrating **deep semantic modeling (BERT)** with **speaker credibility scoring** using **PageRank**.  
This dual-feature approach significantly boosts classification accuracy by leveraging both textual content and metadata-driven credibility insights.

---

## ✨ Highlights

- 🔍 **BERT-based semantic understanding** of political statements  
- 🔗 **Speaker–Topic Graph** construction for credibility modeling  
- ⭐ **PageRank scoring** to rank speaker reliability  
- ⚡ **Feature fusion** (semantic + credibility + metadata)  
- 🌲 **Random Forest classifier** achieving improved performance  

---

## 📌 Abstract

Traditional fake news detection systems heavily rely on textual cues, often ignoring the reliability of the speaker.  
This project introduces a **hybrid detection pipeline** that combines:

- **BERT embeddings** for deep semantic text representation  
- **Credibility scores** derived from historical truthfulness labels  
- **Bipartite speaker–topic graph modeling**  
- **PageRank** for influence & credibility ranking  
- **Random Forest classifier** for final prediction  

This combination results in better robustness, generalization, and interpretability.

---

## 🗂️ Project Structure

├── Fake_News_Detection_Using_BERT_And_PageRank.ipynb # Full workflow & model implementation
└── DataSet/
├── train.tsv
├── test.tsv
└── valid.tsv

---

## 📊 Dataset

- **Dataset:** LIAR Fake News Dataset  
- **Source:** https://www.kaggle.com/datasets/csmalarkodi/liar-fake-news-dataset  
- Comprises **10,000+ political statements**  
- Includes **6 fact-check labels**:  
  `pants-fire`, `false`, `barely-true`, `half-true`, `mostly-true`, `true`  
- Contains metadata such as speaker, party, context, topic, etc.

---

## ⚙️ Tech Stack

- **Python 3.x**  
- **Jupyter Notebook**  
- **HuggingFace Transformers (BERT)**  
- **NetworkX (PageRank implementation)**  
- **scikit-learn**  
- **NumPy & Pandas**

---

## 📈 Results

| Model                        | Accuracy | F1-Score |
|------------------------------|----------|----------|
| Metadata Only                | 61%      | 0.59     |
| BERT Only                    | 69%      | 0.67     |
| **Hybrid (BERT + Metadata)** | **75%**  | **0.74** |

**Additional Metrics**  
- ROC-AUC: **0.75**  
- PageRank credibility features improved model stability and accuracy

---

## 🏅 Publication Details

**Published in IEEE Xplore**  
**Title:** *Hybrid Fake News Detection Using BERT and Speaker Credibility Ranking via PageRank*  
**Conference:** World Skill Conference of Universal Data Analytics and Sciences (WorldSUAS 2025)  
**Organized by:** Symbiosis University of Applied Sciences, Indore  
**Paper ID:** 68  
**Publisher:** IEEE  
**Year:** 2025  

🔗 **Read on IEEE Xplore:** https://ieeexplore.ieee.org/document/YOUR_DOI_LINK_HERE  
*(Replace with actual DOI link)*

---

## 📌 Project Status

- ✅ **Completed**  
- 🧾 **Published in IEEE (WorldSUAS 2025)**  
- 📚 Repository serves as the official implementation reference  

---

## 📬 Contact
- 📧 **Email:** hariiipriyaaa@gmail.com  
- 💼 **LinkedIn:** https://www.linkedin.com/in/hari-priya-l-software/
- 📧 **Email:** manasakb160@gmail.com  
- 💼 **LinkedIn:** https://www.linkedin.com/in/manasa-k-08b7a9320/

---

## ⭐ If you found this project helpful, consider starring the repo!
