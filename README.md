# Skimlit
# PubMed 20k RCT Dataset

## Overview
This repository contains the PubMed 20k RCT dataset, a subset of the PubMed 200k RCT dataset, where all numerical values have been replaced with the "@" symbol. The dataset is designed for natural language processing tasks related to medical literature.

## Dataset Structure
The dataset is organized into the following folders:

- `PubMed_20k_RCT_numbers_replaced_with_at_sign/`
 - `train.zip`: Compressed training set with numerical values replaced by "@"
 - `validation.txt`: Validation set with numerical values replaced by "@"
 - `test.txt`: Test set with numerical values replaced by "@"

## Usage
1. Uncompress the `train.zip` file using a suitable compression utility (e.g., 7-Zip, Keka, p7zip).
2. Load the dataset files (`train.txt`, `validation.txt`, `test.txt`) into your preferred data processing pipeline.
3. Note that all numerical values in the dataset have been replaced with the "@" symbol.

## Additional Notes
- The `PubMed_20k_RCT` dataset is a subset of the larger `PubMed_200k_RCT` dataset.
- The `PubMed_200k_RCT` dataset is available in two versions: with original numerical values and with numerical values replaced by "@".
- The `train.7z` file in the `PubMed_200k_RCT` folder has been compressed due to GitHub's file size limit.
