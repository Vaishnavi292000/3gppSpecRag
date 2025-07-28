# 3gppSpecRag
Power RAGers, a demo of RAG based AI, which takes sample input of 3gpp spec of few AVPs and its description. With the help of document &amp; trained model we get summary of user input.

# 🚀 3GPP Spec Retrieval-Augmented Generation (RAG) App

This is the **Demo of RAG implementation on the simple questions of 3GPP spec**.  
We built a simple chatbot using an LLM (gpt-4.1) to handle user asked questions.

This combines **document similarity search** with **LLM summarization**, letting you ask questions that get answered using your own internal documents.

🎯 **Use case:**  
1. Retrieve the most relevant content from uploaded document and trained model data
2. Summarize or directly answer your question using the retrieved context

By the end, you’ll have a powerful mini assistant that’s grounded in your own documentation, perfect for accelerating engineering discovery and troubleshooting.


# To Run
## Pre-requisites
- python3 -m pip install ipykernel -U --user --force-reinstall --break-system-packages
- python3 -m  pip install python-docx --break-system-package
- python3 -m  pip install openai --break-system-packages
- python3 -m  pip install requests --break-system-packages


## Update below Global variables in the step 2 of Jupyter Notebook

- CLIENT_ID 
- CLIENT_SECRET 
- APP_KEY
- FILE_PATH: # Update this path to your actual document
