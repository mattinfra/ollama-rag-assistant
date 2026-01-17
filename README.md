## 🎯 Why this project?

Large Language Models often hallucinate when answering domain-specific questions.
This project demonstrates how to mitigate hallucinations using a
**Retrieval-Augmented Generation (RAG)** architecture with a **local LLM**.

The chatbot answers questions about a pizza restaurant **only using relevant reviews**
retrieved from a vector database.

## 🧪 Prompt Design

The model is instructed to behave as a domain expert and receives:
- Retrieved restaurant reviews
- The user question

This ensures grounded and context-aware answers.

## 📌 Why RAG instead of fine-tuning?

- Faster iteration
- Lower computational cost
- Easier domain updates
- No model retraining required

This makes RAG ideal for dynamic, review-based knowledge.

## 🚧 Future Improvements

- Web UI (Streamlit / React)
- REST API with FastAPI
- Conversation memory
- Source citations in responses
- Dockerized deployment
