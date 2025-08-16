# Text-to-Image Generator 🎨

A Python-based project using Stable Diffusion to generate images from text prompts. Built with `diffusers`, `transformers`, and Gradio for a user-friendly interface.

## Features ✨
- Generate high-quality images from text prompts.
- GPU-accelerated (CUDA support).
- Interactive Gradio web interface.

## Installation 🛠️
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/text-to-image-generator.git
   cd text-to-image-generator

## Install dependencies
pip install -r requirements.txt

## Usage 🚀
1:Run the Jupyter notebook or Python script:
jupyter notebook Text_to_Image_Generator.ipynb
2:Enter a text prompt (e.g., "A futuristic city in the clouds").

3:View/download the generated image.
## Demo 🌐
Try the Gradio interface locally:
import gradio as gr
gr.Interface(fn=generate_image, inputs="text", outputs="image").launch()
