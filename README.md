Neural Assistant for Mnemonics
This project implements a neural assistant that provides advice on mnemonics. The assistant can answer any questions related to mnemonics and offer tips on how to remember specific information. The core functionalities are powered by various libraries and models, including Hugging Face's Transformers, Langchain, and Cohere.

Functionality:
1. Question Answering: The assistant can answer questions based on provided documents.
2. Spell Correction: Input queries are checked for spelling errors and corrected using a T5 model.
3. Safety Check: User input is moderated to ensure safety before processing.
4. Graph Visualization: The assistant can create a knowledge graph from the provided documents for better understanding.
5. Embedding and Reranking: The assistant utilizes embeddings for improved query understanding and utilizes reranking to provide better answers.
