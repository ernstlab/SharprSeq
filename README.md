# SHARPR-seq

## Overview

SHARPR-seq is a computational method for integrating DNA sequence predictions with Sharpr-MPRA reporter tiling data, aimed at high-resolution mapping of regulatory activity within genomic regions. This repository contains the source code and documentation for SHARPR-seq as described in our manuscript.

## Installation

Clone the repository:
```
git clone https://github.com/ernstlab/SharprSeq.git
```

Install dependencies:
```
pip install -r requirements.txt
```

## Usage

- `notebooks/01_download_and_preprocess_sharpr_data.ipynb`: Jupyter Notebook for downloading and preprocessing Sharpr-MPRA data.
- `notebooks/02_compute_scores.ipynb`: Jupyter Notebook for computing SHARPR-seq scores from preprocessed Sharpr-MPRA data and the `MPRA-DragoNN/DeepFactorizedModel` sequence model [1].

[1] Movva, R. et al. Deciphering regulatory DNA sequences and noncoding genetic variants using neural network models of massively parallel reporter assays. PLoS One 14, e0218073 (2019).
