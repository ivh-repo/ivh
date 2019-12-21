# What is AutoPrognosis?
AutoPrognosis is an algorithmic framework for automating the design of machine learning based clinical prognostic models<sup>1</sup>. Helps in choosing which algorithms to use and tune parameters.

# Source code of AutoPrognosis
https://github.com/ahmedmalaa/AutoPrognosis 

# Data set used
UK Biobank dataset (http://www.ukbiobank.ac.uk/register-apply/). 
Dataset contains data from a prospective cohort study group of 423,604 participants without CVD.

# Components of AutoPrognosis<sup>1</sup>. 
* Data set
* Data imputation algorithm
* Feature extraction algorithms
* Classification algorithms
* Calibration
* Clinical interpretation

For schematic of algorithm refer this [link](https://journals.plos.org/plosone/article/file?id=10.1371/journal.pone.0213653&type=printable)

# How it works?
Uses an advanced Bayesian optimization technique for designing a prognostic model made out of a weighted ensemble of machine learning pipelines.
Each pipelines means different combination of algorithms for each of the components(for imputation, feature extraction and classification).
Design space of autoprognosis contains following<sup>1</sup>: 
  * 7 imputation algorithms
  * 9 feature processing algorithms
  * 20 classification algorithms
  * 3 calibration methods

Combining above components AutoPrognosis contains 5460 machine learning pipelines<sup>1</sup>.


# Comparison of other risk predictor algorithms with AutoPrognosis
Out of 4801 CVD cases recorded within 5 years baseline, AutoPrognosis could predict 368 more cases compared to Framingham score.

# How to run AutoPrognosis?

# References
1. Alaa, Ahmed M., et al. "Cardiovascular disease risk prediction using automated machine learning: A prospective study of 423,604 UK Biobank participants." PloS one 14.5 (2019): e0213653.[Link!](https://journals.plos.org/plosone/article/file?id=10.1371/journal.pone.0213653&type=printable)
