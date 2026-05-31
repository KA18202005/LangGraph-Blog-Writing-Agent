# 🚀 LangGraph Blog Writing Agent

An AI-powered Blog Writing Agent built using **LangGraph**, **LangChain**, **Google Gemini**, and **Tavily Search**. This project demonstrates the evolution of a blog-writing agent from a basic implementation to a research-enhanced, image-capable workflow while also providing a frontend and backend application for generating high-quality blog content.

## ✨ Features

* 📝 Generate complete blog articles from a topic
* 🔍 Research-powered content generation using Tavily Search
* 🧠 Multi-step agent workflow with LangGraph
* 🎯 Improved prompting techniques for better outputs
* 🖼️ AI-assisted image generation support
* 🌐 Interactive frontend application
* ⚡ Backend API for blog generation
* 📚 Progressive learning notebooks demonstrating agent development

---

## 🏗️ Project Structure

```text
LangGraph-Blog-Writing-Agent/
│
├── bwa_frontend.py
├── bwa_backend.py
│
├── 1_bwa_basic.ipynb
├── 2_bwa_improved_prompting.ipynb
├── 3_bwa_research.ipynb
├── 4_bwa_research_fine_tuned.ipynb
├── 5_bwa_image.ipynb
│
├── tavily_test.ipynb
│
├── ai_unpacked_the_weeks_top_developments_in_funding_research_and_regulation_may_24-31_2026.md
│
├── requirements.txt
├── .gitignore
└── README.md
```

---

## 📖 Notebook Roadmap

### 1️⃣ Basic Blog Writing Agent

**File:** `1_bwa_basic.ipynb`

* Introduction to LangGraph
* Basic blog generation workflow
* Single-agent content creation

### 2️⃣ Improved Prompting

**File:** `2_bwa_improved_prompting.ipynb`

* Advanced prompt engineering
* Better structure and readability
* Enhanced blog quality

### 3️⃣ Research Agent

**File:** `3_bwa_research.ipynb`

* Integrates external research
* Uses search tools for fact gathering
* Produces more informative content

### 4️⃣ Fine-Tuned Research Workflow

**File:** `4_bwa_research_fine_tuned.ipynb`

* Improved research pipeline
* Better source utilization
* Higher quality article generation

### 5️⃣ Image-Enhanced Blog Agent

**File:** `5_bwa_image.ipynb`

* Adds image generation capabilities
* Creates richer blog content
* Demonstrates multimodal workflows

---

## 🛠️ Tech Stack

### AI & Agent Frameworks

* LangGraph
* LangChain

### LLM

* Google Gemini

### Search & Research

* Tavily Search API

### Frontend

* Streamlit

### Backend

* Python

### Utilities

* Python Dotenv
* Requests

---

## ⚙️ Installation

### Clone Repository

```bash
git clone https://github.com/KA18202005/LangGraph-Blog-Writing-Agent.git
cd LangGraph-Blog-Writing-Agent
```

### Create Virtual Environment

```bash
python -m venv venv
```

#### Windows

```bash
venv\Scripts\activate
```

#### Linux/macOS

```bash
source venv/bin/activate
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

---

## 🔑 Environment Variables

Create a `.env` file in the project root:

```env
GOOGLE_API_KEY=your_google_api_key
TAVILY_API_KEY=your_tavily_api_key
```

---

## ▶️ Running the Application

### Start Backend

```bash
python bwa_backend.py
```

### Start Frontend

```bash
streamlit run bwa_frontend.py
```

Open the local Streamlit URL displayed in the terminal.

---

## 🔄 Agent Workflow

```text
User Topic
     │
     ▼
Planning Agent
     │
     ▼
Research Agent
     │
     ▼
Content Generation Agent
     │
     ▼
Refinement Agent
     │
     ▼
Image Generation
     │
     ▼
Final Blog Output
```

---

## 📄 Sample Output

The repository includes an example generated article:

```text
ai_unpacked_the_weeks_top_developments_in_funding_research_and_regulation_may_24-31_2026.md
```

This demonstrates the quality and structure of the generated blog content.

---

## 🎯 Learning Outcomes

By exploring this project, you'll learn:

* LangGraph fundamentals
* Agent-based workflow design
* Prompt engineering techniques
* Research-Augmented Generation (RAG)
* Search tool integration
* AI content creation pipelines
* Streamlit application development

---

## 🚀 Future Improvements

* Multiple LLM support
* SEO optimization module
* Blog export to PDF/DOCX
* Citation generation
* Multi-language blog generation
* Publishing directly to CMS platforms

---

## 🤝 Contributing

Contributions are welcome.

1. Fork the repository
2. Create a feature branch

```bash
git checkout -b feature-name
```

3. Commit your changes

```bash
git commit -m "Add feature"
```

4. Push to GitHub

```bash
git push origin feature-name
```

5. Open a Pull Request

---

## ⭐ Support

If you found this project helpful:

* ⭐ Star the repository
* 🍴 Fork the repository
* 🚀 Share it with others

---

## 👨‍💻 Author

**Kavya Agarwal**

GitHub: https://github.com/KA18202005

---

Built with ❤️ using LangGraph, LangChain, Gemini, and Tavily Search.
