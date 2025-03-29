# DeepLearning: Comparing Diffusion, GAN, and Autoencoder

This repository explores and compares three popular deep learning models: **Diffusion Models, Generative Adversarial Networks (GANs), and Autoencoders**. The goal is to evaluate their performance in generating and reconstructing images.

## 📌 Project Overview
- **Diffusion Models**: Learn to generate high-quality images by gradually denoising a noisy input.
- **Generative Adversarial Networks (GANs)**: Use a generator-discriminator framework to produce realistic images.
- **Autoencoders**: Compress and reconstruct images, serving as a benchmark for unsupervised learning.

## 🚀 Features
✅ Train and evaluate **Diffusion, GAN, and Autoencoder** models on a dataset.  
✅ Compare **image quality**, **training stability**, and **performance metrics**.  
✅ Visualize results with **generated/reconstructed images** and **loss curves**.

## 📂 Directory Structure
```
DeepLearning/
│── data/              # Dataset (e.g., MNIST, CIFAR-10, Custom)
│── models/            # Implementations of Diffusion, GAN, and Autoencoder
│── notebooks/         # Jupyter notebooks for training and evaluation
│── results/           # Generated images and evaluation metrics
│── utils/             # Helper functions for preprocessing and visualization
│── train.py           # Main training script
│── README.md          # Project documentation
```

## 📊 Evaluation Metrics
- **FID (Fréchet Inception Distance)** for generative models
- **MSE (Mean Squared Error)** for Autoencoders
- **Visual comparisons** of outputs

## 🛠️ Installation
```bash
git clone https://github.com/yourusername/DeepLearning.git
cd DeepLearning
pip install -r requirements.txt
```

## 🔥 Usage
Train a model using:
```bash
python train.py --model diffusion  # Options: diffusion, gan, autoencoder
```

## 📌 Results
Check the `results/` folder for generated images and model performance.

## 🤝 Contributing
Feel free to open issues and pull requests to improve the project!

## 📜 License
MIT License

---

### 🚀 Developed by:  
- [Ali Tavakoli](https://github.com/AliTavakoli2001)  
- [Amir Hossein Majidi](https://github.com/Amirmj)

