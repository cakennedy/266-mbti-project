## 266-mbti-project
 This git repo contains the work done to experiment with applying several NLP models to the problem of predicting Myers-Briggs Personality Type ( MBTI ) from a data set of posts taken from Typology Central.

### Navigation
 The repository consists of the following directories:
 .
├── background 					# Notebooks containing preliminary and exploratory work
|	 |____ archivednotebooks    # Original set of notebooks prior to reorganization
├── dataprep                    # Notebooks containing EDA, Data Cleaning and Resampling
├── models   					# Notebooks containing details of model implementations and analysis
|    |____ base					# Base Case Model notebook
|    |____ bert					# BERT Model notebooks, including CNN and multi-headed attention, tuning, feature impact
|	        |____featureimpact  # Comparison of the final BERT model with different subsets of features included_
|    |____ setfit				# SetFit Model notebooks
|	 |____ t5					# T5 Model notebooks           
├── LICENSE
└── README.md
|___PredictingPersonalityType.pdf_  # Write up of the project


### Contributors
<a href="https://github.com/cakennedy/266-mbti-project/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=cakennedy/266-mbti-project" />
</a>