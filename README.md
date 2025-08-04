Poetic Text Generation with RNN
This project showcases a character-level Recurrent Neural Network (RNN) built using TensorFlow/Keras to generate poetic or creative English text. It uses a Long Short-Term Memory (LSTM) model trained on a sample corpus to generate new text one character at a time, learning the structure and rhythm of language patterns.

✨ Demo
Give the model a seed phrase, and it continues the poem-like output in a stylistic tone based on its training data.

🚀 Features
Character-level text generation using RNN with LSTM layers.

Temperature sampling for creative text diversity.

Model training, saving, and loading for reuse.

Customizable training data, epochs, and temperature values.

Fully implemented in a Jupyter Notebook.

🧠 Model Architecture
Input: Character sequences (length 100)

Embedding layer

LSTM layer

Dense layer with softmax activation (outputs probability for next character)

🗂️ Files
File	Description
Poetic_Text_Generating_with_RNN.ipynb	Main Jupyter Notebook for data preprocessing, model training, and generation
textgenerator.keras	Saved trained Keras model (if available)
generated_text.txt	(Optional) Sample output of generated text

📦 Requirements
Install dependencies with:

bash
Copy
Edit
pip install tensorflow numpy
📌 How to Run
Clone the repo:

bash
Copy
Edit
git clone https://github.com/yourusername/poetic-text-generator.git
cd poetic-text-generator
Open the notebook:

bash
Copy
Edit
jupyter notebook Poetic_Text_Generating_with_RNN.ipynb
Follow the cells to:

Preprocess text

Train the LSTM model

Generate poetic sequences using your custom seed

✍️ Sample Output
text
Copy
Edit
Seed: "The moonlight falls on"
Generated: "The moonlight falls on the golden sand, as whispers weave the stars by hand..."
⚙️ Customization
Change text_path in the notebook to use your own training corpus.

Tune temperature parameter to control creativity:

Lower → more predictable

Higher → more surprising and diverse

📚 Concepts Used
LSTM Networks

Text tokenization and sequence batching

Temperature sampling

Character-level NLP modeling

🧑‍💻 Author
Manan Sharma
LinkedIn | Portfolio (Optional)

📄 License
This project is licensed under the MIT License.

Let me know if you'd like:

a markdown copy of this file for GitHub directly,

or to auto-generate the generated_text.txt for showcasing in the repo.








You said:
 loss: 1.2537 add this also


ChatGPT said:
Here's the updated README.md with the training loss information added:

📜 Poetic Text Generation with RNN
This project showcases a character-level Recurrent Neural Network (RNN) built using TensorFlow/Keras to generate poetic or creative English text. It uses a Long Short-Term Memory (LSTM) model trained on a sample corpus to generate new text one character at a time, learning the structure and rhythm of language patterns.

✨ Demo
Give the model a seed phrase, and it continues the poem-like output in a stylistic tone based on its training data.

🧠 Model Overview
Architecture: Character-level LSTM with embedding

Training Loss: 1.2537

Input: Character sequences of fixed length (e.g., 100)

Output: Probability distribution over the next character

🚀 Features
Character-level text generation using RNN with LSTM layers

Temperature sampling for creative control

Model training, saving, and loading

Customizable training text and generation parameters

Implemented in Jupyter Notebook using Keras and TensorFlow

🗂️ Files
File	Description
Poetic_Text_Generating_with_RNN.ipynb	Main notebook for data prep, training, and generation
textgenerator.keras	Saved trained model (if available)
generated_text.txt	(Optional) Output text samples from the generator

📦 Requirements
Install dependencies:

bash
Copy
Edit
pip install tensorflow numpy
📌 How to Run
Clone this repository:

bash
Copy
Edit
git clone https://github.com/yourusername/poetic-text-generator.git
cd poetic-text-generator
Launch the notebook:

bash
Copy
Edit
jupyter notebook Poetic_Text_Generating_with_RNN.ipynb
Run through the cells to:

Load and preprocess your text

Train the model

Generate text using a seed phrase

✍️ Sample Output
text
Copy
Edit
Seed: "The stars above the sea"
Generated: "The stars above the sea sang soft in silver air, where dreams and daylight flee..."
⚙️ Customization Options
Change the training text (text_path) to your own poetry or literature

Adjust sequence_length, temperature, and number of epochs

Use model=tf.keras.models.load_model('textgenerator.keras') to reuse the trained model

📚 Concepts Used
LSTM-based sequence modeling

Character-level natural language generation

Categorical sampling with temperature

TensorFlow/Keras training and inference

🧑‍💻 Author
Manan Sharma
LinkedIn | GitHub
