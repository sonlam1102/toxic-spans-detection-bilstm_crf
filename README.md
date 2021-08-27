# Toxic Spans Detection 

This project is for SemEval 2021 Task 5: Toxic Spans Detection   
Model used: BiLSTM-CRF and ToxicBERT 
+ BiLSTM-CRF: for toxic spans detection     
+ ToxicBERT: for toxic classificaion    

The dataset can be found here: https://github.com/ipavlopoulos/toxic_spans    

Publication:   
```
@inproceedings{luu-nguyen-2021-uit,
    title = "{UIT}-{ISE}-{NLP} at {S}em{E}val-2021 Task 5: Toxic Spans Detection with {B}i{LSTM}-{CRF} and {T}oxic{BERT} Comment Classification",
    author = "Luu, Son T.  and
      Nguyen, Ngan",
    booktitle = "Proceedings of the 15th International Workshop on Semantic Evaluation (SemEval-2021)",
    month = aug,
    year = "2021",
    address = "Online",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2021.semeval-1.113",
    doi = "10.18653/v1/2021.semeval-1.113",
    pages = "846--851",
    abstract = "We present our works on SemEval-2021 Task 5 about Toxic Spans Detection. This task aims to build a model for identifying toxic words in whole posts. We use the BiLSTM-CRF model combining with ToxicBERT Classification to train the detection model for identifying toxic words in posts. Our model achieves 62.23{\%} by F1-score on the Toxic Spans Detection task.",
}
```
