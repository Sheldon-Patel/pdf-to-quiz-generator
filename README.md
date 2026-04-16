# 📄 PDF ➜ Quiz Generator

An interactive, browser-based application that converts PDF documents into quizzes instantly. Built with a focus on core NLP principles without relying on traditional LLM architectures.

### 🏆 Hackathon Edition (Zero-LLM)
This project was built to comply with strict hackathon rules regarding AI usage:
- **No LLM APIs:** Zero calls to OpenAI, Gemini, or Claude.
- **No Cloud Dependencies:** Works 100% offline in the browser.
- **Math-Based Logic:** Uses TF-IDF algorithms for importance ranking.
- **Rule-Based NLP:** Uses linguistic rules (not neural networks) for terminology extraction.

## 🚀 Features
- **Instant Extraction:** Reads PDFs page-by-page using PDF.js.
- **Smart Ranking:** Phrases are ranked by TF-IDF (Term Frequency-Inverse Document Frequency) to find the most "quiz-worthy" sentences.
- **3 Question Types:**
  - **Multiple Choice:** Distractors are pulled dynamically from other parts of the document.
  - **True/False:** Logic-swapping nouns to create challenging false statements.
  - **Fill-in-the-Blank:** Entity recognition to identify key concepts.
- **Interactive UI:** Real-time scoring, feedback, and context-sentence verification.

## 🧠 The Tech (No-AI Explanation)
To achieve "intelligence" without a Large Language Model, we use:
1. **PDF.js:** For binary parsing of PDF files.
2. **Custom TF-IDF Algorithm:** A statistical measure used to evaluate how important a word is to a document.
3. **Compromise.js:** A rule-based Natural Language Processing library that performs tokenization and part-of-speech tagging using predefined linguistic patterns.

## 🛠️ How to Run
1. Download or clone this repository.
2. Open [index.html](cci:7://file:///Users/ronnierodricks/.gemini/antigravity/scratch/pdf-to-quiz/index.html:0:0-0:0) in any modern web browser (Chrome, Firefox, Safari).
3. Upload a text-based PDF and generate your quiz!

