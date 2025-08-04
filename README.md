# 📜 Poetic Text Generation with RNN

This project showcases a character-level Recurrent Neural Network (RNN) built using TensorFlow/Keras to generate poetic or creative English text. It uses a Long Short-Term Memory (LSTM) model trained on a sample corpus to generate new text one character at a time, learning the structure and rhythm of language patterns.

## ✨ Demo

> Give the model a seed phrase, and it continues the poem-like output in a stylistic tone based on its training data.

---

## 🧠 Model Overview

- **Architecture**: Character-level LSTM with embedding
- **Training Loss**: **`1.2537`**
- **Input**: Character sequences of fixed length (e.g., 100)
- **Output**: Probability distribution over the next character

---

## 🚀 Features

- Character-level text generation using RNN with LSTM layers
- Temperature sampling for creative control
- Model training, saving, and loading
- Customizable training text and generation parameters
- Implemented in Jupyter Notebook using Keras and TensorFlow

---

## 🗂️ Files

| File                                  | Description                                        |
|---------------------------------------|----------------------------------------------------|
| `Poetic_Text_Generating_with_RNN.ipynb` | Main notebook for data prep, training, and generation |
| `textgenerator.keras`                | Saved trained model                                 |

---

## 📦 Requirements

Install dependencies:

```bash
pip install tensorflow numpy
```

## How to Run
Clone this repository:

```bash```
Copy
Edit
git clone https://github.com/yourusername/poetic-text-generator.git
cd poetic-text-generator
Launch the notebook:


## ✍️ Sample Output

Seed: "The stars above the sea"
Generated: "The stars above the sea sang soft in silver air, where dreams and daylight flee..."

## ⚙️ Customization Options
Change the training text (text_path) to your own poetry or literature

Adjust sequence_length, temperature, and number of epochs

Use model = tf.keras.models.load_model('textgenerator.keras') to reuse the trained model

## 📚 Concepts Used
LSTM-based sequence modeling

Character-level natural language generation

Categorical sampling with temperature

TensorFlow/Keras training and inference

## 🧑‍💻 Author
Manan Sharma
LinkedIn
GitHub

