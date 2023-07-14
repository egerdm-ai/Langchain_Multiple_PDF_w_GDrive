Langchain Chatbot with Multiple Documents

This repository contains code for creating a chatbot using the Langchain library. Langchain is a Python library that simplifies the process of building applications with language models. It provides a set of components that can be combined in various ways to perform different tasks.

Project Description:

This project uses Langchain to create a chatbot that can answer questions based on the content of PDF, TXT, and DOCX files. The chatbot uses the GPT-3.5-turbo model from OpenAI to generate responses.

How It Works:

The code loads documents from a specified directory, splits the documents into smaller chunks, and converts these chunks into embeddings. These embeddings are then stored in a vector database. A ConversationalRetrievalChain is created from the language model and the vector database. This chain is used to generate responses to user queries based on the content of the loaded documents.

Usage:

To use this code, you need to have Python installed on your machine. You also need to install the required libraries by running the following command:
pip install langchain openai chromadb tiktoken

You also need to set your OpenAI API key as an environment variable:
export OPENAI_API_KEY='your-api-key'

Then, you can run the code with the following command:
python main.py

Demo:

You can try a live demo of this project on Google Colab: 
Langchain Chatbot Demo

Link: https://colab.research.google.com/drive/1Jt1lfcQ40y_uat2L-gBYfUUCis0pnz7J#scrollTo=61qHTc4KfLM5

Further Reading:

For a more detailed explanation of this project and the concepts behind it, check out this Medium article: 
Building a Chatbot with Langchain

Link: https://medium.com/@eredem96/deep-dive-into-building-conversational-agents-with-langchain-d73befdcac2f
