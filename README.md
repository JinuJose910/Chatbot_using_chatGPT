# Chatbot_using_chatGPT
This repository contains code that demonstrates how to build a chatbot using OpenAI's GPT (Generative Pretrained Transformer) model and Gradio, a Python library for creating UI components. The chatbot interacts with users in a conversational manner, generating responses based on the input provided.

## Setup

To run the code in this repository, please follow these steps:

1. Clone the repository to your local machine.
2. Install the required dependencies by running the following command:

```
pip install -r requirements.txt
```

3. Set up OpenAI API access by obtaining an API key. You can sign up for an API key at the OpenAI website (https://openai.com/).
4. Replace the placeholder API key in the code with your actual OpenAI API key. Find the following line in the code and update it:

```python
openai.api_key = "YOUR_API_KEY"
```

5. Run the code using the following command:

```
python chatbot.py
```

## Usage

Once the code is running, you can interact with the chatbot using a web interface. Open your web browser and navigate to the provided URL (e.g., http://localhost:7860). You will see a text box where you can enter your messages.

- Enter a message in the text box and click "SEND" to send the message to the chatbot.
- The chatbot will generate a response based on the input provided and display it in the UI.
- You can continue the conversation by entering more messages and clicking "SEND" after each message.

## Customization

If you want to modify the behavior or appearance of the chatbot, you can make changes to the code. For example, you can adjust the model settings, modify the conversation prompt, or customize the UI components using Gradio's documentation (https://gradio.app/docs/).

## Acknowledgments

This code is adapted from the examples provided by OpenAI (https://openai.com/) and Gradio (https://gradio.app/). We would like to acknowledge their contributions to the development of this project. This is a project guided by Pooja Madam from OpenWeaver as a part of virtual Internship.



