# Repo pour le projet module 2 pour CAS AML

## Proposed dataset : 
- https://www.kaggle.com/datasets/kshitizbhargava/deepfake-face-images/data

## Sources : 
https://pyimagesearch.com/2017/03/20/imagenet-vggnet-resnet-inception-xception-keras/ Some ImageNet models

https://github.com/i3p9/deepfake-detection-with-xception/blob/main/train_dateset.py Write-up with xception

https://ieeexplore.ieee.org/document/10363477 Paper about it

## Notebook structure

Exemple from M1:
1. Setup notebook with import and stuff
2. Load dataset
3. Visualize data within the dataset
4. Data Preprocessing
5. Feature Representation
6. Train Logistic Regression 
7. Visualise confusion matrix
8. Train Support Vector Machine SNM
9. Visualise confusion matrix
10. Direct Comparison


Exemple from M2:
1. Setup notebook with import and stuff
2. Load dataset
3. Visualize data within the dataset
4. Data Preprocessing
5. Feature Representation
6. Train CNN model
7. Visualize What CNN Learned
8. Per model Comparison

# Project Folder Structure
```
project_root/
│
├── notebooks/ # Jupyter notebooks (experiments, analysis, reports)
│ ├── <your-name>/ # Each contributor’s personal notebooks
│ │ ├── network_feature_extractor.ipynb
│ │ └── ...
│ ├── team_shared/ # Shared, polished notebooks
│ │ └── final_report.ipynb
│ └── README.md # Notebook usage & conventions
│
├── src/ # Reusable source code
│ ├── data_processing.py
│ ├── models/
│ │ └── feature_extractor.py
│ └── init.py
│
├── data/ # Data storage (ignored in Git if large)
│ ├── raw/ # Original datasets
│ ├── processed/ # Cleaned datasets
│ └── README.md
│
├── results/ # Outputs from experiments
│ ├── figures/
│ ├── metrics/
│ └── logs/
│
├── docs/ # Documentation and guides
│ └── simple_notebook_git_workflow.md
│
├── requirements.txt # Python dependencies
├── environment.yml # Conda environment (optional)
├── .gitignore # Ignore rules
└── README.md # Project overview
```

