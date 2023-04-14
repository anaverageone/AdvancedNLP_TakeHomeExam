# AdvancedNLP_TakeHomeExam

Master of Text Mining, VU University 

Task: Evaluation on the capabilities of two pretrained models for Semantic Role Labeling (SRL)

Student:
Long Ma (2761790)

### Requirements 

please run the following cells to install all:
! pip install panda ! pip install allennlp-models

###  Two pretrained models are available at:

* structured-prediction-srl-bert - https://github.com/allenai/allennlp-models/blob/main/allennlp_models/modelcards/structured-prediction-srl-bert.json
* structured-prediction-srl - https://github.com/allenai/allennlp-models/blob/main/allennlp_models/modelcards/structured-prediction-srl.json

### Files

Current zip file holds following files for challenge dataset creation, classification experiment (2 pretrained models), and system validation (Failure rate). 
The gold lables and sample sentences from challenge data creation and system results from samples are saved in the folder called data and are then used for validation.

* Act_Pass_test.ipynb: a jupiter notebook that test the capability of dealing with active and passive variation.
* Cleft_test .ipynb: a jupiter notebook that test the capability of dealing with it-cleft construction.
* Polysemy_test.ipynb: a jupiter notebook that test the capability of distinguishing verbs with multiple meanings (some noun attribute).
* Proposition_test.ipynb: a jupiter notebook that test the capability of dealing with propositional variation.
* Robustness_test.ipynb: a jupiter notebook that test the robustness (adversarial examples, typos, etc.).
* Act_Pass_test.ipynb: a jupiter notebook that test the capability of dealing with active and passive variation sentences.
* Synonym_test.ipynb: a jupiter notebook that test the capability of dealing with synonym variation using VerbNet verb frame(cooking-45.3).

