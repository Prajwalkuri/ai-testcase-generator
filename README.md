
# AI Test Case Generator

> **Built by Prajwal ** — AI/ML Graduate | QA Automation Enthusiast

An AI-powered tool that generates professional, structured test cases from any feature description — covering Happy Path, Negative, Boundary, Security, and Performance scenarios.

#Features

- Dual LLM support** — works with Ollama (free, local) and OpenAI API
- Smart test generation** — covers all test types automatically
- Excel export** — download colour-coded test cases instantly
- Filter & view** — filter by test type and priority on screen
- Quick examples** — one-click feature templates to try immediately

#Tech Stack

- Python** + **Streamlit** — UI and app framework
- LangChain-style Prompt Engineering** — structured LLM prompting
- OpenAI API / Ollama (Llama3)** — LLM backends
- openpyxl + Pandas** — Excel generation and data handling

#How to Use

1. Select your LLM provider in the sidebar (OpenAI key needed for OpenAI)
2. Paste your feature description in the text box
3. Or click a quick example button
4. Click **Generate Test Cases**
5. View on screen, filter, and download as Excel

#Run Locally

```bash
git clone https://huggingface.co/spaces/YOUR_USERNAME/ai-test-case-generator
cd ai-test-case-generator
pip install -r requirements.txt

# For Ollama: make sure ollama is running
ollama serve
ollama pull llama3

streamlit run app.py
```

#Skills Demonstrated

This project demonstrates:
- Prompt Engineering** — structured JSON output from LLMs
- LLM Integration** — dual provider support (OpenAI + Ollama)
- Generative AI** applied to QA workflows
- Python + Streamlit** — production-ready web app
- QA Domain Knowledge** — test types, priorities, structured test cases
