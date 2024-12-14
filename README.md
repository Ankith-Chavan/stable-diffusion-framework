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

Clone or Download the Repository:
Clone the repository or download the project folder containing the notebook file Stable_diffusion_Model.ipynb.

Set Up the Environment:
Ensure your system has a  GPU for faster processing.

Launch Jupyter Notebook:
Open the terminal and navigate to the project directory
Start Jupyter Notebook:
Open the file Stable_diffusion_Model.ipynb.

Execute the Notebook:
Run each cell sequentially by pressing Shift + Enter.

The notebook will:
Load the Stable Diffusion model.
Accept text prompts for image generation.
Display and save generated images to the output directory.

Modify Text Prompts (Optional):
Edit the text prompt cell in the notebook to generate images based on custom inputs.

Evaluate Model Performance:
After generating images, run the evaluation cells to calculate FID and IS metrics for the generated images.

Save and View Results:
All generated images and evaluation results are saved in the outputs directory.
