# 🔍 Probe – Perplexity-Inspired Smart Search Engine

**Probe** is an intelligent search engine that leverages LLMs (Large Language Models), contextual understanding, and real-time web scraping to provide accurate, concise, and citation-supported answers. Designed with a clean, chat-like interface, Probe aims to enhance search experiences through AI-powered query interpretation and response generation.

---

## 🚀 Features

- **LLM-Powered Answers** – Natural language responses using open-source or integrated LLMs.
- **Web Data Extraction** – Scrapes relevant content from the web and provides citations.
- **Contextual Query Understanding** – Improves result accuracy by understanding intent.
- **Responsive Chat UI** – Interactive, clean, and mobile-friendly design.

---

## 🧰 Tech Stack

| Layer        | Technology                |
|--------------|---------------------------|
| Frontend     | React.js                  |
| Backend      | FastAPI (Python)          |
| Scraping     | BeautifulSoup / Requests  |
| LLM Access   | OpenAI API / Custom LLM   |
| Styling      | CSS / Custom Components   |
| Deployment   | Render / Vercel           |

---

## 🛠️ Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/probe.git
cd probe
```

### 2. Backend Setup (FastAPI)

```bash
cd backend
python -m venv venv
source venv/bin/activate   # On Windows: venv\Scripts\activate
pip install -r requirements.txt
uvicorn app.main:app --reload
```

> The FastAPI server runs at `http://127.0.0.1:8000`

### 3. Frontend Setup (React)

```bash
cd frontend
npm install
npm start
```

> The frontend runs at `http://localhost:3000`

---

## 🔄 API Integration Notes

- Ensure the backend is running and accessible to the frontend.
- If using an external LLM API (e.g., OpenAI), store the API key securely (e.g., in environment variables).

---

## 📌 Future Enhancements

- [ ] Add authentication system   
- [ ] Implement advanced filtering for search results
- [ ] Light/Dark Mode Toggle** – Seamless switch between light and dark themes.  

---

## 📄 License

This project is open-source and available under the **MIT License**.

---

## 🤝 Contributions

Contributions, issues, and feature requests are welcome!  
Feel free to fork the repository and open a pull request.

---

## 🧪 Testing

You can test API endpoints using:

- Postman  
- cURL  
- Built-in React UI with input/output testing  

---

## 📬 Contact

For questions or suggestions, please open an issue on GitHub.

<img width="1624" alt="Screenshot" src="https://github.com/user-attachments/assets/3fbf2dc9-6006-45af-9764-094d839f7979" />



