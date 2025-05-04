Analysing Income Statement / Balance Sheet Table with OpenAI
📘 Project Overview
This project automates the extraction and summarization of key financial insights from complex financial documents like income statements and balance sheets using Azure OpenAI, Llama, and LangChain. The solution is designed to help businesses and investors quickly understand a company's financial performance without manually reviewing extensive reports.

🎯 Project Objectives
Automate the parsing and analysis of financial documents.

Generate concise, insightful summaries.

Save time and improve efficiency in financial analysis.

Support data-driven business and investment decisions using AI.

✅ Outcomes
📄 Automated analysis of income statements and balance sheets.

📊 Key performance indicators (KPIs) and financial metrics extraction.

🕒 Time-efficient review of financial documents.

🤖 AI-powered insights for faster and more informed decisions.

🧩 Modules Implemented
1. 📥 Document Ingestion and Parsing
Upload PDFs or document files containing financial statements.

Extract tables and text using tools like PyMuPDF, pdfplumber, or Tabula.

Parse structured data for further processing.

2. 📈 Financial Data Analysis and Insight Generation
Use LangChain and Llama to extract and interpret key financial figures.

Identify revenue trends, cost breakdowns, net profit, margins, etc.

Calculate financial ratios (e.g., Current Ratio, Net Profit Margin).

3. 📝 AI-Powered Summary Creation
Generate human-readable summaries using Azure OpenAI GPT models.

Summaries include performance highlights, risk factors, and key financial indicators.

4. 🌐 Integration and Deployment
Integrate the solution into a web-based interface or API.

Use Streamlit, Flask, or FastAPI for the front end/backend.

Deploy on Azure, AWS, or GCP for scalability.

🚀 Installation & Setup
Prerequisites
Python 3.8+

Azure OpenAI account & API key

Llama or HuggingFace Transformers

LangChain library



# Install dependencies
pip install -r requirements.txt
📂 Directory Structure
bash
Copy
Edit
financial-analyzer-ai/
├── data/                     # Sample financial statements
├── docs/                     # Documentation
├── src/
│   ├── ingestion.py          # Document ingestion logic
│   ├── parser.py             # PDF/table parsing
│   ├── analysis.py           # Financial metric extraction
│   ├── summarizer.py         # AI summarization using GPT
│   └── app.py                # Main application logic
├── requirements.txt
└── README.md
🔐 Environment Variables
Create a .env file in the root directory with:

🧪 Example Usage
Upload a PDF containing a balance sheet.

The parser extracts key data tables and text.

The analysis module computes financial ratios and highlights.

The AI model generates a summary:

"The company's revenue increased by 12% YoY..."

"The current ratio improved, indicating better liquidity."

📈 Future Enhancements
Support for cash flow statements.

Export summaries to Excel or PDF.

Multilingual document support.

Integration with financial dashboards (e.g., Power BI).

📜 License
This project is licensed under the MIT License. See LICENSE for more information.
