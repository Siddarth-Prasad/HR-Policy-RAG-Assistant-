# 🏢 HRPolicy Q&A Assistant using Retrieval-Augmented Generation (RAG)

An enterprise-grade, full-stack Question & Answering Assistant designed to answer corporate policy inquiries with factual accuracy and zero hallucinations using **Retrieval-Augmented Generation (RAG)**.

The system ingests internal corporate policy documents, semantically chunks them while preserving hierarchical headings, indexes them into a high-performance vector store, and retrieves the most relevant policy clauses to synthesize factual, grounded answers with citations.

---

## ✨ Key Features
- **Strict Anti-Hallucination Guardrails**: Queries outside company policy trigger an automatic HR Business Partner escalation disclaimer.
- **Explainable RAG Context Inspector**: Inspect the exact vector chunks and similarity percentages used to answer questions.
- **Multi-Stage AI Reasoning Pipeline**: Visual step progression displaying real-time retrieval and verification.
- **Multi-Modal Playback**: Interactive text-to-speech audio with animated equalizer waveforms.
- **Dynamic Policy Ingestion**: Drag-and-drop new Markdown, TXT, or PDF documents to reindex on the fly.
- **Interactive UI Customization**: Switch between visual moods (🌌 Aurora, 🌅 Sunset, 🦄 Cyber) and typography styles (🚀 Tech, ✨ Sleek, 💎 Luxe).

---

## 🛠️ Technology Stack
- **Backend**: Python 3.13, Flask 3.1.3, Flask-CORS
- **Vector Math & ML**: NumPy 2.4.3, Scikit-Learn 1.8.0 ($L_2$ normalized dense cosine embeddings)
- **Frontend**: Vanilla HTML5, Modern CSS3 (Glassmorphism & animated mesh), ES6+ JavaScript
- **Optional LLMs**: Google Gemini (`gemini-1.5-flash`), OpenAI (`gpt-4o-mini`), or Built-in Local Synthesizer

---

## 🚀 Quick Start

### 1. Clone the repository
```bash
git clone https://github.com/<YOUR-USERNAME>/hr-policy-rag-assistant.git
cd hr-policy-rag-assistant

