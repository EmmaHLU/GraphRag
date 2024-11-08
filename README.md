# GraphRag
## A Retrieval-Augmented Generation (RAG) system was developed for a consulting firm, leveraging its blog content as the primary knowledge base.

* Neo4j serves as both the graph and vector database, managing content relationships and facilitating efficient retrieval of relevant documents.
* Norwegian-language text embeddings are created using "NbAiLab/nb-bert-base" from Hugging Face, ensuring precise, context-aware embeddings tailored to the language.
* Content retrieved from the Neo4j database is then enriched using "meta-llama/Llama-3.2-3B-Instruct", an LLM designed to generate informative, contextually relevant responses.
* LangChain orchestrates interactions between Neo4j and the language model, streamlining the query, retrieval, and generation pipeline to deliver accurate and insightful outputs.

