# Try-with-Bluebert-model

## Reproduce bluebert model (bluebert_reproduced folder)
This project reproduced the bluebert model from https://github.com/ncbi-nlp/BLUE_Benchmark. 

## Modify and build pipelines to apply bluebert model on new datasets (bluebert_test folder)
This project transfer the bluebert model into the Pytorch version based on Huggingface and https://github.com/dmis-lab/biobert-pytorch. 
Notebook pipelines have been built.

## Download pre-trained Bluebert model
We could donwload the Bluebert weights from Huggingface

https://huggingface.co/bionlp/bluebert_pubmed_uncased_L-12_H-768_A-12
https://huggingface.co/bionlp/bluebert_pubmed_mimic_uncased_L-12_H-768_A-12
https://huggingface.co/bionlp/bluebert_pubmed_uncased_L-24_H-1024_A-16
https://huggingface.co/bionlp/bluebert_pubmed_mimic_uncased_L-24_H-1024_A-16

## Citation

```
@InProceedings{peng2019transfer,
  author    = {Yifan Peng and Shankai Yan and Zhiyong Lu},
  title     = {Transfer Learning in Biomedical Natural Language Processing: 
               An Evaluation of BERT and ELMo on Ten Benchmarking Datasets},
  booktitle = {Proceedings of the 2019 Workshop on Biomedical Natural Language Processing (BioNLP 2019)},
  year      = {2019},
}
```
