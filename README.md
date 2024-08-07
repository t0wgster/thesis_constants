# Sensor Fusion of RGB and HSI Data - by Tony Wang

This repository contains all the program code used in the training, testing and evaluation of my Master Thesis 'Functional Comparative Analysis of Deep Learning Models for Sensor Fusion of RGB and Hyperspectral Imaging'

## Features
- Comparison of six different deep learning models
- Semantic Segmentation based on Unet Model
- 3x RGB Standalone Models and 1x HSI Standalone Model
- 1x Data-Level and 1x Feature-Level Sensor Fusion Model
- 3 Post Processing Techniques for Segmentation Masks

## Installation
Run the following lines:
```python
git clone https://github.com/t0wgster/TonyWang_MasterThesis.git
pip install -r requirements.txt
```

Optional  for CRF based post processing:
```python
pip install git+https://github.com/lucasb-eyer/pydensecrf.git
```

## Functions
- Dataset & Dataloader
- Training
- Evaluation and Visualisation
- Post Processing

## Testing
With the following Zip File, a trained model for RGB and Sensor Fusion for an image pair can be tested:
https://drive.google.com/file/d/1UPik9_YIMs3fvkkJN5kElUP8EHPxT2Ja/view?usp=sharing


