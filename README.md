

## Problem Statement

This project aims to demonstrate Retrieval Augmented Generation (RAG) with a PDF document. The problem is to efficiently retrieve relevant information from a PDF and use it to answer questions.



## Steps Done

1. **Install Requirements**
2. **Select LLM Model**
3. **Instantiate Models or API**
4. **Load PDF**: Loaded the PDF document and split it into pages using PyPDFLoader.
5. **Store in Vector Space**: Stored the PDF content in a vector space using DocArrayInMemorySearch.
6. **Create Retriever**: Created a retriever to find similar vectors for context.
7. **Generate Conversation**: Used the retriever to generate context and answer questions based on the PDF content.

## Dataset

- **Source**: The dataset is a PDF document loaded using PyPDFLoader.
- **Size**: The size of the dataset depends on the length of the PDF document.
- **Features**: Key features include the text content of the PDF pages.
- **Preprocessing**: The PDF is split into pages and stored in a vector space for efficient retrieval.


