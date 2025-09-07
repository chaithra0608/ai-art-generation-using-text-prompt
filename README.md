Stable Diffusion Image Generator

This project demonstrates a cloud-based Stable Diffusion image generation pipeline using Google Colab, Hugging Face, and Gradio. The methodology is structured for reproducibility, interactivity, and efficiency.

🌟 Features
Cloud Execution via Google Colab (no local setup required)
Model Hosting using Hugging Face for easy access to pre-trained weights
Interactive Interface with Gradio: input prompts, sliders, and negative prompts
GPU-Optimized image generation for faster results
Persistent Storage of generated images in Google Drive

🛠️ Methodology
The project is structured into eight key phases:
Requirement Analysis: Selected Google Colab for execution, Hugging Face for model hosting, and Google Drive for storage.
Setup: Installed essential libraries: PyTorch, Transformers, Diffusers, and Gradio.
Authentication: Used a Hugging Face token to access Stable Diffusion model weights securely.
Model Loading: Loaded the Stable Diffusion pipeline in half precision for GPU efficiency.
Prompt Input: Provided multiple input methods: Python input() and Gradio textbox, Supported negative prompts to control image output.
Image Generation: 
  Tunable parameters include:
    Inference steps
    Guidance scale
    Seed for reproducibility
Saving Outputs: Generated images are stored in a dedicated Google Drive folder for persistence.
Interface Development: Launched a Gradio interface with textboxes and sliders for interactive testing.

🚀 How to Run:
Open the Google Colab notebook
Install required libraries (already included in the notebook)
Authenticate with your Hugging Face token
Enter prompts in the interface and adjust sliders as needed
Generate images and view them directly or save to Google Drive

💡 Notes
Fully reproducible in academic or research settings
Designed for ease of use and GPU optimization
Supports both positive and negative prompts for precise image control

📌 Credits
Hugging Face – Pre-trained Stable Diffusion models
Google Colab – Cloud-based execution
Gradio – Interactive web interface
