## SelfCCL:
This repository contains the code, pre-trained models and training data for our paper.

## SelfCCL chekpoints
Our released models are listed as follows: 

"SoDehghan/selfccl-bert-base-uncased"    
"SoDehghan/selfccl-sbert-base-uncased"



# Download datasets
Download training data for SupMPN from HuggingFace
```
!wget https://huggingface.co/datasets/SoDehghan/datasets-for-supmpn/all_snli_mnli_for_supmpn.csv

!wget https://huggingface.co/datasets/SoDehghan/datasets-for-supmpn/sub_snli_for_supmpn_8k.csv

```



# Acknowledgements
Loss function Codes are adapted from the repos of the EMNLP19 paper [Sentence-BERT: Sentence Embeddings using Siamese BERT-Networks](https://github.com/UKPLab/sentence-transformers)
Our implementation are based on setup from the repo of the SimCSE paper [SimCSE: Simple Contrastive Learning of Sentence Embeddings] (https://github.com/princeton-nlp/SimCSE)
