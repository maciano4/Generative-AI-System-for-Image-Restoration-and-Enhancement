# Generative-AI-System-for-Image-Restoration-and-Enhancement
Photos are a memory of or past and everytime I take a photo, i want it to tell a story. How well that story can be depends on certain factors like the camera resolution, the weather and more.Remember that picture you took so many years ago, but today the picture can't tell it's story. That is why this project Generative AI System for Image Restoration and Enhancement is aimed at recreating that story for you. 

# Overview

This project is developed as part of the AAI-521 Final Team Project (Extra Credit). The goal is to build an AI-driven system that restores and enhances old, damaged, or low-resolution images using Generative AI models from Hugging Face. The system performs four key enhancement tasks:

Image Denoising – Remove unwanted noise while preserving essential details.

Image Super-Resolution – Enhance resolution and image clarity.

Image Colorization – Convert grayscale images into colorized versions.

Image Inpainting – Fill missing or damaged regions seamlessly.

# Features

Uses pre-trained models (DDPM, Real-ESRGAN, Colorization Transformer, Stable Diffusion Inpainting).

Modular architecture allowing each enhancement task to run independently.

Easily extendable for fine-tuning or transfer learning.

Ready for deployment via Flask or Streamlit.

# Project Structure

ImageRestoration_ai.ipynb
image_restoration_ai.ipynb # Main notebook (implementation)
README.md # Project documentation
requirements.txt # Dependencies
static/ # Web UI assets (optional)
app.py # Flask web interface (optional)
samples/ # Example images (input/output)

# Install dependencies
pip install -r requirements.txt 
# Clone the repository
git clone https://github.com/maciano4/ImageRestorationAI.git
cd ImageRestorationAI
