## This repository contains the code, pre-trained models and training data for our paper.

## chekpoints
Our released models are listed as follows: 

| Model name                             | Avg. On STS tasks | Avg. On Transfer Learning tasks |
| -------------------------------------- | ----------------- | ------------------------------- |
| SoDehghan/selfccl-bert-base-uncased    |       81.80       |              86.90              |
| SoDehghan/selfccl-sbert-base-uncased   |       81.77       |              86.95              |
| SoDehghan/sbert-nli-v2-contrastive     |       81.60       |              86.82              |


## Hardware requirements

| Model name               |  GPU: Nvidia A100 80GB  |  batch size | epochs  |  
| ------------------------ | ----------------------- | ----------- | ------- | 
| selfccl-bert-base        |           4             |     512     |    4    |  
| selfccl-sbert-base       |           1             |     350     |    4    |
| sbert-nli-v2-contrastive |           1             |     350     |    3    |


## Download datasets
Download training data for our chekpoints from HuggingFace

```
!wget 

```

# Citation
[Somaiyeh Dehghan](https://scholar.google.com/citations?user=_cZFR5sAAAAJ&hl=en), [Mehmet Fatih Amasyali](https://avesis.yildiz.edu.tr/amasyali/), "SelfCCL: Curriculum Contrastive Learning by Transferring Self-Taught Knowledge for Fine-Tuning BERT", Applied Sciences (Special Issue: Special Issue:  New Technologies and Applications of Natural Language Processing), 2023, Vol. 13(3):1913. DOI: [10.3390/app13031913](https://doi.org/10.3390/app13031913)

```
@article{Dehghan2023,
 title    =  {SelfCCL: Curriculum Contrastive Learning by Transferring Self-Taught Knowledge for Fine-Tuning BERT},
 author   =  {Somaiyeh Dehghan and Mehmet Fatih Amasyali},
 journal  =  {Applied Sciences},
 volume   =  {Vol. 13(3):1913},
 pages    =  {},
 year     =  {2023},
 publisher=  {},
 DOI     =   {10.3390/app13031913}
 %url    =   {https://doi.org/10.3390/app13031913}
}
```



## Acknowledgements

