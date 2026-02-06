# LangGraph Tool-Based AI Workflow

A simple agent workflow built using **LangGraph**, **LangChain**, and **OpenAI**, which allows an LLM to decide when to call external tools (like web search) and use the results to generate better answers.

## 🚀 Features

- Tool calling using LangGraph workflow
- Tavily search tool integration for real-time information
- Message state management using LangGraph
- Conditional routing between LLM and tools
- Simple UI using Gradio
- Tracing and debugging using LangSmith

## 🛠️ Tech Stack

- Python
- LangGraph
- LangChain
- OpenAI / GPT models
- Tavily Search API
- Gradio
- Jupyter Notebook

## 📂 Project Structure

simple-search-agent/
│
├── workflow.ipynb
├── requirements.txt
└── README.md


## ⚙️ Setup

### 1. Clone Repository

git clone https://github.com/jaysahu-ai/simple-search-agent
cd simple-search-agent


### 2. Install Dependencies

pip install -r requirements.txt


### 3. Set Environment Variables

Create a `.env` file or set variables manually:

OPENAI_API_KEY=your_key
TAVILY_API_KEY=your_key
LANGCHAIN_API_KEY=your_key # Optional (for tracing)


### 4. Run Notebook

Open the Jupyter notebook and execute cells sequentially.

## 💡 What This Project Demonstrates

- Building agent-style workflows using LangGraph
- Tool integration with LLMs
- State-based orchestration
- Real-time information retrieval for LLM responses

## 📌 Future Improvements

- Multi-agent validation loop
- Blog/news content generation agent
- Better UI and deployment
- Additional tool integrations

---

