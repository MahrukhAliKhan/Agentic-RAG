# Agentic-RAG
## Build a LangChain Agentic RAG system using the OpenAI model (gpt-4o-mini)

In this tutorial, you will create a LangChain agentic RAG system using the OpenAI (gpt-40-mini) that can answer complex queries about the 2024 US Open using external information.

# Overview of agentic RAG
## What is RAG?

RAG is a technique in natural language processing (NLP) that combines information retrieval and generative models to produce more accurate, relevant and contextually aware responses. In traditional language generation tasks, large language models (LLMs) such as Meta's [Llama Models](https://llama.meta.com/) or IBM’s [Granite Models](https://www.ibm.com/granite) are used to construct responses based on an input prompt. Common real-world use cases of these LLMs are chatbots. When models are missing relevant information that is up to date in their knowledge base, RAG is a powerful tool.

## What are AI agents?

At the core of agentic RAG systems are artificial intelligence (AI) agents. An AI agent refers to a system or program that is capable of autonomously performing tasks on behalf of a user or another system by designing its workflow and using available tools. Agentic technology implements tool use on the backend to obtain up-to-date information from various data sources, optimize workflow and create subtasks autonomously to solve complex tasks. These external tools can include external data sets, search engines, APIs and even other agents. Step-by-step, the agent reassesses its plan of action in real time and self-corrects.  

## Agentic RAG vs Traditional RAG

Agentic RAG frameworks are powerful as they can encompass more than just one tool. In traditional RAG applications, the LLM is provided with a vector database to reference when forming its responses. In contrast, agentic RAG implementations are not restricted to document agents that only perform data retrieval. RAG agents can also have tools for tasks such as solving mathematical calculations, writing emails, performing data analysis and more. These tools can be supplemental to the agent's decision-making process. AI agents are context-aware in their multistep reasoning and can determine when to use appropriate tools.

AI agents, or intelligent agents, can also work collaboratively in multiagent systems, which tend to outperform singular agents. This scalability and adaptability is what sets apart agentic RAG agents from traditional RAG pipelines. 

## Implementation
Follow each step in the agentic-rag.ipynb file. Create a virtual environment using python3.9
```
sudo apt install python3.9-venv
python3.9 -m venv venv
source venv/bin/activate
```