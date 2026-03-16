# Next Word Prediction using LSTM

## Project Overview

This project builds a **Next Word Prediction Model** using Deep Learning and Natural Language Processing (NLP).
The model predicts the most probable next word based on the input sequence of words.

This type of model is commonly used in:

* Search engines
* Chatbots
* Text autocomplete
* Smart keyboards

---

## Technologies Used

* Python
* TensorFlow / Keras
* Natural Language Processing (NLP)
* LSTM (Long Short-Term Memory)

---

## Project Workflow

1. **Text Preprocessing**

   * Cleaning the text
   * Removing punctuation
   * Converting text to lowercase

2. **Tokenization**

   * Converting words into tokens using a tokenizer.

3. **Sequence Generation**

   * Creating input sequences for training.

4. **Padding**

   * Making all sequences the same length.

5. **Model Building**

   * Embedding Layer
   * LSTM Layer
   * Dense Output Layer

6. **Model Training**

   * The model learns patterns from the dataset.

7. **Prediction**

   * The trained model predicts the next word for a given sentence.

---

## Model Files

| File            | Description                                     |
| --------------- | ----------------------------------------------- |
| `word_pred.h5`  | Trained deep learning model                     |
| `tokenizer.pkl` | Tokenizer used to convert words into numbers    |
| `max_len.pkl`   | Maximum sequence length used during training    |
| `.ipynb`        | Jupyter notebook containing full implementation |

---

## Example

Input:
I love deep learning

Prediction:
I love deep learning **models**

---

## How to Run the Project

1. Clone the repository

```
git clone https://github.com/yourusername/next-word-prediction.git
```

2. Install dependencies

```
pip install -r requirements.txt
```

3. Run the notebook or prediction script.

---

## Applications

* Text Autocomplete
* Chatbots
* Search Query Suggestions
* Smart Writing Assistants

---

## Author

Harsh Kumar

---

## GitHub Repository

Add your repository link here after uploading the project.




## Model File

The trained model file `word_pred.h5` is not included in this repository because it exceeds GitHub's file size limit.

You can train the model yourself using the provided Jupyter Notebook.

Steps:

1. Open the notebook `next_word_prediction.ipynb`
2. Run all cells to preprocess the data and train the model
3. The model will be saved as `word_pred.h5` after training


---

⭐ If you found this project useful, feel free to star the repository.
