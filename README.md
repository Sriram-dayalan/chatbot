# chatbot
A voice chatbot built with Meta Llama 3 and Ollama Python Library  This repository includes a Python program that calls the Meta Llama 3 model via the Ollama Python Library to obtain a response for questions from a user. Then, it will convert the text response to an audio response. This version has been tested on Windows 11.

At first, you will need to download and install Ollama from the official website at https://ollama.com. Then, download the Meta Llama 3 model with this command,

ollama pull llama3
It will take some time to finish downloading depending on your network speed. Once that is done, we can start Ollama with the following command and use the Llamma 3 model in Python code,

ollama serve
If you would like to use another large language model such as Llama 2, you can pull it in the same way and change the code accordingly.

Before you can run this code on your computer, you will need to install the following Python packages:

pip install ollama
pip install speechrecognition gtts pyaudio pygame
If you have Python 3.12 or newer, also install the "setuptools" package,

pip install setuptools   
You may need to create a Python virtual environment first.

