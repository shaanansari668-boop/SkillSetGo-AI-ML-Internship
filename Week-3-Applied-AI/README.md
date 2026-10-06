# Week 3: Applied AI

Skill Set Go EduTech | AI/ML Internship

## Objective
Build practical skills in TensorFlow/Keras, computer vision, prompt engineering, and AI-assisted application development.

## Datasets
MNIST (3.1) and CIFAR-10 (3.2).

## Tasks Completed
- 3.1 TensorFlow/Keras dense network on MNIST, compared against the Week 2 PyTorch CNN
- 3.2 CNN image classification on CIFAR-10
- 3.3 Prompt engineering portfolio across reasoning, extraction, summarization, and coding tasks
- 3.4 AI-assisted coding task: a Gradio image classification app, with a short code audit

## Tools
Python, TensorFlow, Keras, NumPy, Pandas, Matplotlib, Scikit-learn, Gradio, Google Colab

## Results
- TensorFlow/Keras (MNIST) test accuracy: 97.30%
- PyTorch CNN (Week 2, MNIST) test accuracy: 98.78%, for comparison
- CIFAR-10 CNN test accuracy: 69.28% (precision/recall ranged from 0.46 on cats to 0.85 on frogs)
- Prompt engineering: identified one best practice per task type, e.g. defining exact fields and output format for extraction, specifying audience and length for summarization
- Gradio app: takes an uploaded image, resizes and normalizes it to 32x32, and returns predicted CIFAR-10 class probabilities

## Files
- AbdUrRahman_Week3_TensorFlow_Prompt_Engineering.ipynb (notebook with outputs)
- week3_tensorflow_mnist_model.keras
- week3_cifar10_cnn.keras
- week3_model_results.csv
- prompt_engineering_portfolio (prompt rows and best-practice summary, in the notebook)
- Gradio app code and code audit notes (in the notebook)

## How to Run
Open the notebook in Google Colab (T4 GPU recommended) and run all cells from top to bottom. MNIST and CIFAR-10 download automatically. The Gradio cell launches a shareable demo link when run in Colab.
