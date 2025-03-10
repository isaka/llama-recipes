# End to End Use Applications using various Llama Models

## [Agentic Tutorial](./agents/): 

### 101 and 201 tutorials on performing Tool Calling and building an Agentic Workflow using Llama Models
101 notebooks show how to apply Llama models and enable tool calling functionality, 201 notebook walks you through an end to end workflow of building an agent that can search two papers, fetch their details and find their differences.

## [Benchmarks](./benchmarks/): 

### A folder contains benchmark scripts 
The scripts apply a throughput analysis and introduction to `lm-evaluation-harness`, a tool to evaluate Llama models including quantized models focusing on quality

## [Browser Usage](./browser_use/): 

### Demo of how to apply Llama models and use them for browsing the internet and completing tasks

## [Automatic Triaging of Github Repositories](./github_triage/walkthrough.ipynb): 

### Use Llama to automatically triage issues in an OSS repository and generate insights to improve community experience
This tool utilizes an off-the-shelf Llama model to analyze, generate insights, and create a report for better understanding of the state of a repository. It serves as a reference implementation for using Llama to develop custom reporting and data analytics applications.

## [VideoSummary](video_summary.ipynb): 

### Ask Llama 3 to Summarize a Long YouTube Video (using Replicate or [OctoAI](../3p-integrations/octoai/video_summary.ipynb))
This demo app uses Llama 3 to return a text summary of a YouTube video. It shows how to retrieve the caption of a YouTube video and how to ask Llama to summarize the content in different ways, from the simplest naive way that works for short text to more advanced methods of using LangChain's map_reduce and refine to overcome the 8K context length limit of Llama 3.

## [NBA2023-24](./coding/text2sql/quickstart.ipynb): 

### Ask Llama 3 about Structured Data
This demo app shows how to use LangChain and Llama 3 to let users ask questions about **structured** data stored in a SQL DB. As the 2023-24 NBA season is entering the playoff, we use the NBA roster info saved in a SQLite DB to show you how to ask Llama 3 questions about your favorite teams or players.

## [NotebookLlama](./NotebookLlama/): 

### PDF to Podcast using Llama Models
Workflow showcasing how to use multiple Llama models to go from any PDF to a Podcast and using open models to generate a multi-speaker podcast

## [live_data](live_data.ipynb): 

### Ask Llama 3 about Live Data (using Replicate or [OctoAI](../3p-integrations/octoai/live_data.ipynb))
This demo app shows how to perform live data augmented generation tasks with Llama 3, [LlamaIndex](https://github.com/run-llama/llama_index), another leading open-source framework for building LLM apps, and the [Tavily](https://tavily.com) live search API.

## [WhatsApp Chatbot](./customerservice_chatbots/whatsapp_chatbot/whatsapp_llama3.md): 
### Building a Llama 3 Enabled WhatsApp Chatbot
This step-by-step tutorial shows how to use the [WhatsApp Business API](https://developers.facebook.com/docs/whatsapp/cloud-api/overview) to build a Llama 3 enabled WhatsApp chatbot.

## [Messenger Chatbot](./customerservice_chatbots/messenger_chatbot/messenger_llama3.md): 

### Building a Llama 3 Enabled Messenger Chatbot
This step-by-step tutorial shows how to use the [Messenger Platform](https://developers.facebook.com/docs/messenger-platform/overview) to build a Llama 3 enabled Messenger chatbot.

### RAG Chatbot Example (running [locally](./customerservice_chatbots/RAG_chatbot/RAG_Chatbot_Example.ipynb) or on [OctoAI](../3p-integrations/octoai/RAG_chatbot_example/RAG_chatbot_example.ipynb))
A complete example of how to build a Llama 3 chatbot hosted on your browser that can answer questions based on your own data using retrieval augmented generation (RAG). You can run Llama2 locally if you have a good enough GPU or on OctoAI if you follow the note [here](../README.md#octoai_note).

## [Sales Bot](./customerservice_chatbots/ai_agent_chatbot/SalesBot.ipynb): 

### Sales Bot with Llama3 - A Summarization and RAG Use Case
An summarization + RAG use case built around the Amazon product review Kaggle dataset to build a helpful Music Store Sales Bot. The summarization and RAG are built on top of Llama models hosted on OctoAI, and the vector database is hosted on Weaviate Cloud Services.
