# 🛠️ lovable_clone

**lovable_clone** is an AI-powered coding assistant built with **LangGraph**. It works like a multi-agent development team that can take a natural-language request and transform it into a complete, production-ready project — file by file — using real developer workflows.

---

## 🏗️ Architecture

### **Planner Agent**
Analyzes your request and generates a detailed project plan.

### **Architect Agent**
Breaks down the plan into structured engineering tasks with clear context for each file.

### **Coder Agent**
Implements each task, writes directly into files, and uses available tools just like a real developer.

#### **Coder Agent Architecture**
![Coder Buddy Architecture](./lovable_clone.png)

---

## 🚀 Getting Started

### **Prerequisites**
- Ensure you have **uv** installed (follow installation instructions from the uv documentation).
- Create a **Groq account** and obtain an API key.

---
# ⚙️ Installation and Startup

1. **Create a virtual environment**
   ```bash
   uv venv
   source .venv/bin/activate
2. Install dependencies
    ```bash
    uv pip install -r pyproject.toml

3. Create a .env File
   Add all required variables listed in .sample_env.

4. Start the Application
   ```bash
   python main.py
# Example Prompts

Create a to-do list application using HTML, CSS, and JavaScript.

Create a simple calculator web application.

Create a simple blog API in FastAPI with a SQLite database.

