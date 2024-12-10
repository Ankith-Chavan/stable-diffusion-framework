# Stable Diffusion Model GenAI

This project implements a Stable Diffusion-based framework for generating high-quality, photorealistic images from text descriptions. It evaluates performance using Frechet Inception Distance (FID) and Inception Score (IS), ensuring image diversity and quality. The framework addresses scalability, stability, and diversity limitations of traditional generative models.

---

## Features
- **Image Generation**: Generate photorealistic images from textual prompts using Stable Diffusion.
- **Evaluation Metrics**: Measure performance with FID and IS for generated images.
- **Scalability and Stability**: Overcomes limitations of traditional generative models like GANs.
- **Preprocessing Tools**: Resize, validate, and process images for evaluation.

---

## Requirements
Before running the code, ensure you have the following installed:
- Python 3.8 or higher
- PyTorch
- Hugging Face Diffusers
- Transformers
- Matplotlib
- PIL (Pillow)
- Datasets
- tqdm
- pytorch-fid (for FID and IS calculations)

Install the required dependencies:
```bash
pip install -r requirements.txt
