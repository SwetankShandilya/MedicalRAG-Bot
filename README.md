# MedicalRAG-Bot

## Overview  
The **AI-Powered Health Companion** is a Retrieval-Augmented Generation (RAG)-based intelligent assistant designed to answer medical questions using information from uploaded medical PDFs. This system leverages state-of-the-art language models, embeddings, and vector databases to deliver accurate and contextually relevant answers.

---

## Features  
- **Document Loading and Processing**: Extracts data from uploaded PDFs, splits them into manageable chunks, and prepares them for querying.  
- **ChromaDB Integration**: Efficiently stores document embeddings and metadata for fast and accurate retrieval.  
- **Custom Prompting**: Uses a carefully crafted prompt template to generate precise answers while avoiding unsupported claims.  
- **Streamlit Frontend**: User-friendly interface to process PDFs, initialize the database, and interact with the assistant.  
- **LLM Integration**: Powered by the Llama-2 model via the CTransformers library, providing robust language understanding capabilities.  

---

## Technologies Used  
- **[LangChain](https://github.com/hwchase17/langchain)**: Framework for building LLM-powered applications.  
- **[HuggingFace Embeddings](https://huggingface.co/)**: Sentence embeddings for document retrieval.  
- **[ChromaDB](https://www.trychroma.com/)**: Vector store for efficient retrieval.  
- **[PyPDFLoader](https://github.com/hwchase17/langchain/tree/master/langchain/document_loaders)**: Utility for extracting content from PDF files.  
- **[CTransformers](https://github.com/marella/ctransformers)**: Lightweight LLM integration.  
- **[Streamlit](https://streamlit.io/)**: Simplified web application development framework.  

---

## Installation  

1. Clone the repository:  
   ```bash  
   git clone https://github.com/your-username/health-ai-companion.git  
   cd health-ai-companion  
