# Attribute Alignment of Temporal Knowledge Graphs via Attribute Embedding and Similarity Calculation

## Dependencies

* Python 3.x
* PyTorch >= 1.0
* Scikit Learn
* huggingface/transformers == 1.1.0

## Code

1. Run the following script to train.

```bash
# Example
>> python train.py --gpu_id 0 --channel Literal --dataset DWY100k/wd_dbp
```
2. Run the following script for ensemble.

```bash
# Example
>> python ensemble.py --gpu_id 0 --dataset DWY100k/wd_dbp --svm [or not] 
```

Datasets: { DWY100k/wd_dbp, DWY100k/yg_dbp}

## Datasets

Download the datasets from [OneDrive](https://1drv.ms/u/s!AuQRz5abAH5T2jDOmiMlkqFP8s0Z?e=V6wNWS) and unzip it under the current folder.
