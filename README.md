# Generation and Applications of Side Effect Embeddings in Biomedical Knowledge Discovery [![DOI](https://zenodo.org/badge/208453046.svg)](https://zenodo.org/badge/latestdoi/208453046)

This repository contains the master thesis of Rana Subhi Aldisi. Click [here](https://github.com/AldisiRana/masters_thesis/raw/master/main.pdf) for the latest version.

The predictions in this thesis were produced using this predictive model: [1209_node2vec_predictive_model.pkl](https://github.com/seffnet/seffnet/raw/master/resources/predictive_models/1209_node2vec_predictive_model.pkl) and its corresbonding embeddings [1209_node2vec_emb.embeddings](https://github.com/seffnet/seffnet/raw/master/resources/embeddings/1209_node2vec_emb.embeddings)

## Build

To build as a PDF, clone the repository and use the following command:

```bash
$ latexmk -pdf -pvc main
```
## Abstract

Side effects are unintended consequences of introducing drugs into the body.
Identifying a drug candidate's side effects is an important step in drug development that can both be expensive and still result in incomplete side effects profiles.
Further, side effect profiles have been used to identify drugs' targets and hypothesize new therapeutic benefits for existing drugs.

This thesis introduces a workflow that applies network representation learning to biomedical networks that contain drugs, their targets, their indications, and their side effects in an attempt to understand the mechanisms of action underlying side effects.
Different network representation learning models were evaluated and optimized before selecting the best for training a predictive model for relations between different entities in the original network.
It was then used to predict chemical-phenotype, chemical-target, and target-phenotype relations, which were analyzed and validated using literature.
