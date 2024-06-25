# Streamlit_apps

This repository contains three Streamlit applications for different tasks: ChatBot, Object Detection, and Word Correction. Each application is located in its respective folder.

## Folder Structure

- `chatbot`: A simple chatbot application using Streamlit and HugChat.
- `object_detection`: An object detection application for images using Streamlit, OpenCV, and MobileNetSSD.
- `word_correction`: A word correction application using Levenshtein distance.

---
## Cloning the Repository

First, clone the repository:

```bash
https://github.com/PUVHAM/Streamlit_apps.git
cd Streamlit_apps
```

---

## ChatBot

A simple chatbot application that uses HugChat for generating responses based on user input.

### Files

- `requirements.txt`: Contains the required libraries.
- `app.py`: Main application file.
- `response.py`: Contains the function to generate responses using HugChat.

### Requirements

- streamlit
- hugchat

### Usage

1. Navigate to the `chatbot` directory:
  ```bash
   cd chatbot
  ``` 
2. Install the requirements:
  ```bash
   pip install -r requirements.txt
  ``` 
3. Run the application:
  ```bash
  streamlit run app.py
  ```

### Note
If the chatbot does not respond within a reasonable time or encounters an error, please enter a new message to retry generating a response :)).

---

## Object Detection

An object detection application for images using Streamlit, OpenCV, and MobileNetSSD.

### Files

- `requirements.txt:` Contains the required libraries.
- `app.py:` Main application file.
- `detection.py:` Contains the functions for processing and annotating images.
- `model:` Contains the MobileNetSSD model files.

### Requirements

streamlit
pillow
numpy
opencv-python-headless

### Usage

1. Navigate to the `object_detection` directory:
  ```bash
   cd object_detection
  ``` 
2. Install the requirements:
  ```bash
   pip install -r requirements.txt
  ``` 
3. Ensure the MobileNetSSD model files are in the `model` directory.
4. Run the application:
  ```bash
  streamlit run app.py
  ```

---

## Word Correction

A word correction application using Levenshtein distance to find the correct word from a given vocabulary.

### Files

- `requirements.txt:` Contains the required libraries.
- `app.py:` Main application file.
- `levenshtein_distance.py:` Contains the function for calculating Levenshtein distance.
- `load_file.py:` Contains the function to load vocabulary from a file.
- `Data:` Contains the vocab.txt file with a list of vocabulary words.

### Requirements
streamlit

### Usage

1. Navigate to the `word_correction` directory:
  ```bash
   cd word_correction
  ``` 
2. Install the requirements:
  ```bash
   pip install -r requirements.txt
  ``` 
3. Run the application:
  ```bash
  streamlit run app.py
  ```

---

By following the instructions provided for each application, you should be able to run all the Streamlit apps successfully. If you encounter any issues, please refer to the code snippets and ensure all dependencies are installed correctly.
