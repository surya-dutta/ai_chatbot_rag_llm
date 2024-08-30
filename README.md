# Streamlit + Langchain + LLama.cpp w/ Mistral: Retrieval Augmented Generation

Scrape a website for web content and build a conversational AI chatbot from that knowledge base.

This chatbot has conversational memory and can hold follow-up conversations within the same session.

This code was tested on a WordPress Blog and has some logic that will not directly work on other websites. Also, while this code can technically run on a computer without a GPU, running it on a GPU is recommended since the RAG process can be very slow otherwise. You will also need to change how you install the `llama-cpp-python` package depending on your OS and whether you are planning on using a GPU or not.

# TL;DR instructions

1. Install llama-cpp-python
2. Install langchain
3. Install streamlit
4. Install beautifulsoup
5. Install PyMuPDF
6. Install sentence-transformers
7. Install docarray
8. Install pydantic 1.10.8
9. Download Mistral from HuggingFace from TheBloke's repo: mistral-7b-instruct-v0.1.Q5_0.gguf
10. Place model file in the `models` subfolder
11. Run streamlit

