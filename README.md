# Simple GenAI RAG Application

This application allows you to upload PDF documents and ask questions about them.

## Workflow

1.  **Upload**: Go to the Upload page and select a PDF file. The system extracts the text from the PDF.
2.  **Query**: Go to the Query page (Home). Type a question related to your uploaded documents.
3.  **Answer**: The system searches through the document text and provides an answer based on relevant snippets.

## Architecture

-   **Frontend**: React (Vite) with Shadcn UI.
-   **Backend**: Node.js with Express.
-   **Storage**: In-memory storage for documents and text.
-   **RAG Logic**: Simple keyword-based retrieval (Simulated RAG).

## Note on Python/AI

Due to environment restrictions on the Replit free tier preventing the installation of heavy Python ML libraries (PyTorch, Transformers), this application uses a Node.js backend with a simplified retrieval logic instead of the full Python/FAISS stack originally planned. It effectively demonstrates the full application flow (Upload -> Process -> Query -> Response).
