# Practical Multi AI Agents and Advanced Use Cases with crewAI

This repository contains hands-on notebooks for advanced use cases with crewAI, designed to explore various applications using multiple AI agents. Each lesson builds on the capabilities of crewAI for different practical scenarios.

These materials are adapted from the [Practical Multi AI Agents and Advanced Use Cases with crewAI](https://learn.deeplearning.ai/courses/practical-multi-ai-agents-and-advanced-use-cases-with-crewai) course by Deeplearning AI.

# Lessons Overview

- **L1: Single-Agent Tasks**  
  Introduction to using crewAI for single-agent tasks. This lesson demonstrates how to set up crewAI for simple, focused tasks, leveraging individual agents for precise functions.

- **L2: Multi-Agent Collaboration**  
  Explores how multiple crewAI agents can work together to tackle more complex tasks by sharing information and coordinating outputs.

- **L3: Data Extraction and Processing**  
  Demonstrates crewAI’s utility in data extraction tasks, where multiple agents are used to retrieve, process, and structure data from various sources.

- **L4: Summarization and Content Generation**  
  Utilizes crewAI to perform summarization and content generation, with agents designed to create cohesive summaries from lengthy inputs and to produce new content.

- **L5: Decision-Making with AI Agents**  
  Focuses on using crewAI for decision-making applications, employing agents that analyze scenarios, evaluate alternatives, and provide informed recommendations.

# Setup Instructions

1. Clone this repository.
2. Create an `.env` file in the root directory.
3. Add your API keys for OpenAI, Serper, and Groq as follows:
    ```
    OPENAI_API_KEY=your_openai_key
    SERPER_API_KEY=your_serper_key
    GROQ_API_KEY=your_groq_key
    ```
4. Install the required libraries by running:
    ```
    pip install -r requirements.txt
    ```