# Review-based Recommender Systems  
## A Survey of Approaches, Challenges and Future Perspectives

Welcome to the official repository for our comprehensive survey on **Review-based Recommender Systems**.

📄 **Paper**: [arXiv:2405.05562](https://arxiv.org/abs/2405.05562)  
✅ **Accepted**: [ACM Computing Surveys (CSUR)](https://dl.acm.org/journal/csur)  

This work explores how textual reviews can be effectively integrated into recommender systems. It surveys major methodologies, including deep learning, graph-based, contrastive, and LLM-powered models. We also address practical challenges, emerging trends, and future research directions in this evolving field.

If you are aware of a relevant paper related to our work, please feel free to email the paper title and publication details to one of the co-first authors listed below. We would be glad to review it for possible inclusion in future updates.

---

## Table of Contents

1. [Introduction](#introduction)  
2. [Background](#background)  
3. [Why Incorporate Reviews in RS](#why-incorporate-reviews-in-rs)  
4. [Categories of Review-Based RS](#categories-of-review-based-rs)  
5. [State-of-the-Art Models](#state-of-the-art-models)  
6. [Miscellaneous Approaches](#miscellaneous-approaches)  
7. [Datasets and Evaluation](#datasets-and-evaluation)  
8. [Real-world Applications](#real-world-applications)  
9. [Challenges and Open Problems](#challenges-and-open-problems)  
10. [Future Directions](#future-directions)  
11. [Highlighted Papers](#highlighted-papers)    
12. [citation](#citation)  
13. [contact](#contact)

---

## Introduction

Recommender systems are critical in filtering vast digital content. While traditional RS rely on ratings or implicit feedback, user reviews offer rich, fine-grained signals like aspects, sentiment, and intent. This survey identifies gaps in previous works and presents a structured and updated review of RBRS from 2015 to 2024.

---

## Background

Traditional methods include:

- **Collaborative Filtering**: Relies on similar users/items. Struggles with data sparsity.
- **Content-based Filtering**: Uses item attributes to model user preferences. Suffers from limited exploration.
- **Hybrid Models**: Combines both, with increasing use of deep learning and sentiment analysis.

---

## Why Incorporate Reviews in RS

Reviews address key limitations:

- **Data Sparsity**: Provide detailed context where rating data is missing.
- **Improved Accuracy**: Capture nuanced preferences.
- **Explainability**: Justify why items are recommended based on review text.

---

## Categories of Review-Based RS

**Classification 1: Based on Integration Strategy**
- **Generic Review-based Methods**: Learn user/item representations directly from reviews.
- **Aspect-based Methods**: Extract aspect-level preferences.
- **Rating & Review Fusion**: Combine latent factors from ratings and reviews.
- **Ratings & Aspects Fusion**: Fuse aspect-aware sentiment with rating models.

**Classification 2: Based on Methodology**
- Probabilistic / Topic Models  
- Deep Learning (CNN, RNN, Attention)  
- GNN-based  
- Contrastive Learning  
- LLM-based  
- Miscellaneous (e.g., Reinforcement, Counterfactuals)

---

## State-of-the-Art Models

### Probabilistic & Topic Models  
- **HFT**, **RBLT**, **NGMM**, **TIM**: Use LDA or Gaussian Mixtures to map review topics to latent factors.

### Deep Learning  
- **CNN Models**: ConvMF, DeepCoNN  
- **Attention Models**: AARM, A3NCF  
- **CNN+Attention**: NARRE, D-Attn  
- **RNN/GRU/LSTM**: TARMF, DER, AFRAM  
- **GNN**: TrinRank, RMG, AHOR  
- **Contrastive Learning**: MAGCL, RGCL, MCCL  
- **LLMs**: Prompt-tuned GPT, SIFN with BERT  

---

## Miscellaneous Approaches

Includes:
- Reinforcement Learning (ARG, LightDL)
- Counterfactual Reasoning (CountER)
- Knowledge Distillation (LUME)
- Multi-Criteria Fusion
- Sentiment Lexicons

---

## Datasets and Evaluation

Common datasets:  
- **Amazon**, **Yelp**, **MovieLens**, **TripAdvisor**, **Goodreads**

Metrics used:  
- **Rating Prediction**: MSE, RMSE, MAE  
- **Ranking**: HR, nDCG, Precision/Recall  
- **Explainability/Trust**: BLEU, BERTScore, ROUGE

---

## Real-world Applications

- **E-Commerce** (Amazon, Flipkart)  
- **Tourism & Hotels** (TripAdvisor)  
- **Streaming** (Netflix, Spotify)  
- **Food Delivery** (Yelp, Uber Eats)  
- **Education & Courses** (MOOCs)  

---

## Challenges and Open Problems

- **Scalability**: Real-time integration of reviews
- **Bias & Fairness**: Reviews may reinforce stereotypes
- **Multilinguality**: Sparse resources for low-resource languages
- **Cold Start**: For unseen users/items
- **Explainability vs. Performance Tradeoff**

---

## Future Directions

- **Real-time RS** with continual learning  
- **On-device RS** for privacy-preserving inference  
- **Causal RS** with counterfactual explainability  
- **Conversational RS** powered by LLMs  
- **Multi-modal Fusion** (reviews + images + audio)  

---

## Highlighted Papers

- [04/2017] **Neural collaborative filtering** Xiangnan et al.  ACM.* [[paper]](https://dl.acm.org/doi/abs/10.1145/3038912.3052569)
- [11/2018] **Attentive Aspect Modeling for Review-aware Recommendation** Xinyu et al.  Arxiv.* [[paper]](https://arxiv.org/pdf/1811.04375)
- 
---
## Contact
For queries or collaborations:
- **Email**: [emrul.phy@gmail.com], [mizanur.york@gmail.com]
- **Contributions**: Feel free to submit a pull request for updates or suggestions!

## Citation
If you find our work useful, please cite it as follows:

```bibtex
@article{hasan2024review,
  title={Review-based Recommender Systems: A Survey of Approaches, Challenges and Future Perspectives},
  author={Hasan, Emrul and Rahman, Mizanur and Ding, Chen and Huang, Jimmy Xiangji and Raza, Shaina},
  journal={arXiv preprint arXiv:2405.05562},
  year={2024}
}

```
