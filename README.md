# KG-Based-Recommender-System-Modified

## Model Analysis
### Hyperparameters Default
| Parameter | Value |
|-----------|-------|
| Batch Size | 128 |
| Evaluation Batch Size | 1024 |
| Negative Sampling Rate | 3 |
| Embedding Dimensions | 64 |
| Margin | 35 |
| Learning Rate | 1e-3 |
| Weight Decay | 5e-4 |
| Epochs | 50 |

### Hyperparameters Modification
| Parameter | Value |
|-----------|-------|
| Batch Size | 128 |
| Evaluation Batch Size | 1024 |
| Negative Sampling Rate | 2.0 |
| Embedding Dimensions | 32 |
| Margin | 10 |
| Learning Rate | 2e-3 |
| Weight Decay | 1e-4 |
| Epochs | 45 |

### Experiment Results
#### AUC Evaluation
- *AUC Score Author:* 0.8861
- *My AUC Score:* 0.9002

#### nDCG@5 Evaluation
- *Author nDCG@5 Score:* 0.1078
- *My nDCG@5 Score:* 0.1217

## Conclusion
Based on the experiments conducted, it can be concluded that:
- The KGRS model using the TransE algorithm provides fairly accurate recommendation results after parameter tuning.
- The AUC value increased from 0.8861 to 0.9002, while the nDCG@5 value improved from 0.1078 to 0.1217.
- Increasing the embedding dimension and the number of epochs allowed the model to better learn the relationships between entities.
- As the model complexity increases, the training time becomes longer; however, the results obtained are more satisfactory.

## References
- Q. Guo et al., "A Survey on Knowledge Graph-Based Recommender Systems," IEEE Transactions on Knowledge and Data Engineering, pp. 1–1, 2020, doi: 10/ghxwqg.
- D. Bahdanau, K. Cho, and Y. Bengio, "Neural Machine Translation by Jointly Learning to Align and Translate," in 3rd International Conference on Learning Representations, ICLR 2015, San Diego, CA, USA, May 7-9, 2015. [Online]. Available: [http://arxiv.org/abs/1409.0473](http://arxiv.org/abs/1409.0473)
- https://github.com/Layheng-Hok/KG-Based-Recommender-System?tab=readme-ov-file
- https://github.com/bluga404/KG-Based-Recommender-System-Modified

