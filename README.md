<div align="center">

# 🧠 Introduction to Generative AI (GenAI)

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![Keras](https://img.shields.io/badge/Keras-D00000?style=for-the-badge&logo=keras&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white)

*A comprehensive exploration of Generative AI, transitioning from theoretical foundations to building and training advanced generative models like Autoencoders, VAEs, GANs, and simulating Diffusion Models.*

---

</div>

## 📑 Repository Structure

This repository is divided into progressively advanced sessions, moving from high-level GenAI concepts to practical deep learning implementations using TensorFlow/Keras and OpenCV.

### 📖 What is GenAI?
- A theoretical introduction to Generative AI as a creative synthesizer rather than a data analyzer.
- Explores real-world GenAI applications (ChatGPT, Midjourney) and dissects modern features inside popular apps (like Instagram AI filters and YouTube summaries).
- Demonstrates how Large Language Models (LLMs) mathematically synthesize unique outputs (e.g., generating original poetry) instead of simply retrieving existing text.

### ⚖️ Comparison with traditional AI/ML
- Contrasts Traditional AI (predictive, rigid, based on fixed labels) against Generative AI (creative, highly flexible, interactive).
- Analyzes existing recommendation engines (like Zomato and Spotify) and explores how GenAI could transform them into dynamic, real-time synthesis engines (e.g., an "Infinite Personalized Radio").
- Compares traditional rule-based chatbots against context-aware, highly adaptable GenAI support agents.

### 🤖 SESSION 1 - Introduction to Generative Models
- Compares Discriminative Models (predicting boundaries) vs Generative Models (learning distributions).
- Proposes GenAI feature upgrades for popular apps (Zomato, Instagram, Flipkart).
- Explores image synthesis and AI-driven marketing copy generation.

### 🖼️ SESSION 2 - Autoencoders & Variational Autoencoders (VAE)
- **Simple Autoencoder:** Built and trained a Keras dense autoencoder on the Fashion MNIST dataset, visually comparing MSE vs. Binary Crossentropy (BCE) reconstruction quality.
- **Image Denoising:** Programmatically corrupted images with Gaussian noise and used the trained autoencoder to clean and restore them.
- **Variational Autoencoder (VAE):** Implemented a custom VAE with a sampling layer, training it to encode images into a continuous latent space. Used the decoder to sample mathematical points and synthesize entirely new clothing items.

### ⚔️ SESSION 3 - Generative Adversarial Networks (GANs)
- **Mathematical Simulation:** Wrote a simple_generator() to synthesize fake 28x28 image arrays and a programmatic Discriminator class that evaluates mean pixel brightness to detect fakes.
- **Adversarial Loop:** Simulated a complete adversarial training step by passing generated noise through the discriminator and evaluating the probability scores.
- **Architecture Research:** Explored real-world GAN applications (Prisma, NVIDIA Canvas) and analyzed the structural differences between DCGAN, StyleGAN, and CycleGAN.

### 🌌 SESSION 4 - Diffusion Models (Stable Diffusion Intro)
- **Forward Diffusion:** Implemented a Python script to recursively inject Gaussian noise into a clean image over 10 steps, simulating the forward corruption process of diffusion models.
- **Reverse Diffusion Approximation:** Used OpenCV median blurring to approximate algorithmic denoising on heavily corrupted images.
- **Stable Diffusion:** Triggered a live Stable Diffusion generation of a futuristic cyberpunk cricket stadium, saving the resulting artwork directly into the repository.
- **Ethics & Risks:** Addressed the dangers of deepfakes and mass style theft, highlighting mitigation strategies like SynthID watermarking and Opt-Out data registries.

### 🏭 SESSION 5 - Applying Generative Models in Industry
- **Text Summarization:** Leveraged ChatGPT to condense a 3-paragraph news article about an intense IPL cricket final down to a single paragraph summary (ipl_summary.txt).
- **Q&A Chatbots:** Programmed a programmatic Python response generator that mimics a Zomato-style restaurant bot.
- **Food Image Synthesis:** Used advanced prompt engineering to generate a vibrant, 8k resolution image of a *Sci-Fi Cyberpunk Gujarati Thali*.
- **AI Code Generation:** Demonstrated how to use LLMs (Copilot/ChatGPT) to algorithmically write Python list-comprehension filters for Spotify playlists.
- **Production Challenges:** Analyzed two massive enterprise risks (AI Hallucinations and Compute Latency) and defined the exact solutions (RAG and Hybrid ML Routing).

---

## 🚀 Getting Started

The coding sessions are provided as fully executed Jupyter Notebooks (.ipynb). You can view the embedded outputs and visualizations directly on GitHub without needing to run them!

If you wish to run the notebooks locally, ensure you have the following dependencies installed:
`ash
pip install numpy matplotlib opencv-python tensorflow
`
