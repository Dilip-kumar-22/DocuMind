# DocuMind 🧠

> Your personal AI-powered document assistant. Upload your files and start a conversation.

DocuMind is a sophisticated, full-stack application that leverages Retrieval-Augmented Generation (RAG) to allow users to "chat" with their documents. Upload PDFs, DOCX, or TXT files and ask questions to get instant, context-aware answers from an AI that has mastered your content.

## Core Features

-   **Multi-File Support:** Upload various document formats (`.pdf`, `.docx`, `.txt`).
-   **Intelligent AI Chat:** Ask complex questions and receive accurate answers based on the document's content.
-   **Modern UI:** A clean, responsive, and intuitive interface built with Next.js and Tailwind CSS.
-   **High-Performance Backend:** A robust and scalable API powered by Python and FastAPI.

## Tech Stack

-   **Frontend:** Next.js & TypeScript
-   **Styling:** Tailwind CSS
-   **Backend:** FastAPI (Python)
-   **AI Core:** LangChain
-   **Vector Storage:** ChromaDB

## Project Structure

This project is a monorepo containing two main components:

\`\`\`
/DocuMind
|-- /client     # The Next.js frontend application
\`-- /server     # The FastAPI backend server
\`\`\`

This structure allows for clear separation of concerns while keeping the entire project within a single, manageable repository.
