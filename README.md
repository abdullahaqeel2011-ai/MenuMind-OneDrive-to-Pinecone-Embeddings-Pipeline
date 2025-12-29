# MenuMind-OneDrive-to-Pinecone-Embeddings-Pipeline
🧠 MenuMind – OneDrive to Pinecone Embeddings Pipeline

MenuMind is an automated n8n workflow that searches documents from Microsoft OneDrive, downloads them, converts their content into OpenAI embeddings, and stores them in a Pinecone vector database for fast and accurate semantic search.

✨ Key Features

🔍 Automatic File Search
Searches OneDrive for files using a keyword (e.g., Menu)

📥 Instant File Download
Downloads matched files directly inside the workflow

📄 Smart Document Parsing
Extracts usable text from documents using a default data loader

🧠 OpenAI Embeddings
Converts text into high-quality vector embeddings

📦 Pinecone Vector Storage
Stores embeddings in a Pinecone index for retrieval and RAG use-cases

⚡ One-Click Execution
Trigger the entire pipeline manually with a single click

🧩 Workflow Components

🟢 Manual Trigger – Starts the workflow

☁️ Microsoft OneDrive – Searches & downloads files

📄 Document Loader – Converts files into readable text

🧠 OpenAI Embeddings – Generates vector embeddings

📌 Pinecone Vector Store – Saves vectors into an index

🚀 Use Cases

🍽️ Restaurant menu semantic search

🤖 RAG-based chatbots

📚 Knowledge base indexing

🔎 AI-powered document search

🧠 Context injection for LLM applications

🛠 Requirements

✅ n8n (self-hosted or cloud)

✅ Microsoft OneDrive OAuth credentials

✅ OpenAI API access

✅ Pinecone account & index

⚙️ How It Works (Execution Flow)

▶️ Trigger workflow manually

🔍 Search OneDrive for matching files

📥 Download file contents

📄 Extract text data

🧠 Generate embeddings via OpenAI

📦 Insert vectors into Pinecone index

📌 Notes

Index name is configurable (default: menu)

Supports scalable document ingestion

Ideal for AI search and chatbot backends

📄 License

🆓 Free to use and modify

📌 Attribution recommended

👤 Author

Abdullah Aqeel

AI Automation Engineer | Software Quality Assurance Engineer (SQAE)
