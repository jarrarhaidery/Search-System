# 🔍 Search System — AI-Powered Research Pipeline

An agentic search and research system that autonomously performs web research, synthesizes information from multiple sources, and generates structured, readable reports — built with LangChain and a modular pipeline architecture.

---

## 🚀 What It Does

- Takes a research query and autonomously searches, retrieves, and synthesizes information
- Processes results through a structured pipeline: **search → retrieve → rank → summarize**
- Outputs clean, structured research reports from multiple sources
- Modular architecture makes it easy to swap search providers or output formats

---

## 🛠️ Tech Stack

| Layer | Technology |
|---|---|
| Framework | LangChain |
| Language | Python |
| Interface | Streamlit / CLI |
| Search | Web Search API |
| Structure | Template-based report generation |

---

## 📁 Project Structure

```
Search-System/
├── app.py           # Main application entry point
├── src/             # Core pipeline modules
├── research/        # Research output storage
├── template.py      # Report template definitions
├── setup.py         # Package setup
├── test.py          # Test suite
└── requirements.txt
```

---

## ⚙️ Setup & Installation

```bash
# 1. Clone the repository
git clone https://github.com/jarrarhaidery/Search-System.git
cd Search-System

# 2. Install dependencies
pip install -r requirements.txt

# 3. Configure API keys in .env
GEMINI_API_KEY=your_key_here
SEARCH_API_KEY=your_key_here

# 4. Run the application
python app.py
```

---

## 💡 How It Works

1. **Query Input** — User provides a research topic or question
2. **Search** — System performs targeted web searches to gather relevant sources
3. **Retrieval & Ranking** — Results are filtered and ranked by relevance
4. **Synthesis** — LangChain pipeline synthesizes findings into a coherent summary
5. **Report Generation** — Output is structured using predefined templates and saved to `research/`

---

## 📌 Topics

`langchain` `ai-research` `search` `agentic-ai` `python` `llm` `information-retrieval` `generative-ai` `automation`
