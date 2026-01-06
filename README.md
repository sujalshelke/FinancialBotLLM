# FinancialBotLLM
## RAG streamlit based Financial bot

Welcome to the “Guided Live Project - Financial Bot with LLMs” module of the Applied GenAI:
Advanced Training for Tech Professionals and Managers course. In the fast-paced financial sector,
artificial intelligence is becoming essential for enhancing customer experience and data analysis.
This module focuses on building a financial bot that leverages Large Language Models (LLMs),
Vector Databases, and web scraping techniques. Learners will learn to build a responsive
financial chatbot capable of handling a variety of financial queries and providing real-time
insights through efficient data retrieval mechanisms.

## Learning Objectives
By the end of this module, you will:
● Understand and apply web scraping techniques to gather financial data.
● Integrate LLMs with VectorDB for optimized data querying and retrieval.
● Fine-tune LLMs for specialized financial queries to enhance response accuracy.
● Develop an interactive, user-friendly interface with Streamlit to facilitate chatbot
interactions.

## Milestones
1. Data Collection and Integration
● Objective: Set up web scraping to retrieve financial data, structure and vectorize
data for the database.
○ Web scraping for financial data
○ Structuring financial data for embeddings
○ Storing embeddings in a VectorDB (e.g., Chroma)

2. LangChain for Query Optimization

● Objective: Use LangChain to translate natural language queries into relevant
database queries.
○ Setting up LangChain with VectorDB
○ Prompt engineering and optimization
○ Efficient data ingestion and retrieval with LangChain

3. Retrieval-Augmented Generation (RAG)
● Objective: Understand RAG and use it to enhance LLM responses with accurate,
contextual information.
○ Introduction to RAG
○ Implementing RAG with financial data
○ Best practices for retrieval and generation

4. Chatbot Development with Streamlit
● Objective: Develop a chatbot interface in Streamlit with conversation memory
and interactive capabilities.
○ Building the Streamlit chat interface
○ Integrating the LLM-based bot with VectorDB
○ Memory management for seamless user experience

5. Dashboard and Visualization Integration
● Objective: Enhance chatbot responses with graphical insights and visualizations.
○ Creating interactive charts and graphs
○ Displaying financial data insights visually
○ Customizing visualization options for various query types

## Hands-On Post-Class Assignments
● Implement a web scraper for a financial website of your choice, storing results in a CSV
file.
● Set up a VectorDB, store embeddings, and test retrieval with a custom prompt.
● Build and deploy a Streamlit-based chatbot for answering financial queries.
● Fine-tune prompts to handle nuanced financial questions and visualize insights.

## Implementation and run instructions
The solution is self-contained where you would need to run only one file fin_bot.py

- Start by installing the dependencies by running pip install -r requirements.txt
- Runt the RAG application from the terminal by running 
	python3 fin_bot.py OPENAI_API_KEY THE_QUESTION
