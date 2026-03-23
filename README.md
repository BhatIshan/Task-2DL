 Deep Learning Models: CNN, RNN, and GAN

 Project Overview
This project focuses on implementing and evaluating multiple deep learning models for different types of tasks, including image classification, sentiment analysis, and image generation. The goal is to understand how different neural network architectures perform across various domains.

The project is divided into three main parts:
- Image Classification using CNN and Transfer Learning  
- Sentiment Analysis using RNN-based models  
- Image Generation using GAN  



 Models Implemented

 1. Convolutional Neural Network (CNN)
- Dataset: CIFAR-10  
- Custom CNN architecture  
- Transfer Learning using ResNet18  
- Task: Image Classification  

2. RNN-based Models (RNN, LSTM, GRU)
- Dataset: IMDB Movie Reviews  
- Task: Sentiment Analysis (Positive / Negative)  
- Comparison between RNN, LSTM, and GRU  

 3. Generative Adversarial Network (GAN)
- Dataset: Fashion-MNIST  
- Task: Generate synthetic clothing images  
- Components:
  - Generator  
  - Discriminator  



 Datasets Used
- CIFAR-10 → Image classification (10 classes)  
- IMDB Dataset → Text sentiment classification  
- Fashion-MNIST → Image generation  



Technologies Used
- Python  
- PyTorch  
- Torchvision  
- Torchtext  
- NumPy  
- Matplotlib / Seaborn  
- Google Colab (GPU support)  

 Training Strategy

| Model | Batch Size | Epochs | Learning Rate |
|------|------------|--------|--------------|
| CNN | 128 | 10–20 | 0.001 |
| ResNet18 | 64 | 10 | 0.0005 |
| RNN/LSTM/GRU | 32 | 5–10 | 0.001 |
| GAN | 128 | 50 | 0.0002 |



 Results

 Image Classification
- Custom CNN Accuracy: 81.2%  
- ResNet18 Accuracy: 86.18%  

 Sentiment Analysis
- RNN Loss: ~0.52  
- LSTM Loss: ~0.18  
- GRU Loss: ~0.13 (Best Performance)  

 GAN
- Generated images improve over epochs  
- Moderate realism achieved  
- Training shows expected instability  



 Key Observations
- Transfer learning improves classification accuracy  
- LSTM and GRU outperform basic RNN  
- GAN successfully generates images but requires stable training  


 Challenges Faced
- GAN training instability  
- Hyperparameter tuning  
- Limited computational resources  



 Future Improvements
- Use advanced architectures (DCGAN, Attention models)  
- Apply hyperparameter optimization  
- Train on larger datasets  



Author
Ishan  
Information Science and Engineering  
NMAM Institute of Technology  

---

 References
- Deep Learning – Ian Goodfellow  
- PyTorch Documentation  
- CIFAR-10, IMDB, Fashion-MNIST datasets  

---

 Acknowledgement
This project was developed as part of the Deep Learning course to gain practical experience with modern neural network architectures.
