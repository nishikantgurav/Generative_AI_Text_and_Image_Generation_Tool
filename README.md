# Generative_AI_Text_and_Image_Generation_Tool
This repository contains the code for a generative AI-powered web application that provides two forms for users to interact with: 
-  Text to Text: Generate text in response to a given input text using OpenAI's GPT-3.
-  Text to Images: Generate images in response to a given input text using OpenAI's DALL-E.
# Dependencies
This project relies on the following libraries:
- gradio
- requests
- openai
You can install these dependencies using pip:
pip install gradio requests openai

# How it works
This tool uses the Gradio library to create a web interface with two forms:

- Text to Text: When a user enters text into this form and submits it, the input text is sent to OpenAI's GPT-3, which generates a textual response. The generated text is then displayed on the page.

- Text to Images: When a user enters text into this form and submits it, the input text is sent to OpenAI's DALL-E, which generates an image. The generated image is then displayed on the page.
# Usage
To run the tool, execute the python script:
python generative_ai_tool.py

This will launch the Gradio interfaces, and a link to the web application will be printed in your console. Click on this link to open the web application in your browser.
# Security
This code uses an OpenAI API key which is hardcoded in the script. Please replace it with your own API key. Never share your API key publicly.



