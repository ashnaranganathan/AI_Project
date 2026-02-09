# AI_Project
# OWL-ViT Open-Vocabulary Object Detection Project

## Overview
This project implements the OWL-ViT (Open-Vocabulary Vision Transformer) model for object detection, based on the paper: [OWL-ViT Paper](https://arxiv.org/abs/2205.06230). The project demonstrates:

- Running the original OWL-ViT model
- Implementing a prompt-tuning improvement to enhance detection performance
- Visualizing object detection results on sample images

## Project Structure
AI_Project_OWL_ViT/
├── notebooks/
│ ├── owlvit_original.ipynb # Original OWL-ViT model inference
│ ├── owlvit_improved.ipynb # Model with prompt-tuning improvement
├── scenic/ # Cloned Scenic OWL-ViT repository
├── data/ # Sample images / dataset (optional)
├── results/ # Output images and evaluation plots
├── report/ # Project report PDF
├── presentation/ # Presentation slides


---

## Requirements
- Python 3.9+  
- Jupyter Notebook / JupyterLab  
- Libraries:
  - PyTorch: `torch`, `torchvision`  
  - Transformers: `transformers`  
  - Image processing: `Pillow`  
  - Visualization: `matplotlib`  

Install required libraries with:

```bash
pip install torch torchvision transformers pillow matplotlib

## How to Run
Open the notebooks in the `notebooks/` folder.  
The notebooks are **Jupyter Notebook** files, compatible with **Google Colab**.

1. Run `owlvit_original.ipynb` to test the original OWL-ViT model  
2. Run `owlvit_improved.ipynb` to see the prompt-tuning improvement in action  

Sample images and evaluation results are saved in the `results/` folder.  
For full replication, you can download the COCO dataset or provide your own images in the `data/` folder.

## Results
- Example images with detected objects and bounding boxes are provided  
- Comparisons between the original and improved models are visualized with plots in the `results/` folder  
- Improvements include better detection accuracy on unseen object categories

## Resources
- Project Report: `report/OWL-ViT_Report.pdf`  
- Presentation Slides: `presentation/OWL-ViT_Presentation.pptx`
