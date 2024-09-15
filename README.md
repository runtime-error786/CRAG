## Overview



This repository provides a framework for building a custom question-answering agent using Large Language Models (LLMs) and document retrieval techniques. The workflow is designed to retrieve documents from both local embeddings and web searches, grade them for relevance, and generate concise answers based on the filtered documents. The system is built using LangChain, Chroma, HuggingFace, and a custom state-based workflow.

## The agent can handle:

- Local document retrieval from pre-indexed sources using embeddings.


-Web search integration if the retrieved documents are insufficient.




-Grading and filtering of documents based on their relevance to the user's query.



-Generation of short, concise answers based on the most relevant documents.
