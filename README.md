# 🌐 Website Summarizer Agent using GPT-4o-mini

An AI-powered web summarization agent that analyzes the content of a given website URL and produces a **structured summary with key insights and recommendations**.  
The application uses **OpenAI GPT-4o-mini**, custom web scraping, and a **Gradio-based UI** for interactive use.

---

## 🚀 Features
- Accepts any public website URL
- Scrapes and extracts meaningful textual content
- Generates concise, structured summaries
- Highlights key points and insights
- Provides improvement recommendations
- Interactive web interface using Gradio
- Streaming LLM responses for better UX

---

## 🧠 How It Works
1. User provides a website URL
2. The scraper extracts page content
3. Content is passed to GPT-4o-mini with a system prompt
4. The model generates a structured summary
5. Results are displayed in real time via Gradio

---

## 🛠 Tech Stack
- Python
- OpenAI API (GPT-4o-mini)
- Gradio
- Python-dotenv
- Web scraping (custom scraper)

---

## 📂 Project Structure
website-summarizer-agent/
├── summarizer.ipynb
├── scraper.py
├── README.md
├── requirements.txt
├── .gitignore
└── .env.example

---

## ▶️ How to Run

### 1. Clone the repository
```bash
git clone https://github.com/your-username/website-summarizer-agent.git
cd website-summarizer-agent
### 2. Create virtual environment (optional)
python -m venv venv
source venv/bin/activate   # Windows: venv\Scripts\activate
### 3. Install dependencies
pip install -r requirements.txt
### 4. Set environment variables
Create a .env file:
OPEN_API_KEY=your_openai_api_key
### 5. Run the notebook
jupyter notebook summarizer.ipynb
Then execute all cells to launch the Gradio interface.


---


## 🔮 Future Enhancements
- Multi-page & hierarchical summarization – Extend scraping to handle multi-page websites and generate structured, section-wise summaries.
- Document-type support – Enable ingestion and summarization of PDFs, DOCX, and other report formats alongside web pages.
- Adaptive summarization prompts – Provide configurable system prompts for different output styles (executive, technical, bullet points).
- Content cleaning & preprocessing – Automatically filter boilerplate, navigation menus, and ads for more accurate summaries.
- Evaluation & feedback integration – Implement user feedback loops and automated quality metrics to continuously improve LLM-generated summaries.
