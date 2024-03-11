## Kidney Disease Classification
This project focuses on the classification of kidney diseases using deep learning and computer vision techniques. We have developed a complete pipeline encompassing data ingestion, transformation, model training, and evaluation. The project leverages technologies such as Next.js, TypeScript, TailwindCSS for the frontend, and Python, Flask, mlflow, DVC for the backend.

### Frontend URL: https://kidney-disease-classification.vercel.app/
### Backend URL: 
- (Model Notebooks can be found in Research Folder)
- (Model Results can be found in Results Folder)

## Features
- Comprehensive data processing and transformation pipeline.
- Multiple deep learning, Transformers and machine learning models for comparative analysis.
- Complete backend implementation in Flask with logging, custom exception handling, and class-based modular coding following OOPs principles.
- Frontend developed using Next.js, TailwindCSS, TypeScript and Shadcn.UI for a seamless user experience.

## Dataset Information

### Context
CT KIDNEY DATASET: Normal-Cyst-Tumor and Stone

### Content
The dataset comprises 12,446 unique data points, including 3,709 cyst, 5,077 normal, 1,377 stone, and 2,283 tumor findings. It was collected from PACS from various hospitals in Dhaka, Bangladesh. After thorough selection and anonymization processes, the images were converted to a lossless jpg format and verified by medical professionals.

### Dataset Link: https://www.kaggle.com/datasets/nazmul0087/ct-kidney-dataset-normal-cyst-tumor-and-stone/data

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
### STEPS:

Clone the repository

```bash
git clone https://github.com/giufalcao/Kidney-Disease-MLOps.git
```
### STEP 01- Create a Python environment after opening the repository

```bash
conda create -n kidney_mlops python=3.8 -y
conda activate kidney_mlops
```

### STEP 02- install the requirements
```bash
pip install -r requirements.txt
```
