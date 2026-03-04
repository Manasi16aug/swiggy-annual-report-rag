# Swiggy Annual Report RAG Application

This is my submission for the internship assignment: Build a RAG Application on Swiggy Annual Report.

**Objective**  
Build an AI system that answers questions **strictly based ONLY on the Swiggy Annual Report** without hallucination.

**Source Document**  
Swiggy Annual Report FY 2024-25  
Direct Link: https://www.swiggy.com/corporate/wp-content/uploads/2025/07/Swiggy-Annual-Report-FY-2024-25.pdf  
(178 pages, latest publicly available as of July 2025)

**Technologies Used**  
- PDF Loader: PyPDFLoader  
- Chunking: RecursiveCharacterTextSplitter (1000/200)  
- Embeddings: sentence-transformers/all-MiniLM-L6-v2 (local)  
- Vector Store: FAISS  
- LLM: microsoft/Phi-3-mini-4k-instruct (local, 4-bit)  
- UI: Gradio  
- Framework: LangChain

**How to Run**  
1. Open in Colab:  
   [![Open In Colab]([https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Manas16aug/swigg-annual-report-rag/blob/main/SWIGGY_RAG.ipynb](https://colab.research.google.com/drive/1vYFxNnHZAQgnF2iEheVAR5uIZr05b5QK#scrollTo=CA4yUxCdgX5e))  
  

2. Mount Drive, place PDF, run cells.

Submitted by: Manasi  Chougale
Mumbai  
March 2026
