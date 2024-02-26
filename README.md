# Generative AI: Retrieval Augmented Generation (RAG)
Guest lecture on Retrieval-Augmented Generation (RAG) for DS 3891 Generative AI 

## Intro

RAG was first introduced in Meta's 2020 paper titled ["Retrieval Augmented Generation for Knowledge-Intensive Tasks"](https://arxiv.org/abs/2005.11401) Since then, it has become a widely popular method to enhance generative AI reponses. This method relies on giving a corpus of information to a large language model (LLM), which then uses that information to generate its response.
RAG is best for situations in which LLM users want fact-based answers or answers with sources from a specific collection.

## Using this Repo

Use this repo to access a tutorial notebook on implementing RAG using the Python library Langchain. 

# Langchain Documentation

You can find the Langchain documentation used to create this tutorial below. The suggested order for the documentation is as follows:

1. [Document Loading](https://python.langchain.com/docs/modules/data_connection/document_loaders/)
2. [Text Splitters](https://python.langchain.com/docs/modules/data_connection/document_transformers/)
3. [Vector Stores](https://python.langchain.com/docs/modules/data_connection/vectorstores/)
4. [Retrievers](https://python.langchain.com/docs/modules/data_connection/retrievers/vectorstore)


## Resources

- [Langchain cookbook on RAG](https://python.langchain.com/docs/expression_language/cookbook/retrieval)
- [Langchain RAG Quickstart](https://python.langchain.com/docs/use_cases/question_answering/quickstart)
- [RAG Guide from DataStax](https://www.datastax.com/guides/what-is-retrieval-augmented-generation)
- [Semantic Text Splitting](https://github.com/FullStackRetrieval-com/RetrievalTutorials/blob/main/5_Levels_Of_Text_Splitting.ipynb)
- [Adding Citations](https://python.langchain.com/docs/use_cases/question_answering/citations)
  
