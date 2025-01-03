# Practical Multi AI Agents and Advanced Use Cases with crewAI

This repository contains hands-on notebooks for advanced use cases with crewAI, designed to explore various applications using multiple AI agents. Each lesson builds on the capabilities of crewAI for different practical scenarios.

These materials are adapted from the [Practical Multi AI Agents and Advanced Use Cases with crewAI](https://learn.deeplearning.ai/courses/practical-multi-ai-agents-and-advanced-use-cases-with-crewai) course by Deeplearning AI.

# Lessons Overview

## Lesson L1: Automated Project Planning
**Task**: Develop a system that automates project planning by breaking down projects into tasks, estimating time requirements, and allocating resources accordingly.

**Agents**:

* Project Planner Agent: Responsible for decomposing the project into manageable tasks.
* Time Estimator Agent: Estimates the time required for each task.
* Resource Allocator Agent: Assigns appropriate resources to each task based on availability and requirements.
* These agents collaborate to streamline the project planning process, ensuring efficient task breakdown, accurate time estimation, and optimal resource allocation.

## Lesson L2: Project Progress Reporting
**Task**: Create a system that generates progress reports by interacting with project management tools, such as Trello, to monitor and report on project status.

**Agents**:

* Data Retrieval Agent: Fetches current project data from the project management tool.
* Progress Analyzer Agent: Analyzes the retrieved data to assess the status of tasks and overall project progress.
* Report Generator Agent: Compiles the analysis into a structured progress report for stakeholders.
* This setup enables automated, up-to-date reporting on project progress, facilitating informed decision-making.

## Lesson L3: Agentic Sales Pipeline
**Task**: Develop an agent-based sales pipeline that processes lead information, enriches and scores leads, and drafts personalized emails for qualified prospects.

**Agents**:

* Lead Information Agent: Gathers and enriches lead data from various sources.
* Lead Scoring Agent: Evaluates and scores leads based on predefined criteria to determine their potential value.
* Email Drafting Agent: Creates personalized email drafts tailored to the interests and needs of qualified leads.
* This agentic system automates the lead management process, enhancing efficiency and personalization in sales communications.

## Lesson L4: Support Data Insight Analysis
**Task**: Establish a pipeline that analyzes customer support data to generate issue reports and visualizations, aiding in the identification of common problems and areas for improvement.

**Agents**:

* Data Extraction Agent: Collects customer support data from various channels.
* Issue Analysis Agent: Identifies and categorizes common issues within the support data.
* Visualization Agent: Creates visual representations of the analyzed data to highlight trends and insights.
* This configuration facilitates a deeper understanding of customer support dynamics, enabling targeted improvements.

## Lesson L5: Content Creation at Scale
**Task**: Design a system that automates large-scale content creation by researching topics, generating content, and preparing social media posts.

**Agents**:

* Research Agent: Conducts online research to gather information on specified topics.
* Content Generation Agent: Produces written content based on the research findings.
* Social Media Agent: Crafts social media posts to promote the generated content across various platforms.
* This agentic approach streamlines the content creation process, enabling efficient production and dissemination of information.


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