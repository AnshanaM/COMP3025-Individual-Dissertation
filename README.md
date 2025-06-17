# COMP3025-Individual-Dissertation
 Generalisation in Pedestrian Detection: A  Comprehensive Benchmarking of CNNs and ViTs  Across Diverse Datasets
# Evaluation Script and Finetuned Models

This folder contains the **main evaluation script** for the project of the finetuned models.

---

## 1. Demonstration & Evaluation

To run the demonstration or understand the model evaluation process, open the following Jupyter notebook:
performance-evaluation.ipynb


This notebook contains:

- Step-by-step instructions for running evaluations
- Code to load and test each finetuned model
- Visual output of results and performance metrics

---

## 2. Models (Google Drive Folder)

The Google Drive folder contains:

- `.pth` files — PyTorch model checkpoints
- Each model was finetuned on a selected dataset

These models can be directly loaded and evaluated using the provided notebook.

---

## 3. API Keys and Tokens

To run the **RF-DETR** and **YOLOv11** models, the following are required:

- A **Hugging Face token**
- A **Roboflow API key**

These should be saved as secrets in your **Google Colab Notebook environment**.

Please refer to the `performance-evaluation.ipynb` notebook for:

- Instructions on generating these keys
- How to store them in Colab secrets
- How to integrate them into the evaluation pipeline

---

## 4. Evaluation Output (Google Drive Folder)

Also located in the Drive link above is the following directory:
evaluation-output/

---

Make sure to download the models from Drive, configure your API tokens, and run everything through the provided notebook for a smooth evaluation workflow.

