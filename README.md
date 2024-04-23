# Term-Project-METCS-777-Team#11
<h1 align="center" font-size:16px"><b>Garbage Detection and Classification system</b></h1>


## Introduction
The Garbage Detection and Classification System is designed to apply advanced machine learning techniques to accurately identify and categorize garbage items from images. It supports efficient waste sorting and management, promoting recycling efforts and environmental sustainability.

## Dependencies 
Ensure these libraries and frameworks are installed to run the project:
- Python 3
- NumPy
- Pandas
- Matplotlib
- PyTorch
- OpenCV
- Scikit-learn

## Goal of this Repository
This repository provides detailed analysis and implementation of machine learning models in Python, serving both educational purposes for those entering the field and as a resource for practitioners.

## Dataset
The project utilizes the [TACO (Trash Annotations in Context)](http://tacodataset.org/) dataset, which is a comprehensive dataset for garbage detection in the context of urban environments. The dataset includes a wide variety of waste in situ taken in diverse environments.

To replicate our results or use the TACO dataset for your own experiments, you can download it directly from the [TACO dataset download page](http://tacodataset.org/#download).

After downloading, please ensure to follow the dataset's directory structure as required by the scripts and Jupyter Notebooks in this repository.

## Dataset Preparation
1. Download the TACO dataset from the above link.
2. Unzip the dataset into a directory named `data`.
3. The expected directory structure should be:
data/
├── annotations.json
└── batch_1/
└── batch_2/
...
4. Update the data loading paths in the scripts to match the location of your `data` directory.

## Authors
<b>Kaiwen Zhu, Maryam Baizhigitova, Linxin Zhou</b>
