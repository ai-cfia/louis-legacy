# louis

## Introduction

Conversational agents based on LLM (Large Language Models) such as OpenAI ChatGPT or Google Bard have the potential to 10x productivity of employees by retrieving concise answers to complex questions with the ability to compose, translate and rewrite. With plugins, they also have the capability to interact with other API and complete tasks on behalf of users. 

The CFIA (Canadian Food Inspection Agency) AI Lab is currently prototyping solutions using OpenAI LLM (Large Language Model) ChatGPT and reaching out to all organization stakeholders to work with them at experimenting tasks that can be assisted by the use of LLM.

## Objective

Create a conversational agent against our public and private knowledge base that can reliably and accurately provide relevant and focused answer to questions related to the CFIA to all users.

This requires an excellent search facility to feed chunks of relevant information to each query to the Large Language Model(s) (LLM).

## Louis

![image](https://github.com/ai-cfia/louis/assets/538542/a992e13d-e00e-466a-a960-ea79f50ba018)


## Finesse
![image](https://github.com/ai-cfia/louis/assets/538542/adf66a0c-8e7e-48bd-99f9-f007e9ebcf7b)

![image](https://github.com/ai-cfia/louis/assets/538542/e4ca684c-ff6f-4ce7-8605-c7c28dc68933)

## Implementation

Louis is implemented as an opensource project made up of multiple repositories under the CFIA AI Laboratory Github organization:

* Louis backend: https://github.com/ai-cfia/louis-backend
  * relational database schema
  * web scrapping and text manipulation job processing (based on scrapy)
  * API (Application Programming Interface) for semantic search
  * API (Application Programming Interface) for conversational agent
* Louis Chat: https://github.com/ai-cfia/louis-frontend
  * React implementation of the frontend to the conversational agent
* Louis Finesse: https://github.com/ai-cfia/louis-smartsearch-frontend
  * React implementation of the frontend to semantic search.

## System diagram

![louis drawio](https://github.com/ai-cfia/louis/assets/538542/2ffda0ed-55e0-42ce-8150-65d6a79f52d2)

## References

* [HuggingChat: open source alternative to ChatGPT](https://huggingface.co/chat/)
* [LangChain: Building applications with LLMs through composability](https://github.com/hwchase17/langchain)
  * [BabyAGI with Tools](https://python.langchain.com/en/latest/use_cases/autonomous_agents/baby_agi_with_agent.html)
* [Pinecone: Long-term Memory for AI](https://www.pinecone.io/)
* [AgentGPT: Assemble, configure, and deploy autonomous AI Agents in your browser.](https://github.com/reworkd/AgentGPT)

