🌾 AgriExport AI – Intelligent Agricultural Export Assistant

AgriExport AI is a Retrieval-Augmented Generation (RAG) based AI assistant designed to provide reliable information about agricultural crop exports, trade regulations, and market insights.

The system retrieves relevant knowledge from a vector database built from agricultural documents and uses an AI model to generate structured, professional responses for farmers, traders, and exporters.

🚀 Features

AI-powered agricultural export advisory

RAG architecture for accurate knowledge retrieval

Document knowledge base built from PDF export reports

Supabase Vector Database for semantic search

n8n workflow automation for backend orchestration

Structured HTML formatted responses

Fast responses using OpenAI GPT models

Easily extendable knowledge base

🧠 How It Works

The system uses a Retrieval-Augmented Generation (RAG) pipeline to ensure responses are grounded in real documents.

Architecture Workflow
User Query
     ↓
Webhook Trigger (n8n)
     ↓
Embedding Generation
     ↓
Supabase Vector Search
     ↓
Relevant Document Retrieval
     ↓
AI Agent (OpenAI)
     ↓
Structured Response Generation
     ↓
Chat Interface Response
📂 Knowledge Base

The knowledge base consists of agricultural export documents including:

crop export policies

WTO trade reports

SPS regulations

agricultural market insights

Documents are processed using:

PDF Loader → Text Splitter → Embeddings → Supabase Vector Store
🛠 Tech Stack

n8n – Workflow automation & AI agent orchestration

Supabase – Vector database for semantic search

OpenAI API – LLM and embeddings

HTML / JavaScript – Chat interface

RAG Architecture – Retrieval-Augmented Generation

📊 Key Capabilities

The assistant can answer questions such as:

Wheat export requirements

Cotton export market insights

Agricultural trade regulations

Global crop export trends

SPS and MRL compliance issues

⚡ Performance

Average response time: ~2–4 seconds

Context-aware answers using semantic document retrieval

Structured and professional output formatting

📌 Future Improvements

Planned enhancements include:

Conversation memory support

Metadata-based document filtering

Source citation for retrieved documents

Faster response optimization

Multi-language support

📜 License

This project is open-source and intended for educational and research purposes.

👨‍💻 Author

Developed as an AI project exploring RAG architecture for agricultural trade intelligence systems.

You can try the AI assistant by visiting the live chat interface: https://nasir-ali911.github.io/Agri-export-agent-v2/

