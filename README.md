# Generative AI Use Cases Repository

## Introduction
Generative AI Use Cases Repository
Welcome to the Generative AI Use Cases Repository! This comprehensive resource showcases cutting-edge applications in generative AI, including Retrieval-Augmented Generation (RAG), AI Agents, and industry-specific use cases. Discover how MongoDB integrates with RAG pipelines and AI Agents, serving as a vector database, operational database, and memory provider.

**Key Features:**

- RAG pipelines and applications leveraging MongoDB for efficient data retrieval and management
- AI Agents utilizing MongoDB as a scalable memory provider
- Practical notebooks and guidance on frameworks like LlamaIndex, Haystack and LangChain
- Integration with state-of-the-art models from Anthropic and OpenAI
- Industry-specific use cases across healthcare, finance, e-commerce, and more

## Table of Contents
- [Introduction](#introduction)
- [Use Cases](#use-cases)
- [Notebooks](#notebooks)
  - [Evaluations](#evaluations)
  - [RAG](#rag)
  - [Agents](#agents)
  - [Workshops](#workshops)
- [Tools](#tools)
- [Datasets](#datasets)
- [General Knowledge](#general-knowledge)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Use Cases

This section contains examples of use cases that are commonly seen in industry-focused scenarios and generic applications. Each entry in the table includes a description and links to production-level examples and relevant code.

| Use Case                       | Stack                  | Link                                              | Description |
|--------------------------------|------------------------|---------------------------------------------------|-------------|
| **Customer Support Chatbot**   | JavaScript, OpenAI, MongoDB | [View Repository](https://github.com/mongodb/chatbot) | The MongoDB Chatbot Framework provides libraries that enable the creation of sophisticated chatbot |

## Evaluations
- [Evaluating your LLM applications](https://github.com/mongodb-developer/GenAI-Showcase/blob/main/notebooks/evals/ragas-evaluation.ipynb)
- [Angle Embeddings Evaluation](/notebooks/evals/angle-embeddings-eval.ipynb)
- [OpenAI Embeddings Evaluation](/notebooks/evals/openai-embeddings-eval.ipynb)
- [VoyageAI Embeddings Evaluation](/notebooks/evals/voyageai-embeddings-eval.ipynb)


## RAG
| Title                                             | Stack            | Colab                                                                                                                                                                                            | Article |
|---------------------------------------------------|------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|---------|
| RAG with Llama3, Hugging Face and MongoDB         | Hugging Face, Llama3, MongoDB              | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/mongodb-developer/GenAI-Showcase/blob/main/notebooks/rag/rag_mongodb_llama3_huggingface_open_source.ipynb) |  |
| How to Build a RAG System Using Claude 3 Opus and MongoDB                       | MongoDB, Anthropic, Python              | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/mongodb-developer/GenAI-Showcase/blob/main/notebooks/rag/anthropic_mongodb_pam_ai_stack.ipynb)       |   [![View Article](https://img.shields.io/badge/View%20Article-blue)](https://www.mongodb.com/developer/products/atlas/rag_with_claude_opus_mongodb/)      |
| How to Build a RAG System with the POLM AI Stack                                    | POLM (Python, OpenAI, LlamaIndex, MongoDB)              | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/mongodb-developer/GenAI-Showcase/blob/main/notebooks/rag/building_RAG_with_LlamaIndex_and_MongoDB_Vector_Database.ipynb) | [![View Article](https://img.shields.io/badge/View%20Article-blue)](#) |
| MongoDB LangChain Cache Memory Python Example     | POLM (Python, OpenAI, LangChain, MongoDB)              | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/mongodb-developer/GenAI-Showcase/blob/main/notebooks/rag/mongodb-langchain-cache-memory.ipynb)      | [![View Article](https://img.shields.io/badge/View%20Article-blue)](https://www.mongodb.com/developer/products/atlas/advanced-rag-langchain-mongodb/) |
| MongoDB LangChain Cache Memory JavaScript Example | JavaScript, OpenAI, LangChain, MongoDB              | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/mongodb-developer/GenAI-Showcase/blob/main/notebooks/rag/mongodb-langchain-js-memory.ipynb) | [![View Article](https://img.shields.io/badge/View%20Article-blue)](https://www.mongodb.com/developer/products/atlas/add-memory-to-javascript-rag-application-mongodb-langchain/) |
| Naive RAG Implementation Example                  | POLM (Python, OpenAI, LlamaIndex, MongoDB)                | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](  https://colab.research.google.com/github/mongodb-developer/GenAI-Showcase/blob/main/notebooks/rag/naive_rag_implemenation_llamaindex.ipynb) | [![View Article](https://img.shields.io/badge/View%20Article-blue)](https://www.mongodb.com/developer/products/atlas/rag-with-polm-stack-llamaindex-openai-mongodb/) |
| OpenAI Text Embedding Example                     | Python, MongoDB, OpenAI              | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://github.com/mongodb-developer/GenAI-Showcase/blob/main/notebooks/rag/openai_text_3_emebdding.ipynb)             | [![View Article](https://img.shields.io/badge/View%20Article-blue)](https://www.mongodb.com/developer/products/atlas/using-openai-latest-embeddings-rag-system-mongodb/) |
| RAG with Hugging Face and MongoDB Example         | Hugging Face, Gemma, MongoDB              | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/mongodb-developer/GenAI-Showcase/blob/main/notebooks/rag/rag_with_hugging_face_gemma_mongodb.ipynb) | [![View Article](https://img.shields.io/badge/View%20Article-blue)](https://www.mongodb.com/developer/products/atlas/gemma-mongodb-huggingface-rag) |
| Chat With PDF Example | Python, MongoDB, OpenAI, LangChain | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/mongodb-developer/GenAI-Showcase/blob/main/notebooks/rag/chat_with_pdf_mongodb_openai_langchain_POLM_AI_Stack.ipynb) |
| RAG Pipeline | Python, MongoDB, Gemma2, KeraNLP | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/mongodb-developer/GenAI-Showcase/blob/main/notebooks/rag/rag_pipeline_kerasnlp_mongodb_gemma2.ipynb) |
| RAG Pipeline with Open Models| Python, MongoDB, Gemma2, Hugging Face | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/mongodb-developer/GenAI-Showcase/blob/main/notebooks/rag/rag_with_gemma2_mongodb_open_models.ipynb) |
| MongoDB and Haystack cooking advisor| Python, Haystack , OpenAI | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/mongodb-developer/GenAI-Showcase/blob/main/notebooks/rag/haystack_mongodb_cooking_advisor_pipeline.ipynb)| [![View Article](https://img.shields.io/badge/View%20Article-blue)](https://www.mongodb.com/developer/products/atlas/haystack-ai-mongodb-atlas-vector-demo)|
| MongoDB and Semantic Kernel Movie Recommendation Bot - Console App | C#, MongoDB, Semantic Kernel, Azure OpenAI or OpenAI | [GitHub Repo](https://github.com/mongodb-developer/SemanticKernel_With_CSharp_And_Atlas) | Coming soon |



## Agents
An agent is an artificial computational entity with an awareness of its environment. It is equipped with faculties that enable perception through input, action through tool use, and cognitive abilities through foundation models backed by long-term and short-term memory. Within AI, agents are artificial entities that can make intelligent decisions followed by actions based on environmental perception, enabled by large language models.

| Title                          | Stack                | Colab Link                                     | Article Link                                     |
|--------------------------------|----------------------|------------------------------------------------|--------------------------------------------------|
| AI Research Assistant   | FireWorks AI, MongoDB, LangChain      |[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/mongodb-developer/GenAI-Showcase/blob/main/notebooks/agents/agent_fireworks_ai_langchain_mongodb.ipynb) |  [![View Article](https://img.shields.io/badge/View%20Article-blue)](https://www.mongodb.com/developer/products/atlas/agent-fireworksai-mongodb-langchain/)    | 
AI Investment Researcher | MongoDB, CrewAI and LangChain | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/mongodb-developer/GenAI-Showcase/blob/main/notebooks/agents/crewai-mdb-agg.ipynb) | [![View Article](https://img.shields.io/badge/View%20Article-blue)](https://www.mongodb.com/developer/products/mongodb/augment-llm-capabilities-with-mdb-aggregation/)
| Agentic RAG: Recommmendation System | Claude 3.5, LlamaIndex, MongoDB | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/mongodb-developer/GenAI-Showcase/blob/main/notebooks/agents/how_to_build_ai_agent_claude_3_5_sonnet_llamaindex_mongodb.ipynb) | [![View Article](https://img.shields.io/badge/View%20Article-blue)](https://www.mongodb.com/developer/products/atlas/claude_3_5_sonnet_rag/)|
| Agentic HR Chatbot | Claude 3.5, LangGraph, MongoDB | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/mongodb-developer/GenAI-Showcase/blob/main/notebooks/agents/hr_agentic_chatbot_with_langgraph_claude.ipynb) | Coming Soon|
|AWS Bedrock Agent | Claude 3, AWS Bedrock, Python, MongoDB | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/mongodb-developer/GenAI-Showcase/blob/main/notebooks/agents/mongodb_with_aws_bedrock_agent.ipynb) | [![View Article](https://img.shields.io/badge/View%20Article-blue)](https://www.mongodb.com/developer/products/atlas/mdb-aws-bedrock-agent-start/)

## Workshops
Workshops are designed to take learners through the step-by-step process of developing LLM applications. These workshops include essential explanations, definitions, and resources provided within the notebooks and projects. Each workshop is structured to build foundational knowledge and progressively advance to more complex topics. Practical exercises and real-world examples ensure that learners can apply the concepts effectively, making it easier to understand the integration and deployment of generative AI applications.

| Title | Colab Link |
|-------|------------|
| Pragmatic LLM Application Development: From RAG Pipelines to AI Agent | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/mongodb-developer/GenAI-Showcase/blob/main/notebooks/workshops/Pragmatic_LLM_Application_Introduction_From_RAG_to_Agents_with_MongoDB.ipynb) |
| Building chatbots with NextJS and Atlas Vector search | [![View Article](https://img.shields.io/badge/View%20Article-blue)](https://mongodb-developer.github.io/vector-search-workshop)


## Tools
Useful tools and utilities for working with generative AI models:
- [Embeddings Generator](/tools/embeddings_generator): A set of scripts for generating and manipulating embeddings.

## Datasets
Below are various datasets with embeddings for use in LLM application POCs and demos. All datasets can be accessed and downloaded from their respective Hugging Face pages.


| Dataset Name                                      | Description | Link |
| ------------------------------------------------- | ----------- | ---- |
| Cosmopedia             | Chunked version of a subset of the data Cosmopedia dataset | [![View Dataset](https://img.shields.io/badge/View%20Dataset-8A2BE2)](https://huggingface.co/datasets/MongoDB/subset_arxiv_papers_with_embeddings)  |
| Movies                           | Western, Action, and Fantasy movies, including title, release year, cast, and OpenAI embeddings for vector search. | [![View Dataset](https://img.shields.io/badge/View%20Dataset-8A2BE2)](https://huggingface.co/datasets/MongoDB/embedded_movies)  |
| Airbnb                         | AirBnB listings dataset with property descriptions, reviews, metadata and embeddings. | [![View Dataset](https://img.shields.io/badge/View%20Dataset-8A2BE2)](https://huggingface.co/datasets/MongoDB/airbnb_embeddings)  |
| Tech News                      | Tech news articles from 2022 and 2023 on valuable tech companies. | [![View Dataset](https://img.shields.io/badge/View%20Dataset-8A2BE2)](https://huggingface.co/datasets/MongoDB/tech-news-embeddings)  |
| Restaurant                  | Restaurant dataset with location, cuisine, ratings, attributes for industry analysis, recommendations, and geographical studies.  | [![View Dataset](https://img.shields.io/badge/View%20Dataset-8A2BE2)](https://huggingface.co/datasets/MongoDB/whatscooking.restaurants)  |
Subset Arxiv papers | This arXiv subset has 256-dimensional OpenAI embeddings for each entry, created by combining title, author(s), and abstract. | [![View Dataset](https://img.shields.io/badge/View%20Dataset-8A2BE2)](https://huggingface.co/datasets/MongoDB/subset_arxiv_papers_with_embeddings)



## General Knowledge
Thought leadership in AI is not an option, we take it seriously. That's why we've curated articles and pieces created by our team to get you conversation-ready and equipped with the right information to make key decisions when building AI products.

| Title | Link |
|-------|------|
| What is an AI Stack? | [![View Article](https://img.shields.io/badge/View%20Article-blue)](https://www.mongodb.com/developer/products/atlas/agent-fireworksai-mongodb-langchain/) |
| How to Optimize LLM Applications With Prompt Compression Using LLMLingua and LangChain | [![View Article](https://img.shields.io/badge/View%20Article-blue)](https://www.mongodb.com/developer/products/atlas/prompt_compression/) |
| What is Atlas Vector Search | [![View Article](https://img.shields.io/badge/View%20Article-blue)](https://www.mongodb.com/products/platform/atlas-vector-search) |
| How to Choose the Right Chunking Strategy for Your LLM Application | [![View Article](https://img.shields.io/badge/View%20Article-blue)](https://www.mongodb.com/developer/products/atlas/choosing-chunking-strategy-rag/) |
| How to Choose the Right Embedding Model for Your LLM Application | [![View Article](https://img.shields.io/badge/View%20Article-blue)](https://www.mongodb.com/developer/products/atlas/choose-embedding-model-rag/) |
| How to Evaluate Your LLM Application | [![View Article](https://img.shields.io/badge/View%20Article-blue)](https://www.mongodb.com/developer/products/atlas/evaluate-llm-applications-rag/) |



## Contributing
We welcome contributions! Please read our [Contribution Guidelines](CONTRIBUTING.md) for more information on how to participate.

## License
This project is licensed under the [MIT License](LICENSE).

## Contact
Feel free to reach out for any queries or suggestions:
- Email: richmond.alake@mongodb.com
- Email: apoorva.joshi@mongodb.com
- Email: pavel.duchovny@mongodb.com
