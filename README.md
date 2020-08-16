# MDRDC（Malevolent Dialogue Response Detection and Classification） dataset and baselines

## The MDRDC dataset and baselines for malevolent dialogue detection and classification.

## Dataset
We would release our dataset and mTurk webpage design html files after the successful submission of the paper.
The whole dataset includes 6,000 dialogues.

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

#### BERT pretrained files download:
##### vocab
'bert-base-uncased': "https://s3.amazonaws.com/models.huggingface.co/bert/bert-base-uncased-vocab.txt",
'bert-large-uncased': "https://s3.amazonaws.com/models.huggingface.co/bert/bert-large-uncased-vocab.txt",
'bert-base-cased': "https://s3.amazonaws.com/models.huggingface.co/bert/bert-base-cased-vocab.txt",
'bert-large-cased': "https://s3.amazonaws.com/models.huggingface.co/bert/bert-large-cased-vocab.txt",
'bert-base-multilingual-uncased': "https://s3.amazonaws.com/models.huggingface.co/bert/bert-base-multilingual-uncased-vocab.txt",
'bert-base-multilingual-cased': "https://s3.amazonaws.com/models.huggingface.co/bert/bert-base-multilingual-cased-vocab.txt",
'bert-base-chinese': "https://s3.amazonaws.com/models.huggingface.co/bert/bert-base-chinese-vocab.txt".

##### pretrained BERT weights
'bert-base-uncased': "https://s3.amazonaws.com/models.huggingface.co/bert/bert-base-uncased.tar.gz",
'bert-large-uncased': "https://s3.amazonaws.com/models.huggingface.co/bert/bert-large-uncased.tar.gz",
'bert-base-cased': "https://s3.amazonaws.com/models.huggingface.co/bert/bert-base-cased.tar.gz",
'bert-large-cased': "https://s3.amazonaws.com/models.huggingface.co/bert/bert-large-cased.tar.gz",
'bert-base-multilingual-uncased': "https://s3.amazonaws.com/models.huggingface.co/bert/bert-base-multilingual-uncased.tar.gz",
'bert-base-multilingual-cased': "https://s3.amazonaws.com/models.huggingface.co/bert/bert-base-multilingual-cased.tar.gz",
'bert-base-chinese': "https://s3.amazonaws.com/models.huggingface.co/bert/bert-base-chinese.tar.gz".
