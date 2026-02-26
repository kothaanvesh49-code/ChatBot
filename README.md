# ChatBot


LangChain - A Framework for developing applications powered by LLMs

What is LangChain?
LangChain is an open-source framework that acts like a toolkit and orchestration layer for building applications with Large Language Models.

It simplifies the process of chaining together different components (like LLMs, data sources, and tools) to create complex, intelligent applications. It's designed to make prompt engineering more efficient and allow developers to adapt language models to specific business contexts.

Imagine you want to build a truly smart application powered by a Large Language Model (LLM), like OpenAI's GPT or Google's Gemini. Simply sending a prompt to an LLM isn't usually enough for real-world scenarios. You often need to:

Get relevant information: Your LLM might need to access external data (your documents, a database, the internet) to answer a user's question accurately.
Remember past conversations: For a coherent dialogue, the LLM needs a memory of what was said before.
Perform actions: Sometimes, the LLM needs to "do" something, like search the web, call an API, or run a calculator.
Structure its output: You might want the LLM's response to be in a specific format (e.g., JSON, a bulleted list).


This project is a simple conversational AI chatbot built using LangGraph and LangChain, designed to demonstrate how stateful LLM workflows can be implemented using graph-based architectures. The chatbot leverages both OpenAI’s GPT-4o and Groq’s LLaMA 3.1 (8B Instant) models to generate intelligent responses. Using LangGraph’s StateGraph, I implemented a structured flow with defined START and END nodes, along with a custom state schema to manage conversation history through message reducers. The project also incorporates environment variable management for secure API key handling and demonstrates how to invoke large language models programmatically within a controlled graph execution pipeline. Additionally, the graph structure is visualized using Mermaid diagrams for better interpretability. This project highlights my hands-on experience with LLM orchestration, conversational state management, and graph-based AI workflow design, making it a foundational implementation for building scalable, production-ready AI assistants.
