   
# MDRDC（Malevolent Dialogue Response Detection and Classification）dataset and baselines

## The MDRDC dataset and baselines for malevolent dialogue detection and classification.

## Dataset
Dataset, lexicon and annotation task design html files will be publicly available after our paper gets accepted.
The ./dataset/data_example.tsv file has an example of the dataset now. The whole dataset includes 6,000 dialogues.


## Baselines
### Requirements
python 3.6
pytorch 1.0
Tensorflow >= 1.4.0

### Run models
#### charCNN
We modify the charCNN baseline from Yuanping Chen's open source code.
Link: [charCNN](https://github.com/srviest/char-cnn-text-classification-pytorch)
#### RNN,CNN,RCNN
We modify the RNN,CNN,RCNN baselines from Wenxing Hu's open source code.
Link: [RNN,CNN,RCNN](https://github.com/649453932/Chinese-Text-Classification-Pytorch)

#### GCN
We use the GCN baseline from Liang Yao's open source code.
Link: [textGCN](https://github.com/yao8839836/text_gcn),[textGCN.pytorch](https://github.com/iworldtong/text_gcn.pytorch)

#### BERT-base
We modify the BERT-base text classification model from Yingxin Song's open source code.
Link:
[BERT-base](https://github.com/songyingxin/Bert-TextClassification)

#### BERT-conf
We use the softmax score and TCP score as confidence.
Softmax score come from the BERT-base model directly. Please use the softmax score of BERT-base classification model.
TCP score is trained by the BERT-Confidnet module. Please refer to the code of our another paper, link: [BERT-conf](https://github.com/repozhang/CaSE_HMCEval)

#### checkpoint files:
We provide part of the checkpoint files for BERT-base classification model.
Due to the file size, we provide the files for Table 7 and Table 8.
You can load the files to get the results for the test dataset.

##### MDRDC without context (Table 7):[1st-level, 2nd-level and 3rd-level](https://drive.google.com/file/d/1Ih6UQas7aVpKw2FR179ro7xKORpNU6I9/view?usp=sharing)

##### MDRDC with context (Table 8):[1st-level, 2nd-level and 3rd-level](https://drive.google.com/file/d/17sfHuwjRPOn0T6C2T7ARw8WMtsjJ_iRU/view?usp=sharing)


#### BERT pretrained files download:
##### vocab
[bert-base-uncased](https://s3.amazonaws.com/models.huggingface.co/bert/bert-base-uncased-vocab.txt),
[bert-large-uncased](https://s3.amazonaws.com/models.huggingface.co/bert/bert-large-uncased-vocab.txt),
[bert-base-cased](https://s3.amazonaws.com/models.huggingface.co/bert/bert-base-cased-vocab.txt),
[bert-large-cased](https://s3.amazonaws.com/models.huggingface.co/bert/bert-large-cased-vocab.txt),
[bert-base-multilingual-uncased](https://s3.amazonaws.com/models.huggingface.co/bert/bert-base-multilingual-uncased-vocab.txt),
[bert-base-multilingual-cased](https://s3.amazonaws.com/models.huggingface.co/bert/bert-base-multilingual-cased-vocab.txt),
[bert-base-chinese](https://s3.amazonaws.com/models.huggingface.co/bert/bert-base-chinese-vocab.txt).

##### pretrained BERT weights
[bert-base-uncased](https://s3.amazonaws.com/models.huggingface.co/bert/bert-base-uncased.tar.gz),
[bert-large-uncased](https://s3.amazonaws.com/models.huggingface.co/bert/bert-large-uncased.tar.gz),
[bert-base-cased](https://s3.amazonaws.com/models.huggingface.co/bert/bert-base-cased.tar.gz),
[bert-large-cased](https://s3.amazonaws.com/models.huggingface.co/bert/bert-large-cased.tar.gz),
[bert-base-multilingual-uncased](https://s3.amazonaws.com/models.huggingface.co/bert/bert-base-multilingual-uncased.tar.gz),
[bert-base-multilingual-cased](https://s3.amazonaws.com/models.huggingface.co/bert/bert-base-multilingual-cased.tar.gz),
[bert-base-chinese](https://s3.amazonaws.com/models.huggingface.co/bert/bert-base-chinese.tar.gz).


##### Please refer the paper below:
@article{zhang2021taxonomy,
  title={A taxonomy, data set, and benchmark for detecting and classifying malevolent dialogue responses},
  author={Zhang, Yangjun and Ren, Pengjie and de Rijke, Maarten},
  journal={Journal of the Association for Information Science and Technology},
  year={2021},
  publisher={Wiley Online Library}
}
        
        

