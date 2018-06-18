# Sentence selection
#### The selection of relevant sentences for QA systems

## Rankers
| TF-IDF        | InferSent     | MatchZoo | USE | Mean Word2Vec | Perplexity |
|:-------------:|:-------------:|:--------:|:---:|:-------------:|:----------:|
| Ready | Ready | Almost ready | None | None | Need check |

## Scores

| **Ranker**    | Recall@1 | Recall@3 | Recall@5 |
|:--------------|:--------:|:--------:|:--------:|
| TF-IDF        | 0.627 | 0.882 | 0.962 |
| InferSent MS Marco | 0.660 | 0.918 | 0.980 |
| InferSent SQuAD | 0.567 | 0.888 | 0.971 |
| InferSent Fujitsu | 0.278 | 0.703 | 0.910 |
| InferSent Query_Context | 0.682 | 0.920 | 0.982 |
| MatchZoo      | None | None | None |
| USE           | None | None | None |
| Mean Word2Vec | None | None | None |
| Perplexity (Avg) | 0.264 | 0.678 | 0.894 |

## Results
| Model | EM | F1 |
|:------|:--:|:--:|
| R-NET | 70.918 | 79.644 |
| TF-IDF | 63.917 | 72.472 |
| Ifs@3 (Query_Context) | 62.081 | 70.707 |
| TF-IDF + MSMarco| 64.626 | 73.057 |
