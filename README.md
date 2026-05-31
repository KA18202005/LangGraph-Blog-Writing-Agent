# 🚀 LangGraph Blog Writing Agent

An AI-powered **Blog Writing Agent** built using **LangGraph**, **LangChain**, and modern LLM workflows. This project demonstrates how to create an intelligent content generation system capable of researching, planning, and generating high-quality blog articles through an agentic workflow.

## 📌 Features

* ✍️ Automated blog generation from user prompts
* 🔍 Research-enhanced content creation
* 🧠 Multi-step reasoning using LangGraph workflows
* 📑 Structured and well-formatted blog outputs
* 🖼️ AI-generated image support
* 🔄 Improved prompting and fine-tuned workflow versions
* 📓 Step-by-step Jupyter notebooks for learning and experimentation

---

## 🏗️ Project Structure

```text
LangGraph-Blog-Writing-Agent/
│
├── 1_bwa_basic.ipynb
├── 2_bwa_improved_prompting.ipynb
├── 3_bwa_research.ipynb
├── 4_bwa_research_fine_tuned.ipynb
├── 5_bwa_image.ipynb
│
├── .gitignore
└── README.md
```

### Notebook Overview

| Notebook                          | Description                                            |
| --------------------------------- | ------------------------------------------------------ |
| `1_bwa_basic.ipynb`               | Basic blog writing agent implementation                |
| `2_bwa_improved_prompting.ipynb`  | Enhanced prompt engineering for better blog quality    |
| `3_bwa_research.ipynb`            | Adds research capabilities to improve factual accuracy |
| `4_bwa_research_fine_tuned.ipynb` | Optimized research workflow and content generation     |
| `5_bwa_image.ipynb`               | Generates relevant images alongside blog content       |

---

## 🛠️ Tech Stack

* **Python**
* **LangGraph**
* **LangChain**
* **Google Gemini**
* **OpenAI APIs** (optional)
* **Jupyter Notebook**

---

## ⚙️ Installation

### 1. Clone the Repository

```bash
git clone https://github.com/KA18202005/LangGraph-Blog-Writing-Agent.git
cd LangGraph-Blog-Writing-Agent
```

### 2. Create a Virtual Environment

```bash
python -m venv venv
```

#### Windows

```bash
venv\Scripts\activate
```

#### Linux / macOS

```bash
source venv/bin/activate
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

If a requirements file is not available, install the required packages manually:

```bash
pip install langgraph langchain langchain-community google-generativeai python-dotenv
```

---

## 🔑 Environment Variables

Create a `.env` file in the project root:

```env
GOOGLE_API_KEY=your_google_api_key
OPENAI_API_KEY=your_openai_api_key
```

Use the keys according to the model provider configured in the notebooks.

---

## ▶️ Running the Project

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Open any notebook and run the cells sequentially.

Recommended learning order:

1. Basic Agent
2. Improved Prompting
3. Research Agent
4. Fine-Tuned Research Agent
5. Image Generation Agent

---

## 🧠 How It Works

The workflow follows an agentic architecture:

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
Editing & Refinement
     │
     ▼
Final Blog Output
```

Using LangGraph, each step is represented as a node in a graph, enabling structured reasoning and modular workflow design. LangGraph is specifically designed for building stateful, multi-step AI agents and workflows.

---

## 📚 Learning Outcomes

By completing these notebooks, you'll learn:

* LangGraph fundamentals
* Building AI agents with LangChain
* Prompt engineering techniques
* Research-augmented generation
* Multi-step workflow orchestration
* AI-powered content creation
* Image generation integration

---

## 🎯 Use Cases

* Technical blog writing
* SEO content generation
* Research article drafting
* Educational content creation
* Marketing content production
* AI writing workflow experimentation

---

## 🤝 Contributing

Contributions are welcome!

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

If you found this project useful:

* Star the repository ⭐
* Fork the project 🍴
* Share it with others 🚀

---

## 📬 Connect

GitHub: https://github.com/KA18202005

If you like AI Agents, LangGraph, and Generative AI projects, feel free to connect and collaborate.

---

### Made with ❤️ using LangGraph and Generative AI
