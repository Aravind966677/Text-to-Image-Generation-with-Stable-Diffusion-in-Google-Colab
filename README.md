# Text-to-Image-Generation-with-Stable-Diffusion-in-Google-Colab

# Stable Diffusion in Google Colab

## Overview
This project demonstrates how to use the **Stable Diffusion** model to generate images from text prompts in **Google Colab**. Stable Diffusion is a text-to-image model capable of creating high-quality images based on natural language descriptions.

This repository provides a simple script that runs on **Google Colab**, allowing you to generate images without needing to install anything locally or set up complex environments. It uses the `diffusers` library to load a pre-trained model and generate images directly from textual prompts.

## Prerequisites
- **Google Colab**: You can run the notebook on Colab without the need for local hardware setup.
- **GPU (optional)**: A GPU is recommended for faster image generation, but CPU will work as well (with slower performance).

## Setup Instructions

### 1. Open Google Colab
   - Go to [Google Colab](https://colab.research.google.com/).
   - Create a new notebook by selecting `New Notebook`.

### 2. Install Required Libraries
   To install the necessary libraries, run the following code in a Colab cell:
   ```python
   !pip install diffusers transformers accelerate torchvision
