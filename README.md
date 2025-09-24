# 📚 AI Flashcard Maker (Colab + Hugging Face)

An **AI-powered flashcard generator** that creates Q&A, Multiple-Choice, and True/False cards on any topic.  
Built entirely in **Google Colab** with **Hugging Face Flan-T5** models — **no OpenAI API key required**.

---

## 🚀 Features
- Generate flashcards from **any topic** using natural language.
- Three card types:
  - ❓ Q&A  
  - 📝 Multiple Choice (4 options)  
  - ✅ True/False  
- **Ultra-Fast mode** using `flan-t5-small` (lightweight & free).  
- Interactive **Gradio UI** inside Colab.  
- Export decks to:
  - CSV  
  - JSON  
  - TSV (Anki-compatible)  
- Optional Google Drive integration for saving decks.  

---

## 🛠️ Setup
1. Open the notebook in **Google Colab**.  
2. Switch to a **GPU runtime**:  
   - `Runtime → Change runtime type → GPU`  
3. Run the cells step by step:  
   - Definitions (Cells 1–7)  
   - Ultra-Fast generator cell  
   - Gradio UI cell  

---

## 📊 Usage
- Enter a **topic** in the text box (e.g., `"Random Forest"`).  
- Choose how many Q&A, MCQ, and True/False cards you want.  
- Click **Generate Deck**.  
- Preview appears in the notebook + export paths are listed.  

Example output:

Generated 11 cards for Random Forest
CSV: random_forest.csv
TSV: random_forest_anki.tsv
JSON: random_forest.json


---

## 📦 Exports
- **CSV** → easy to view or edit in Excel/Sheets.  
- **TSV** → directly import into [Anki](https://apps.ankiweb.net/).  
- **JSON** → structured storage for programmatic use.  

---

## 🖼️ Screenshots
*(Add screenshots of your Colab and Gradio UI here)*

---

## 📈 Extensions (Future Work)
- Add **Spaced Repetition (SM-2)** scheduling.  
- Export to **DOCX** for printable flashcards.  
- Add a **dashboard with analytics** (distribution of card types, word counts).  
- Batch deck generation for multiple topics.  

---

## 🧑‍💻 Tech Stack
- Python 3 (Colab)  
- [Transformers](https://huggingface.co/transformers/) (Flan-T5 models)  
- [Gradio](https://gradio.app/) for UI  
- Pandas, JSON, Regex for data handling  

---

## 📜 License
MIT License — feel free to fork, modify, and use.

---

Built by Janhavi Patil 
