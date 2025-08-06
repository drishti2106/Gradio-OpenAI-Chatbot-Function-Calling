This project demonstrates how to use OpenAI’s API with function calling features and how to build a simple chatbot interface using Gradio.
Features

OpenAI API Integration:
Seamlessly interact with OpenAI models (like GPT-3.5-turbo and GPT-4), including advanced function calling.
Function Calling Examples:
Learn how to define and call functions (e.g., getting weather, generating bash commands, and varied personality responses) via the OpenAI API.
Gradio Web Interface:
An interactive chatbot UI built with Gradio Blocks for user conversation.
Secure API Key Handling:
The OpenAI API key is read from a local key.txt file to avoid hardcoding secrets into your code.
Project Structure

function-calling.ipynb
Examples demonstrating:
Basic text completion and chat with OpenAI
Calling user-defined functions (weather info, generating commands, personality responses)
APIbasics.ipynb
Chatbot built with Gradio:
Loads an OpenAI-driven joke bot
Keeps message history
Provides a web UI for live chat
Getting Started

1. Clone the Repository


2. Set Up Your OpenAI API Key

Create a file called key.txt in the root directory.
Paste your OpenAI API key into key.txt.

Example content:
text
sk-XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX

NEVER share your key.txt or your API key.

3. Install Dependencies


4. Run the Notebooks

You can open and run:
function-calling.ipynb to explore function calling
APIbasics.ipynb (or similar) to launch the Gradio chatbot locally

5. Use the Gradio Interface

When you run the Gradio notebook, a link will appear in your terminal to open the chatbot in your browser.
Type your messages to interact with the bot!
Notes

Your API key is read from key.txt. If this file is missing or invalid, API calls will fail.
The provided notebooks are ready for experimentation; modify the function definitions or prompts for custom use cases.
For git projects, add key.txt to your .gitignore.

Keep your API key secret.
Do NOT commit key.txt to version control.
Requirements

Python 3.6+
openai
gradio
Enjoy experimenting with OpenAI’s function calling and building your own chatbots!
