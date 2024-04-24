# METCS777-Term-Project-Team#11
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

## Environment Setup

Before executing the code for the Garbage Detection and Classification System, ensure that your environment is properly set up. Follow these steps:

1. **Operating System**: Confirm that you are using a compatible operating system. The system has been tested on Windows, Linux, and macOS.

2. **Python Installation**: Install Python 3.8 or later from [python.org](https://www.python.org/).

3. **Dependency Installation**: Install all required dependencies by running:
   ```bash
   pip install numpy pandas matplotlib torch torchvision opencv-python scikit-learn

# How to Run the Code

## Prerequisites

Before you begin, ensure you have met the following requirements:
* You have installed the latest version of Python 3.
* You have a `<Windows/Linux/Mac>` machine. State which OS is supported/required.
* You have read the project documentation.

## Running the Code

To run the code, follow these steps:

1. Clone the repository to your local machine: git clone https://github.com/maryambaizhigit/Term-Project-MET-CS-777-Garbage-Detection.git
2. Navigate to the cloned repository directory: cd Term-Project-MET-CS-777-Garbage-Detection
3. Install the required packages.
4. Run the scripts for each model.
5. Add any additional instructions if the code needs to be run with specific flags or configurations.

## Dataset Preparation
1. Download the TACO dataset from the above link.
2. Unzip the dataset into a directory named `data`.
3. The expected directory structure should be:
data/

├── annotations.json

└── batch_1/

└── batch_2/

...

5. Update the data loading paths in the scripts to match the location of your `data` directory.
6. Execute the scripts in your environment (anaconda-Jupyter Notebook):
   For CNN model, run `METCS777-term-project-code-sample-MaryamBaizhigitova-Team#11.ipynb`
   For Faster R-CNN model, run `METCS777-term-project-code-sample-KaiwenZhu-Team#11.ipynb`
   For SVM model, run `METCS777-term-project-code-sample-LinxinZhou-Team#11.ipynb`

7. If needed, modify any configuration files or flags as required by your experimental setup.

## Results of Running the Code

Upon running the different models with the TACO dataset, the following accuracies were observed:

- **CNN Model**: Achieved an accuracy of 43%. This model was particularly effective in identifying common types of garbage but struggled with items having irregular shapes or those partially obscured.

- **Faster R-CNN**: Recorded an accuracy of 8%. Despite being a powerful model for object detection, the lower accuracy might indicate issues with model training parameters or data preprocessing steps that need optimization.

- **SVM Model**: Obtained an accuracy of 21.5%. While SVMs are generally less effective for high-dimensional data like images, this accuracy shows it can still provide baseline insights.

Further analysis and tuning of the models are necessary to improve performance and reliability.

## Detailed Explanation of the Dataset and Results

The TACO dataset is specifically designed for advancing waste management solutions through computer vision technologies. It consists of annotated images of various garbage items found in urban settings, making it ideal for training and testing our garbage detection models.

### Dataset Composition
- The dataset includes images divided into batches (batch_1, batch_2, etc.).
- Annotations in JSON format provide details like object boundaries and categories.

### Model Evaluations
- **CNN**: Best suited for textured and color-based classifications. The accuracy indicates potential in routine garbage types but needs further tuning for complex scenarios.
- **Faster R-CNN**: Generally robust for spatial data analysis; however, the low performance suggests the need for enhanced feature extraction methods or more extensive training epochs.
- **SVM**: Limited by the high dimensionality of image data; future work could explore dimensionality reduction techniques or kernel tricks to enhance its effectiveness.

The disparity in model performances underscores the complexity of waste classification and the challenges in handling diverse and unpredictable environmental conditions.


## Authors
<b>Kaiwen Zhu, Maryam Baizhigitova, Linxin Zhou</b>
