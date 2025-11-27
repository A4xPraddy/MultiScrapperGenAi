# 🧠 Multi Scrapper AI — All-in-One Content Scraper + AI Parser

Multi Scrapper AI is an advanced, Streamlit-powered content intelligence tool that can scrape, parse, summarize, and analyze data from:

✔ YouTube Videos <br>
✔ PDF Documents  <br>
✔ Websites/HTML Pages  

It uses Gemini 2.0 Flash and Ollama-based LLM parsing to help users extract insights, answer questions, and create summaries—turning long content into instant knowledge.
Built for students, researchers, developers, and general users who want quick insights from long content without manual reading.

# ✨ Features
## 🎥 YouTube Video Summarizer

Extracts transcripts using YouTube Transcript API
Detects all available transcript languages automatically
Summarizes using Gemini 2.0 Flash
Clean, structured output with subheadings
Thumbnail preview + Download Summary option

## 📄 PDF Content Parser

Extract text using PDFMiner / PyPDF2
High-accuracy extraction even from complex PDFs
Shows full extracted text in an expandable view
Supports deep question-answering with Ollama

## 🌐 Website Scraper + AI Parser

Scrapes webpage content using:
requests
BeautifulSoup
Extracts only relevant <body> content
Cleans, splits, and prepares DOM text
AI parsing using Ollama models
Useful for SEO research, content extraction, competitor analysis, etc.

## 🤖 Dual AI Engine
### Gemini 2.0 Flash

#### Used for:
YouTube transcript summarization
Fast and accurate content understanding
Ollama LLM

#### Used for:

Website content parsing
PDF question answering
Custom extraction tasks

# 🏗️ Tech Stack

### Backend / Logic

Python
Streamlit
Requests
BeautifulSoup
YoutubeTranscriptApi
PDFMiner / PyPDF2
Langcodes

### AI Models

Gemini 2.0 Flash (Google Generative AI)
Ollama Models (Local/Hosted)ed data.

# 📁 Project Structure
📦 multi-scrapper-ai
│
├── main.py                # Streamlit application (UI + logic)
├── scrape.py              # Web scraping utilities
├── parse.py               # Ollama-based content parsing
├── requirements.txt
└── README.md

# ⚙️ Installation
## 1️⃣ Clone the repository
git clone https://github.com/A4xPraddy/MultiScrapperGenAi.git
## 2️⃣ Install dependencies
pip install -r requirements.txt
## 🚀 Run the App
streamlit run main.py


# 🔥 How It Works
### 1. Select input type

YouTube link
PDF file
Website URL

### 2. System extracts content

Fetch transcript
Extract PDF text
Scrape website body

### 3. AI analyzes content

Generate structured summaries
Extract custom information
Answer user questions
Convert raw text into knowledge

### 4. Download / view results

Summaries
Parsed results
Extracted content

### 🎯 Use Cases

✔ Students preparing notes<br>
✔ Researchers analyzing multiple sources<br>
✔ Content writers or SEO analysts<br>
✔ Journalists fact-checking content<br>
✔ Developers building AI-assisted tools<br>
✔ Anyone wanting quick understanding of long content<br>


