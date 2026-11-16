# Dataset

This project uses the **Wisconsin Diagnostic Breast Cancer (WDBC)** dataset.

Download the original data file, `wdbc.data`, from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/17/breast+cancer+wisconsin+diagnostic) and place it in this directory.

The notebook expects the file at:

```text
data/wdbc.data
```

The raw dataset is not committed to this repository. The notebook defines the 32 columns (ID, diagnosis, and 30 numeric measurements), maps `B` to 0 and `M` to 1, and excludes the identifier from the feature matrix.
