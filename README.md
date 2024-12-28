# Building-a-E-Commerce-GenAI-Base-Chatbot

The FAQ Chatbot for an e-commerce dataset is developed using the LangChain
framework, incorporating Chroma DB, a RAG system, and dynamic prompting. Initially,
documents are loaded into ChromaDB and converted into vector embeddings using the HuggingFaceEmbeddings function to enable efficient semantic retrieval. The querying process
is handled by a HuggingFacePipeline, utilizing the Zephyr-7b-beta model with quantization
Configuration Load Model with Less GPU memory. The system leverages ChromaDB to
retrieve the most relevant document vectors. Finally, the RAG (Retrieval-Augmented Generation) system integrates the LLM, retrieval mechanism, and prompts to ensure high-quality,
context-aware responses.

Author:-
Sonu Kumar(MT23144)
