# What is AutoPrognosis?
AutoPrognosis is an algorithmic framework for automating the design of machine learning based clinical prognostic models[1]. Helps in choosing which algorithms to use and tune parameters.

# Source code of AutoPrognosis
https://github.com/ahmedmalaa/AutoPrognosis 

# Data set used
UK Biobank dataset (http://www.ukbiobank.ac.uk/register-apply/). 
Dataset contains data from a prospective cohort study group of 423,604 participants without CVD.

# Components of AutoPrognosis. (for schematic refer to 'AutoPrognosis.docx' file)
	Data set
	Data imputation algorithm
	Feature extraction algorithms
	Classification algorithms
	Calibration
	Clinical interpretation

# How it works?
Uses an advanced Bayesian optimization technique for designing a prognostic model made out of a weighted ensemble of machine learning pipelines.
Each pipelines means different combiination of algorithms for each of the components(for imputation, feature extraction and classification).

# Comparison of other risk predictor algorithms with AutoPrognosis
Out of 4801 CVD cases recorded within 5 years baseline, AutoPrognosis could predict 368 more cases compared to Framingham score.

# How to run AutoPrognosis?

