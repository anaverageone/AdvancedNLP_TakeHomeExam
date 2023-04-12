# AdvancedNLP_TakeHomeExam

Master of Text Mining, VU University Task: Named Entity Recognition

Student:
Long Ma (2761790)

###requirements please run the following cells to install all:

! pip install pandas ! pip install sklearn ! pip install gensim ! pip install numpy

Files

Current zip file holds following files for feature extraction, classification experiment, hyper-parameter tuing, feature ablation, and final system validation:

NER_Preprocess.ipynb: a jupiter notebook to pre-process original training (conll2003.train.conll), devlopment (conll2003.dev.conll), and test (conll2003.test.conll). Output is used in Experiment.ipynb for training the classifiers and validating (testing) the system.

Experiment.ipynb: a jupiter notebook containing all functions for feature extraction, classification experiment, hyper-parameter tuing, feature ablation, and final system validation.

word_embedding_basic_system.ipynb: a jupiter notebook to incoporate word embeddings and one-hot encoding as feature representation for system experiment.
