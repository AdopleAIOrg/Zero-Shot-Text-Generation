# Zero-Shot-Text-Generation

A simple Streamlit app that allows users to enter a prompt and generate text based on the prompt.

# Instalation

      !pip install -r requirements.txt


# Code Explanation

app.py: This file defines the Streamlit app and user interface. It utilizes the _get_input method to collect user input for the prompt and desired text length. The generated text is displayed using the generator method (not provided in this repository).

# Features

1. Zero-Shot Text Generation: The app leverages a pre-trained language model with zero-shot capabilities to generate text without the need for a specific prompt. Instead, users can provide high-level prompts or descriptions, and the model will generate relevant text based on the context.

2. Custom Prompt Tagging: Users can input custom prompt tags or labels to guide the text generation process. These tags act as hints or constraints for the language model, ensuring the generated text aligns with the desired topics or attributes.

3. Multilingual Text Generation: The zero-shot classification approach enables multilingual text generation. Users can generate text in different languages by specifying the target language as one of the custom prompt tags. The model adapts to the specified language and generates text accordingly.

# Usage

1. Run the Streamlit app.

        !streamlit run app.py & npx localtunnel --port 8501
     
2. The app will launch in your default web browser.

3. Enter a prompt in the provided text input box.

4. Use the slider to adjust the length of the generated text.

5. Click the "Generate Text" button to generate the text based on the provided prompt and length.

# Contact

If you have any doubt about this github feel free and ask: Email : ceo@adople.com
