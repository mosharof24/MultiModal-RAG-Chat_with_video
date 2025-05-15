# 🎥 Chat With Video – Multimodal RAG Prototype

A research prototype exploring Multimodal Retrieval-Augmented Generation (RAG) by enabling users to chat with video content. This system combines vision, language, and audio understanding to deliver natural and context-aware interactions with videos.
✨ Features

    🔊 Speech-to-Text: Uses OpenAI's Whisper to generate transcripts from video audio.

    🧠 Multimodal Embedding:

        Pipeline 1: Embeds captions using BridgeTower (Hugging Face).

        Pipeline 2: Combines captions and video frames with LLaVA for richer context.

    📦 Vector Storage: Stores embeddings in ChromaDB for fast and efficient retrieval.

    💬 Video Chat Interface: Enables users to ask questions about the video and retrieve relevant moments using semantic similarity.

🛠️ Tech Stack

    Python

    Hugging Face Transformers (BridgeTower)

    OpenAI Whisper (for ASR)

    LLaVA via Ollama

    ChromaDB

    Streamlit (optional, for UI)
