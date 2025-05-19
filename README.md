# Generative-AI-With-Ui
# 🎛️ Generative AI with Blockchain

A powerful multi-modal Generative AI system that supports text, image, audio, video, and PowerPoint (PPT) generation using a unified user interface (UI). This system is designed for seamless execution in Google Colab and supports future integration with blockchain for enhanced content security and traceability.

---

## 🚀 Features

| Function           | Description                                                                 |
|--------------------|-----------------------------------------------------------------------------|
| 📝 Text Generator   | Uses Google's Gemini Pro to generate text based on user prompts             |
| 🖼️ Image Generator  | Uses Stable Diffusion to generate high-quality images from text             |
| 🎤 Audio Generator  | Converts text to speech using Coqui TTS or gTTS                             |
| 🎥 Video Generator  | Creates short videos using ZeroScope or similar latent diffusion models     |
| 📊 PPT Generator    | Fetches content from Wikipedia and builds a presentation using python-pptx |
| 🧑‍💻 UI Interface    | Fully integrated Gradio interface with input/output display and download    |

---

## 🧠 Tech Stack

- Python 3.x
- Gradio (for interactive UI)
- PyTorch (for model inference)
- Hugging Face Diffusers (Stable Diffusion, Video models)
- Google Generative AI SDK (Gemini Pro)
- Coqui TTS / gTTS
- Wikipedia API
- python-pptx
- Google Colab (recommended execution environment)

---

## 📦 Installation

To run this project, install the required dependencies:

```bash
!pip install numpy --upgrade --force-reinstall
!pip install torch --upgrade
!pip install transformers --upgrade
!pip install diffusers --upgrade
!pip install wikipedia requests librosa pathlib python-pptx TTS pillow google-generativeai gTTS

import os
os.kill(os.getpid(), 9)
pip install torch wikipedia requests python-pptx Pillow diffusers transformers TTS numpy google-generativeai gTTS gradio 
