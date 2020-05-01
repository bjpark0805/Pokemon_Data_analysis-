# Pokemon data analysis

## Overview

This package provides an implementation of Pokemon data analysis, which is orginated from [Michael Metter's kernal](https://www.kaggle.com/mmetter/pokemon-data-analysis-tutorial/notebook). 
I implemented this kernel by myself using Jupyter notebook, practicing my python skills, and basic data analysis. I found the missing values of the original data, calculate the battel record and winning percentage of the pokemons, and visulize the analysis using Matplotlib and Seaborn just like the original kernal. Moreover, I gave some additional comments for each cells for detailed explanations. 
Finally, I concluded the analysis with linear regression and SVM practice and PCA. 
These techniques could give the prediction and validation process of the analysis. 





The following four files have been newly created.
The first three files in the `script` directory automatically runs the main
script above for specific objectives such as to train teachers or students.
The last file `load_student.py` is the core module of this project which implements various
functions for compressing BERT via low-rank factorizations, including Tucker
decomposition and SVD.
The only public function in the file, `lobert_student()`,  is called by
`NLI_KD_training.py` to initialize compressed models.
All other functions are called only in `load_student.py`.      
- `scripts/finetune_teacher.py`
- `scripts/save_teacher_prediction.py`
- `scripts/train_student.py`
- `utils/load_student.py`

The tree structure of this project is given as follows:

``` Unicode
LoBERT
  ├── data
  │    ├── data_raw
  │    │     ├── glue_data: task dataset
  │    │     └── download_glue_data.py
  │    ├── models
  │    │     └── bert_base_uncased: ckpt
  │    └── outputs
  │          ├── LOBERT: save teacher model prediction & trained student model 
  │          └── KD: save fine-tuned BERT-base
  ├── src
  │    ├── bert
  │    │     ├── examples: BERT utils 
  │    │     ├── pytorch_pretrained_bert: BERT sturcture files
  │    │     └── tests: BERT test files
  │    ├── result
  │    │     └── glue/result_summary: save result_summaries for each hyperparameter
  │    ├── scripts
  │    │     ├── finetune_teacher.py : finetune teacher model for each task
  │    │     ├── save_teacher_prediction.py: save teacher prediction for all the layers 
  │    │     └── train_student.py: train student model 
  │    ├── utils
  │    │     └── load_student.py: create & initiate student model
  │    ├── envs.py: save directory paths for several usage
  │    ├── NLI_KD_training.py: comprehensive training file for teacher and student models
  └──  └── run_glue_benchmark.py: comprehensive prediction file for teacher and student models
```

#### Data description
- combats.csv
- pokemon.csv
- test.csv

* Note that: 
    * GLUE datasets consists of CoLA, diagnostic, MNLI, MRPC, QNLI, QQP, RTE, SNLI, SST-2, STS-B, WNLI
    * You can download GLUE datasets by LoBERT/data/data_raw/download_glue_data.py

## Install
* Python 3.7
* Numpy
* Matplotlib
* Seaborn
* Pandas

## Contact

- Bumjoon Park (qkrskaqja@snu.ac.kr)

