# 🤖 Multimodal RAG Chatbot

This project is a Retrieval-Augmented Generation (RAG) chatbot built using LangChain and Gradio, extended to handle **multimodal PDF inputs** (text + images) and **evaluate its own answers** with an internal grading pipeline.

> Built as part of my AI/ML internship — combining LLMs, CV, and real-world UX.

---

## Features

- **Text-based RAG** from PDF content using LangChain
- **Image extraction & filtering** from PDFs using PyMuPDF + OpenCV
- **Image captioning** via Gemini Flash (multimodal LLM)
- **Captions added to vector store** so the chatbot can reference diagrams
- **Internal response grader**:
  - Loads test questions from a CSV
  - Compares chatbot's answers to gold responses
  - Grades responses using a second Gemini LLM call

---

## Technologies Used

* LangChain
* Gradio
* Gemini 2.0 Flash (for image captioning & grading)
* PyMuPDF
* OpenCV
* Pandas

---

## Acknowledgements

Built during my internship under the mentorship of Mr. Deepak Rawat from DeepKlarity.
This project taught me how to combine computer vision, LLMs, and UX — and I’m incredibly grateful for the experience!

---
