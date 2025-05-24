# Review-based Recommender Systems  
## A Survey of Approaches, Challenges and Future Perspectives

Welcome to the official repository for our comprehensive survey on Review-based Recommender Systems [Paper](https://arxiv.org/abs/2405.05562). This work covers the integration of textual reviews into recommender systems, highlighting methodologies, challenges, and future directions in this evolving domain. If you are aware of a relevant paper related to our work, please feel free to email the paper title and publication details to one of the co-first authors listed below. We would be glad to review it for possible inclusion.

---

## Table of Contents

1. Introduction  
2. Background  
3. Why Incorporate Reviews in RS  
4. Categories of Review-Based RS  
5. State-of-the-Art Models  
6. Miscellaneous Approaches  
7. Datasets and Evaluation  
8. Real-world Applications  
9. Challenges and Open Problems  
10. Future Directions  
11. Conclusion    
12. Citation  

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

## Conclusion

This survey unifies scattered works on review-based recommender systems and introduces a dual classification to structure the field. It evaluates over 110 models across various methodologies and identifies future pathways for robust, fair, and interpretable recommender systems.

---
## Contact
For queries or collaborations:
- **Email**: [emrul.phy@gmail.com], [mizanur.york@gmail.com]
- **Contributions**: Feel free to submit a pull request for updates or suggestions!
- 
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
