# Generation and Applications of Side Effect Embeddings in Biomedical Knowledge Discovery

## Build

To build as a PDF, clone the repository and use the following command:

```bash
$ latexmk -pdf -pvc main
```
## Abstract
Side effects are unintended reactions caused by introducing drugs into the body. Discovering a drug’s side effects is an important step in drug development, which can be expensive and lead to incomplete side effects profile. Many approaches have been developed to predict side effects in an effort to understand the mechanism(s) of action of a drug and – as a consequence - make the drug development process more efficient. Side effect information has also been used to identify drug targets and find new therapeutic benefits for existing drugs.

This thesis introduces a workflow that applies network representation learning, which is a machine learning approach for learning representations in low dimensions, on biomedical networks that contain drug-, target- and side effect-information in an attempt to understand the causes of side effects. Different representation learning methods were evaluated to select the best model, which was then used to train a logistic regression classifier to predict relations between different entities. The predictive model was able to predict chemical-phenotype, chemical-target and target-phenotype relations, which were analyzed and validated using literature.
