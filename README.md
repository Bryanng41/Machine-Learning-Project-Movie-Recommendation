# Movie Recommendation System with Traditional and Deep Learning Models

This project explores and compares multiple approaches to movie recommendation systems using **The Movies Dataset** from Kaggle. Spanning from collaborative filtering to deep learning models, this project aims to understand how each method performs in addressing personalization and cold-start problems.

We used six Google Colab notebooks to implement and test:
- Data Preprocessing
- Collaborative Filtering (CF)
- Content-Based Filtering (CBF)
- Hybrid (CF + CBF)
- Neural Collaborative Filtering (NCF, NeuMF, Hybrid NeuMF)
- Sequence-based LSTM Recommender

---

## 📊 Dataset

We used [The Movies Dataset on Kaggle](https://www.kaggle.com/datasets/rounakbanik/the-movies-dataset), originally from [GroupLens](https://grouplens.org/datasets/movielens/).

---

## 📈 Evaluation Metrics

Our models were evaluated using:
- Precision@K
- NDCG@10
- Top-K Accuracy

---

## 📓 Notebook Links (Google Colab)

| Step | Model | Colab Link |
|------|-------|------------|
| Step 1 | Data Preprocessing | [Colab](https://colab.research.google.com/drive/10qFoIhXaufa7ZUA98WQOaAOgAmJJniid?usp=sharing) |
| Step 2A | Collaborative Filtering | [Colab](https://colab.research.google.com/drive/1qjlfgj8qvyb4t5K05dvY0MeXWLzrx7Ob#scrollTo=tsMeoVKFuFQs) |
| Step 2B | Content-Based Filtering | [Colab](https://colab.research.google.com/drive/1kri8k-x7XNF2xvh7O_cjMMtBtZFBc1iv#scrollTo=R5bZv3CVEKTc) |
| Step 2C | Hybrid CF + CBF | [Colab](https://colab.research.google.com/drive/15Kf6Fi0w0k1HgxAYU7huEPkTTu_ffl77#scrollTo=b4B4JBBMvt0x) |
| Step 3 | NCF + NeuMF + Variants | [Colab](https://colab.research.google.com/drive/1p237l_pdPN_YO_J_92iCvsi2qUC7vzZn?usp=sharing) |
| Step 4 | LSTM Recommender | [Colab](https://colab.research.google.com/drive/1eGqQRYtL2hpcvfXzP6S0J_q1zBduVBBh#scrollTo=A7WmW2MsJq7U) |

---

## 👥 Team Members
- Ng Zheng Leng Bryan
- Heng Hong Quan
- Lim Jun Ying
- Brandon Mok
- Tan Ee Sean
