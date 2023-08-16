# CHATBOT

## Overview
This project involves training a chatbot using a neural language model to engage in dialogues with users. The model is designed to respond appropriately based on the input it receives. The primary goal is to create a conversational AI system that can mimic human-like responses in a given context.

## Model
The chatbot model is built using a neural network architecture, specifically GPT-2 - a state-of-the-art architecture for natural language processing tasks. It leverages pre-trained word embeddings and learns to generate coherent and contextually relevant responses.

The model file is very big hence i am providing the link : https://drive.google.com/file/d/1ViU_mPnqi1SP9IUBsPouNF-soVBePxt2/view?usp=sharing

## Task
The primary task of this project is to develop a chatbot that can hold meaningful conversations with users. The chatbot's responses should be coherent, contextually accurate, and demonstrate an understanding of the conversation history. The model is trained to predict the next word in a sequence, making it capable of generating natural-sounding text.

## Dataset
The chatbot model is trained on a dataset containing dialogues between users and potential chatbot responses. The dataset is sourced from Open-source, and it's preprocessed to include contextual information and bot responses, allowing the model to learn how to generate relevant answers in different situations.

## Challenges
Throughout the development of this project, we encountered several challenges:
- **Dataset Quality**: Ensuring that the dataset contains diverse and relevant dialogues that cover a wide range of conversational scenarios.
- **Generating Coherent Responses**: Teaching the model to generate coherent responses that make sense within the context of the ongoing conversation need a large dataset and lot of computation power this model is trained on relatively small dataset, we can increase the accuracy upon feeding a large dataset.

## Usage
**Step 1: Download and Save the Model File**
1.  Download the pre-trained model checkpoint file (`model.pth`).
2.  Save the downloaded model checkpoint file to your Google Drive for easy access during setup.

**Step 2: Open and Run the Gradio Application Notebook**

4.  Open the `Gradio_application.ipynb` notebook in Google Colab.
5.  Execute each cell in the notebook sequentially to ensure all dependencies are loaded.

**Important**

6. Make sure the `model.pth` file is in the same directory as the notebook or has the correct path specified in the `model_path` variable.
7. Before running the notebook, ensure you have the required libraries (Gradio, PyTorch, etc.) installed in the Colab environment.
8. Authenticate your Google Drive in Colab to access the model file if it's saved there.


## Contact
For questions or feedback, please contact me
