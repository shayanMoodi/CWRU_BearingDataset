# CWRU_BearingDataset
This repository contains code for analyzing and processing the Case Western Reserve University (CWRU) Bearing Dataset. The CWRU dataset is widely used for fault diagnosis and prognostics of rotating machinery. This code facilitates the loading, filtering, and preparation of the dataset for machine learning tasks.
## Features
. Data Loading: Utilities to download and load the CWRU Bearing Dataset.

. Filtering and Extraction: Functions to filter and extract relevant features from the dataset, such as DE (Drive End) and FE (Fan End) vibration signals.

. Fault Classification: Mapping of different fault types and their severity for classification tasks.

. Preprocessing: Shuffling and preprocessing functions to prepare the data for machine learning models.
## Usage
1. Data Loading: Automatically download and load the .mat files from the CWRU repository.
2. Filtering: Extract DE and FE time series data using regular expressions.
3. Fault Mapping: Classify different types of bearing faults and their severity levels.
4. Preprocessing: Shuffle and preprocess the dataset to prepare it for training machine learning models.
## Dependencies
. Python 3.x
. NumPy
. SciPy
. scikit-learn
