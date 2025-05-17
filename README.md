# 🖼️ Text-to-Image Generator with Stable Diffusion

A lightweight text-to-image application using **Stable Diffusion Turbo**, built with a user-friendly flow. Type in your imagination as a prompt, and watch it turn into AI-generated art — no GPU or complex setup required.

---

## ⚙️ Key Features

- Integration with `stabilityai/sd-turbo` (Stable Diffusion Turbo)  
- Clean and minimal Google Colab-based interface  
- CPU-friendly and easy to run  
- Adjustable inference steps and guidance scale  
- Auto-resizing and saving of generated images  
- Displays generated output within the notebook

---

## 🧩 Workflow Overview

### 🔤 1. Text Input  
Enter any descriptive prompt (e.g., _"A dog is painting a sunset"_).

### 🧠 2. Model Setup  
Loads `sd-turbo` via `StableDiffusionPipeline` from Hugging Face's diffusers library.

### 🎨 3. Image Generation  
Processes the text and produces an image in around 15 steps using latent diffusion.

### 🖼️ 4. Display & Save  
Final image is resized, displayed in the notebook, and saved as a PNG (`generated_image.png`).

---

## 🔧 Configuration Options

| Setting          | Default   | Description                                |
|------------------|-----------|--------------------------------------------|
| Inference Steps  | 15        | Number of steps for image refinement       |
| Image Size       | 256x256   | Output resolution                          |
| Guidance Scale   | 5         | Controls how closely output matches prompt |
| Device           | CPU       | Auto-selected, runs without GPU            |
| Save Format      | PNG       | Saved locally with fixed filename          |

---


