# Autogen-Tutorial

## Overview

This repository introduces **AutoGen**, a framework developed by Microsoft for building multi-agent LLM (Large Language Model) applications. It explains how AutoGen simplifies the development of complex, interactive workflows involving agents with different capabilities and expertise. The repository provides an overview of LLMs, their capabilities, and the concept of tokenization, highlighting the importance of context length and cost considerations for different model options.

Additionally, this repository explores how to build more complex workflows using LLM Agents with sequential chats. It delves into how conversations between agents can carry over information, allowing for a series of interconnected tasks. The repository then provides a practical implementation of this concept using AutoGen, demonstrating how to create a chain of chats with information shared between agents.

### Highlights

- 🤖 **AutoGen streamlines multi-agent LLM application development.**
- 🤝 **Agents interact with each other, following various conversational patterns.**
- 💬 **Agents can represent real-world entities, LLMs, or custom components.**
- 🧠 **LLMs process input text as tokens, with context length defining their memory capacity.**
- 💰 **Different models offer varying capabilities and cost implications.**
- 🤖 **Sequential chats allow for complex workflows by carrying over information between conversations.**
- 🗝️ **The `summary` method captures information from previous chats, enabling subsequent agents to access the context.**
- 💬 **A chat can be initialized by specifying parameters such as recipient agent, message, and desired number of turns.**
- 🧑‍🏫 **The example uses three agents - an adventurer, a wizard, and a guardian - to demonstrate the concept of sequential chats.**
- 🔐 **The example showcases how the adventurer, guided by the wizard, uses the correct password to pass the guardian and access the secret world.**
