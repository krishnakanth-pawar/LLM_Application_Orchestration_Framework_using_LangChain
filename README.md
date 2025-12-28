# LLM Application Orchestration Framework using LangChain
## Overview

This project demonstrates how to build **prompt-driven LLM workflows** using **LangChain** and **OpenAI chat models**.
It focuses on **modern runnable-based orchestration**, showing how to design **sequential and parallel LLM pipelines** using LangChain Expression Language (LCEL).

---

## Tech Stack

* Python
* LangChain
* OpenAI Chat Models
* Prompt Engineering
* Jupyter Notebook
* Environment Variables (`.env`)

---

## Features

* Dynamic prompt engineering using `PromptTemplate` and `ChatPromptTemplate`
* Runnable-based LLM pipelines using the pipe (`|`) operator (LCEL)
* Multi-step workflows with output passing between LLM tasks
* Parallel execution for concurrent multilingual translation
* Custom `RunnableLambda` for intermediate processing and logging
* Secure API key management using environment variables

---

## Setup

1. **Install dependencies**

```bash
pip install python-dotenv langchain-openai langchain-community
```

2. **Create a `.env` file**

```env
OPENAI_API_KEY=your_openai_api_key_here
```

3. **Run the Jupyter Notebook** to execute the LLM workflows.

---



Just say the word.
