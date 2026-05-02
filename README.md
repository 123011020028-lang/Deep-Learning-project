# 🖼️ Image Captioning using CNN + LSTM

## 📌 Project Overview

This project implements an **Image Captioning System** that automatically generates textual descriptions for images using deep learning techniques.

It combines:

* **CNN (Convolutional Neural Network)** → for extracting image features
* **LSTM (Long Short-Term Memory)** → for generating captions

---

## 🚀 Features

* Automatically generates captions for input images
* Uses pre-trained **InceptionV3** model for feature extraction
* Text processing using Tokenizer
* Sequence generation using LSTM
* Works on **Flickr8k dataset**

---

## 🧠 Tech Stack

* Python
* TensorFlow / Keras
* NumPy
* Matplotlib

---

## 📂 Dataset

We used the **Flickr8k Dataset**, which contains:

* 8000 images
* 5 captions per image

---

## ⚙️ How It Works

1. **Image Feature Extraction**

   * Pre-trained CNN extracts high-level features from images

2. **Text Processing**

   * Captions are cleaned and tokenized
   * Converted into sequences

3. **Model Training**

   * Image features + text sequences are fed into LSTM
   * Model learns to predict next word

4. **Caption Generation**

   * Given an image → model generates a sentence word by word

---

## 📁 Project Structure

```
Image-Captioning/
│
├── Flicker8k_Dataset/        # Image dataset
├── Flickr8k.token.txt        # Captions file
├── notebook.ipynb            # Jupyter Notebook
├── image_caption_model.h5    # Trained model
└── README.md

This project is for academic purposes only.
