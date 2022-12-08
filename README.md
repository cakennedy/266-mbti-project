## 266-mbti-project
 This git repo contains the work done to experiment with applying several NLP models to the problem of predicting Myers-Briggs Personality Type ( MBTI ) from a data set of posts taken from Typology Central.

### Repository Navigation
 The repository consists of the following directories and files:

Directory  |  Contents
-----------| -------------
background | This directory contains interim and scratch versions of our work, created throughout the project.
dataprep   | This directory contains data preparation files, including EDA of the database, data cleaning and resampling.
models     | This directory contains implementation of our base, BERT, SetFit and T5 models.  Notebooks show model train/validation/testing and analysis.
models/base  | This directory contains implementation & analysis of our base model.
models/BERT  | This directory contains implementation & analysis of our BERT model.  It shows several evolving versions of the model.
models/BERT/featureimpact  | This directory contains our BERT model run with different subsets of features to determine the relative impact of our feature set.
models/SetFit  | This directory contains implementation & analysis of our SetFit model.  
models/T5  | This directory contains implementation & analysis of our T5 model.
