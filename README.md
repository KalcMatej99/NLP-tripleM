# NLP-tripleM
Repository of team TripleM for NLP @ UL FRI. Project 3:Cross-lingual sense disambiguation

Students: Matej Miočić, Marko Ivanovski, Matej Kalc

## Folder structure
 - Reports and additional material for showing our work is present in folder `Reports`.
 - Source code with jupyter notebooks are in  `src` which is divided into:
    - `corpus`: code for obtaining corpus; See demo of corpus [here](./src/corpus/demo.ipynb)
    - `pretrained models`: some pre-trained models which we were able to upload on github
    - `results`: a bunch of results used for analysis on non-contextual embeddings
    - `web scrapper`: the scrapper for obtaining homonyms from fran.si
    - `non contextual embeddings` and `contextual embeddings` contain code for the mentioned embeddings clusters, scores, analysis
    - `classification` for classifying with clusters and annotated sentences

## Before running the code

Before running the code please install the requirments in `requirements.txt`. If you experience any problems with downloading AllenNLP run the following command:
```
pip3 install allennlp
```

### Downloading models and corpus  
1. In order work with our corpus you need to download it from [here](https://drive.google.com/drive/folders/1yzRX4mhToohfWD1Dj3iGY8facWCvnNK_?usp=sharing).

2. To work with Word2Vec you need to download the embeddings from [here](http://vectors.nlpl.eu/repository/).

3. To work with fastText you need to download the embeddings from [here](https://fasttext.cc/docs/en/crawl-vectors.html).

4. ELMo pretrained weights can be found [here](https://www.clarin.si/repository/xmlui/handle/11356/1277).

4. Finally, sloBERTa can be download from [here](https://www.clarin.si/repository/xmlui/handle/11356/1397).


## Report

Click [here](./TripleM_report.pdf) to open the report.
