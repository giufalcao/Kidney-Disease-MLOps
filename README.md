## Kidney Disease Classification
This project focuses on the classification of kidney diseases using deep learning and computer vision techniques. I have developed a complete pipeline covering:
1. Data Ingestion
2. Data Transformation
3. Model training
4. Model evaluation. 


## Workflows

1. Update config.yaml
2. Update secrets.yaml [Optional]
3. Update params.yaml
4. Update the entity
5. Update the configuration manager in src config
6. Update the components
7. Update the pipeline 
8. Update the main.py
9. Update the dvc.yaml
10. app.py

# How to run?

## Step 1: Clone the repository

```bash
git clone https://github.com/giufalcao/Kidney-Disease-MLOps.git
```
## Step 2 - Create a Python environment after opening the repository

```bash
conda create -n kidney_mlops python=3.8 -y
conda activate kidney_mlops
```

## Step 03 - Install the requirements
```bash
pip install -r requirements.txt
```

# Dataset Information

## Context
CT KIDNEY DATASET: Normal-Cyst-Tumor and Stone

## Dataset Descrpition
The dataset was collected from PACS (Picture archiving and communication system) from different hospitals in Dhaka, Bangladesh where patients were already diagnosed with having a kidney tumor, cyst, normal or stone findings. Both the Coronal and Axial cuts were selected from both contrast and non-contrast studies with protocol for the whole abdomen and urogram. The Dicom study was then carefully selected, one diagnosis at a time, and from those we created a batch of Dicom images of the region of interest for each radiological finding. Following that, we excluded each patient's information and meta data from the Dicom images and converted the Dicom images to a lossless jpg image format. After the conversion, each image finding was again verified by a radiologist and a medical technologist to reconfirm the correctness of the data.

The dataset contains 12,446 unique data within it in which the cyst contains 3,709, normal 5,077, stone 1,377, and tumor 2,28

## How to get the dataset: 

1. Download the data by clicking [HERE](https://www.kaggle.com/datasets/nazmul0087/ct-kidney-dataset-normal-cyst-tumor-and-stone/data).


2. Check if the data is zipped and separed by kidney classification.


## Technology Stack
### Frontend:
- Nextjs 14
- TypeScript
- TailwindCSS
- Shadcn.UI

### Backend:
- Python
- DVC
- MLFlow
- Deep Learning & Computer Vision
- Transformers & HuggingFace
- Flask
- OOP Principles