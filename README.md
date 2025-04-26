
# 📊 MarketGenAI-Agent: Multi-Agent System for AI Use Case Generation and Research

## 🚀 Project Overview
Developed for **InstaResz Business Services Pvt. Ltd.**, MarketGenAI-Agent is a Multi-Agent Architecture System that performs:
- Web scraping of company/industry information
- AI-powered Q&A over scraped content
- AI/ML/GenAI use case generation
- Resource asset collection for datasets and research references

The goal is to empower organizations to discover actionable AI opportunities and improve operations, supply chain, and customer experience using Generative AI.

## 🏗️ Features
- 🔍 **Web Scraping**: Scrape industry-specific news, insights, and company profiles.
- 🧠 **AI-Powered Insights**: Answer complex research questions using Google Gemini LLM.
- 📚 **Text Processing**: Chunk and embed content into a searchable FAISS database.
- 🔗 **Resource Asset Collection**: Prepare links to datasets and references.
- 🖥️ **Interactive UI**: Easy-to-use Streamlit-based interface.

## 🛠️ Tech Stack

| Technology              | Purpose                          |
|--------------------------|----------------------------------|
| Streamlit                | Web Interface                   |
| BeautifulSoup            | Web Scraping                    |
| Requests                 | HTTP Requests                   |
| LangChain                | Chunking & Vector Storage       |
| Google Generative AI API | Q&A and Text Generation         |
| FAISS                    | Vector Similarity Search        |
| UnstructuredURLLoader    | Additional URL Data Loading     |

## 📂 Project Structure
```
├── app.py            # Main Streamlit Application
├── gen.py            # Simplified version for basic scraping
├── geni_hlp.py       # Helper for Unstructured URL loading
├── requirements.txt  # Python dependencies
├── faiss_index/      # (Generated at runtime) Vector DB
└── README.md         # Project Documentation
```

## 🔥 How to Run Locally

### 1. Clone the Repository
```bash
git clone https://github.com/your-username/marketgenai-agent.git
cd marketgenai-agent
```

### 2. Install Requirements
```bash
pip install -r requirements.txt
```

### 3. Run the App
```bash
streamlit run app.py
```

## ✨ Screenshots
(Add screenshots after running your Streamlit app!)

Example sections to add:
- Homepage UI
- Query Section
- AI-Powered Response Section

## 📄 Deliverables
- ✅ Source Code
- ✅ Research & Proposal Report
- ✅ Architecture Flowchart
- ✅ Demo Video (to be recorded)

## 📈 Future Enhancements
- Automatic dataset search from Kaggle, HuggingFace
- Auto-generate full client report
- Deploy on Streamlit Cloud
- Integrate competitor analysis agent

---

> Built with ❤️ by Himanshu Kasera for InstaResz Business Services Pvt. Ltd.
