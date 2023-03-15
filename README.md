# Learning Adapters for Code-Switching Speech Recognition
This repository is developed under huggingface Framework



### Requirements
#### python 3.8.10
- datasets >= 1.18.0
- torch >= 1.5
- torchaudio
- librosa
- jiwer
- evaluate
- numpy
- pandas
- jieba
- editdistance
- tensorboard
- fairscale
- seaborn
- accelerate
- spacy

## Installatation
1. Install huggingface
```
> cd transformers
> pip install -e .
```


## dataset  and pretrained weight

* dataset
```
MLLAB-public (\\mllab.asuscomm.com)W:\Chun-Yi_He\ASR_data\NTUT\dataset_NTUT
MLLAB-public (\\mllab.asuscomm.com)W:\Chun-Yi_He\ASR_data\ASCEND
```
* pretrained weight
```
MLLAB-public (\\mllab.asuscomm.com)W:\Chun-Yi_He\pretrained_weight
```
## FIle structure
```
|_ /ASCEND/
  |_ dataset_NTUT (NTUT AB01 dataset)  
  |_ waves (ASCEND dataset)
  |_ pretrained_weight
```

## Model training 
```
> cd examples/pytorch/speech-recognition/ASCEND/
> pip install -r requirements.txt
> bash run_train.sh
```
## Model inference
```
python inference.py
```

