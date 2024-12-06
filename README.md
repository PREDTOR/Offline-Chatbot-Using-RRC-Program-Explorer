# Offline-Chatbot-Using-RRC-Program-Explorer
In this project We worked in a team of 3 under the guidance of our instructor Baha Rababah. This is a offline chatbot that uses PDFs that is fed to the model, using these PDFs it generated responses according to user query with an interactive loop to interact with the this model by user.

README
Offline Chatbot for PDF Processing

Final Project - Large Language Model Chatbot
Contributors - Cassandra Phung, Kumar Kartikeyn Arora, Husandeep Kaur
Course - COMP-3704 (254805) Neural Networks and Deep Learning
Term – Fall 2024
Institution - Red River College Polytechnic
Date - December 5, 2024

Introduction

Objective
This chatbot was developed to operate entirely locally and offline, ensuring user privacy and data security. It enables users to load PDF files as input and interact with a language model (LLM) directly within this Jupyter Notebook.

Key Features
•	Processes and interacts with PDF files using a language model (LLM) within a Jupyter Notebook.
•	By operating offline, the chatbot avoids relying on online platforms where user-uploaded data could be utilized for training generative AI models.
•	Due to this being a local system, it is suitable for handling sensitive files such as financial, medical or general personal information.

Use Case
For this demonstration, the chatbot processes information from three of Red River College's Information Technology Programs. The data has been sourced directly from the official RRC website.

Other Potential Applications
This chatbot is particularly useful for scenarios involving sensitive data that users prefer not to upload to online platforms, as many companies use user-uploaded data to improve their generative AI.

Examples of sensitive files include:
- Patient Information: Medical records or other health-related documents.
- Financial Information: Banking or investment details.
- Personal Information: Documents users wish to keep private.
- By keeping the process offline, this tool provides a secure alternative for handling confidential files.

How to run the code

Instructions
•	See attached requirements.txt to setup your chatbot virtual environment
•	This can be done in Anaconda Navigator
•	Once you’ve set up your virtual environment, download the latest version of Ollama where you will be pulling the embedding model and LLM needed for this chatbot
•	Once you have Ollama installed, open command prompt and pull the following models:
•	llama2:7b and nomic-embed-text

Ollama Instructions
Ensure ollama is running, as models need to communicate with the server
•	Open command prompt
•	Check if ollama is running: ollama --version
•	If it cannot connect to a running Ollama instance: ollama start
•	Open new command prompt
•	ollama list
•	Ensure you have both models: llama2:7b and nomic-embed-text
