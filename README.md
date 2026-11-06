# AI-Powered Autonomous Research Agent 🤖

An intelligent AI-powered research assistant built using **Python, FastAPI, Ollama, and Qwen3 (4B)** that automates the end-to-end research process. The system transforms user queries into structured research reports by combining AI-driven planning, web search, information extraction, evidence verification, and automated report generation.

## 🚀 Features

- **AI Research Planning:** Breaks down research queries into structured research tasks.
- **Intelligent Web Search:** Retrieves relevant information from multiple online sources using DuckDuckGo.
- **Content Extraction:** Extracts and processes webpage content using BeautifulSoup and Requests.
- **Evidence Verification:** Evaluates research findings to improve the reliability of generated information.
- **Automated Report Generation:** Produces structured, readable Markdown research reports.
- **Local LLM Integration:** Uses Qwen3 (4B) through Ollama for local AI inference.
- **Interactive Web Interface:** Displays research progress and generated results through a frontend dashboard.
- **REST API Integration:** Uses FastAPI to connect the research engine with the frontend.

## 🛠️ Tech Stack

**Backend:** Python, FastAPI, Uvicorn, Pydantic

**AI/LLM:** Ollama, Qwen3 (4B)

**Web Research:** DuckDuckGo, Requests, BeautifulSoup

**Frontend:** HTML5, CSS3, JavaScript

## ⚙️ Project Architecture

1. User submits a research query.
2. The AI agent analyzes the query and creates a research plan.
3. The system searches the web and extracts relevant information.
4. Research findings undergo evidence verification.
5. The AI synthesizes the collected information.
6. A structured Markdown research report is generated and displayed.

## 💻 Installation and Setup

### 1. Clone the repository

```bash
git clone https://github.com/YOUR_USERNAME/ai-research-agent.git
cd ai-research-agent
```

### 2. Create a virtual environment

```bash
python -m venv venv
```

### 3. Activate the environment

**Windows:**
```powershell
venv\Scripts\activate
```

### 4. Install dependencies

```bash
pip install fastapi uvicorn ollama requests beautifulsoup4 pydantic
```

### 5. Install Ollama and download the model

Install Ollama from https://ollama.com/

```bash
ollama pull qwen3:4b
```

### 6. Start the application

Ensure Ollama is running, then execute:

```bash
uvicorn main:app --reload
```

### 7. Access the application

- **Web Application:** http://127.0.0.1:8000
- **API Documentation:** http://127.0.0.1:8000/docs

## 🎯 Project Objective

The objective of this project is to simplify and accelerate research by combining autonomous AI workflows, large language models, and web information retrieval into a unified research assistant.

## 🔮 Future Enhancements

- Multi-agent research collaboration.
- Advanced source credibility scoring.
- PDF and DOCX report exports.
- Research history and persistent storage.
- Improved citation management and source traceability.

---

**Developed as an AI engineering project exploring autonomous agents, local LLM deployment, web research automation, and full-stack application development.**
