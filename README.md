![Binaryhood](Logo/BinaryhoodLogo.png)

# ChatBot

## Installation & Setup

[Install Python] https://www.dataquest.io/blog/installing-python-on-mac/

[Install pip] https://phoenixnap.com/kb/install-pip-mac

If you have Python & pip installed then check their version in the terminal or command line tools

```
python3 --version
```

```
pip --version
```

## Installing Flask

In your terminal run the requirements.txt file using this pip

```
pip install -r requirements.txt
```

## What you will create

In this tutorial, I will guide you through the process of building a chatbot that can carry out conversations with users using natural language processing.

To start, we will be using Microsoft DialoGPT, a pre-trained language model that can generate human-like responses to given prompts. We will be integrating DialoGPT with Flask, a popular Python web framework, to create a web application that can communicate with users via a chat interface.

For the frontend of our application, we will be using HTML, CSS, and JavaScript to create a visually appealing and interactive chat interface. Additionally, we will be using jQuery to handle the HTTP requests that are made to the backend server.

# ChatBot Link
The Chatbot is constructed using the Microsoft/DialoGPT-medium model.

```
https://huggingface.co/microsoft/DialoGPT-medium
```

# User-Html

```
var userHtml = '<div class="d-flex justify-content-end mb-4"><div class="msg_cotainer_send">' + user_input + '<span class="msg_time_send">'+ time + 
    '</span></div><div class="img_cont_msg"><img src="https://i.ibb.co/d5b84Xw/Untitled-design.png" class="rounded-circle user_img_msg"></div></div>';
```

# Bot-HTML

```
var botHtml = '<div class="d-flex justify-content-start mb-4"><div class="img_cont_msg"><img src="https://i.ibb.co/fSNP7Rz/icons8-chatgpt-512.png" class="rounded-circle user_img_msg"></div><div class="msg_cotainer">' + bot_response + '<span class="msg_time">' + time + '</span></div></div>';
```
