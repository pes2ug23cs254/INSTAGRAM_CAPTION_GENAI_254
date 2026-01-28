# AI-Based Instagram Caption Generator using Hugging Face

This project is an AI-powered Instagram Caption Generator that creates aesthetic, mood-based captions from a simple photo description. It uses Natural Language Processing (NLP) techniques and pre-trained transformer models from Hugging Face.

---

## Project Overview

Writing engaging captions for social media posts can be difficult. This project provides an AI solution that generates creative Instagram-style captions based on the mood and vibe of a given photo description.

The system analyzes the emotional tone of the scene and then generates captions that match that mood. This shows how transformer-based NLP models can be applied to real-world creative tasks.

---

## Models Used

The project uses two Hugging Face models:

* **Sentiment Analysis Model**
  Used to detect whether the scene description has a positive or negative emotional tone.

* **Text Generation Model (DistilGPT-2)**
  Used to generate keywords related to the mood and aesthetic of the scene.

These models are accessed using the Hugging Face `pipeline` API.

---

## Technologies Used

* Python
* Hugging Face Transformers
* Jupyter Notebook
* Natural Language Processing (NLP)

---

## How the System Works

1. **Mood Detection**
   The input description is first analyzed using a sentiment analysis model to determine if the scene feels happy or moody.

2. **Keyword Extraction**
   A text generation model is prompted to produce aesthetic or vibe-related keywords based on the description.

3. **Caption Creation**
   The system combines the detected mood and generated keywords to create stylish Instagram captions using predefined templates and emojis.

---

## Example Outputs

**Input:**
`girl laughing with friends at a beach sunset`

**Output:**

* Caught in a golden kind of moment ✨
* Smiling through these warm little things 🌸
* Just me, some sunset vibes, and good energy 💫

---

**Input:**
`girl standing alone at night in fog on an empty road`

**Output:**

* Lost in silent thoughts under quiet skies 🌙
* Some nights just feel mysterious and still 🖤
* Wrapped in shadows, silence, and calm moments 🌫️

---

## How to Run the Project

1. Install the required libraries:

   ```
   pip install transformers torch
   ```

2. Open the Jupyter Notebook.

3. Run the cells in order to:

   * Load the models
   * Define the functions
   * Enter your own photo description

4. The system will display three AI-generated Instagram captions.

---

## Key Features

* Mood-aware caption generation
* Uses multiple Hugging Face NLP models
* Generates aesthetic, Instagram-style captions
* Supports custom user input
* Clean and safe outputs for demonstration

---

## Academic Purpose

This project was developed as part of a GenAI  coursework assignment. It demonstrates the use of pre-trained transformer models for text generation and sentiment analysis in a practical and creative application.

---

## Author

Name: PADMAA.K.B
Course: GenAI 
Institution: PES UNIVERSITY


