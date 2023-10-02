# QA-Bot-LangChain

### Overview
This repository contains a simple yet powerful chatbot developed for Hushh.ai interview task using LangChain, OpenAI, and other libraries. The chatbot is designed to answer user queries, provide insights from an embedded knowledge base, and engage in conversational interactions.

### Features
1. Document Processing: Utilizes LangChain to process PDF documents, extracting relevant information for analysis.
2. Token-based Chunking: Implements advanced text chunking techniques to enhance context retention during document processing.
3. Question Answering (QA): Employs OpenAI GPT-2 models for QA tasks, enabling the chatbot to answer user questions based on the knowledge base.
4. Conversational Retrieval: Implements a conversational retrieval chain for a dynamic and interactive chat experience.
   
### Getting Started
To run the chatbot locally:

1. Install required dependencies using !pip install -q langchain==0.0.150 pypdf pandas matplotlib tiktoken textract transformers openai faiss-cpu.
2. Set up your OpenAI API key by updating the os.environ["OPENAI_API_KEY"] line with your key.
3. Add the PDF document to the local files in the notebook.
4. Follow the provided Jupyter Notebook for step-by-step instructions on document processing and chatbot usage.
   
### Usage
1. Load your PDF document, either by simple page splitting or advanced chunking methods.
2. Create a knowledge base using LangChain and OpenAI embeddings.
3. Interact with the chatbot using user queries, benefiting from both QA and conversational retrieval capabilities.

### Acknowledgments
This project leverages the capabilities of LangChain, OpenAI, and other open-source libraries. Special thanks to the developers of these tools for their contributions.

