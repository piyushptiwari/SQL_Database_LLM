Title: SQL_Database_LLM: Query Databases with Natural Language

Project Description

Harness the power of LLMs, LangChain, and SQL Agents to build an intuitive natural language interface for database querying.
Ask questions about your database in plain English to get insights and analytics without needing to write SQL code directly.

Key Features

Natural Language Understanding: Translates user questions using advanced language models like ChatGPT to generate accurate database queries.
SQL Integration: Seamlessly transforms questions into actionable SQL queries with LangChain's SQL agents.
Multi-Domain Support: Adaptable to various databases and schemas.
Error Handling: Includes graceful handling of potential LLM or API errors.
Data Exploration: Unlocks easy data analysis and insight generation for non-technical users.
Installation Instructions

1. Prerequisites

Python 3.x
OpenAI API Key (https://beta.openai.com/account/api-keys)
SerpApi API Key (optional, for enhanced web search capabilities)
PyMySQL for database connectivity.


2. Setup

1-Clone the repository:
Bash
git clone https://github.com/piyushptiwari/SQL_Database_LLM.git

2-Set environment variables for database connectivity and API keys:
Bash
export OPENAI_API_KEY=your_openai_api_key
export SERPAPI_API_KEY=your_serpapi_api_key (optional)
export DB_USER=your_db_user
export DB_PASSWORD=your_db_password
export DB_HOST=your_db_host
export DB_PORT=your_db_port
export DB_NAME=your_db_name
