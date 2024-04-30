# Requirements

Python 3.11

# Folder structure

```
.
├── train/
│   ├── <Class1>/
│   │   ├── img1.tif
│   │   ├── img2.tif
│   │   ├── ...
│   │   └── imgN.tif
│   ├── <Class2>/
│   │   ├── img1.tif
│   │   ├── img2.tif
│   │   ├── ...
│   │   └── imgN.tif
│   ├── ...
│   └── <ClassN>/
│       ├── img1.tif
│       ├── img2.tif
│       ├── ...
│       └── imgN.tif
└── test/
    ├── <Class1>/
    │   ├── img1.tif
    │   ├── img2.tif
    │   ├── ...
    │   └── imgN.tif
    ├── <Class2>/
    │   ├── img1.tif
    │   ├── img2.tif
    │   ├── ...
    │   └── imgN.tif
    ├── ...
    └── <ClassN>/
        ├── img1.tif
        ├── img2.tif
        ├── ...
        └── imgN.tif
```

Folder names are used as class labels.

# Installation

1. `git clone` the repo
2. `python -m venv .venv` to create a new virtual environment (recommended)
3. Activate virutal environment (differs by OS, check accordingly)
4. `pip install -r requirements.txt` to install required packages

# Usage

`SVM_baseline.ipynb` : This notebook contains the baseline SVM implementation using scikit-learn library

`CNN_DL.ipynb` : This notebook contains the CNN implementation using tensorflow