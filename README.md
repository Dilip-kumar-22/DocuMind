# 🧠 DocuMind: AI-Powered Document Intelligence

DocuMind is a modern web application that allows you to upload your documents (PDF, DOCX, TXT) and interact with an AI that possesses a complete understanding of their content. It's like having a personalized ChatGPT for your own knowledge base.

This project is designed to be a powerful, local-first tool for researchers, students, and professionals to intelligently query and interact with their private documents.

---

### ✨ Features

*   **Secure & Private:** Your documents are processed and stored locally. Nothing is sent to a third-party service.
*   **Multiple File Formats:** Supports `.pdf`, `.docx`, and `.txt` file uploads.
*   **Conversational AI:** Engage in a natural language conversation with your documents. Ask questions, summarize content, and extract key information.
*   **Modern UI:** A sleek, responsive, and intuitive interface built with Next.js and Tailwind CSS.
*   **High-Performance Backend:** Powered by a FastAPI server, ensuring rapid and efficient API responses.

---

### 🛠️ Technology Stack

*   **Frontend:** [Next.js](https://nextjs.org/) & [TypeScript](https://www.typescriptlang.org/)
*   **Styling:** [Tailwind CSS](https://tailwindcss.com/)
*   **Backend:** [Python](https://www.python.org/) with [FastAPI](https://fastapi.tiangolo.com/)
*   **AI Core:** [LangChain](https://www.langchain.com/) for document processing, embeddings, and conversational logic.
*   **Vector Storage:** [ChromaDB](https://www.trychroma.com/) for efficient local similarity search.

---

### 🚀 Getting Started

**Prerequisites:**

*   Node.js & npm (or yarn)
*   Python 3.9+ & pip
*   Git

**Installation & Setup:**

1.  **Clone the repository:**
    `git clone https://github.com/YOUR_USERNAME/DocuMind.git`
    `cd DocuMind`

2.  **Setup Backend:**
    `cd backend`
    `pip install -r requirements.txt`
    `uvicorn main:app --reload`

3.  **Setup Frontend:**
    `cd ../frontend`
    `npm install`
    `npm run dev`

---

###  Roadmap

*   [ ] User authentication
*   [ ] Support for more file types (e.g., `.csv`, `.md`)
*   [ ] Dockerize for one-click deployment
*   [ ] Integration with cloud vector databases (e.g., Pinecone)
