# Oracle Vendor Classification

This repository houses the code for the vendor classification approach using Supervised Contrastive Learning.

## Dataset

The folder `dataset` hosts 2 datasets in `json` format:
- `dataset.json`, which is the original data.
- `dataset_1500_seq_length`, which is the original data truncated to contain a fixed sequence length of 1,500 behaviors per vendor profile.

## Requirements

* Run: `pip install -r requirements.txt`.

## Running

Execute the notebook cells sequentially in `vendor_classification.ipynb`.